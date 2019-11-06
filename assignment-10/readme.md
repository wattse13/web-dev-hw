# Assignment 10

## Created by Eli Watts for MART 341, Sect. 50

### Questions:

*What is the difference between a system font, web font, and web-safe font?*

System fonts are available locally on a user’s computer, or other device, but may be limited in web-use due to licensing. When using system fonts it is important to keep cost, and load times in mind as it may be necessary to pay licensing fees and because they must be exported as images, which increases loading time. As system fonts may be exported as images, it is important to include either alternative text or an alternative header for individuals relying on screen readers.

Unlike system fonts, web fonts are not necessarily stored locally on a user’s computer, or other device. Instead, they are stored on servers and can be accessed using certain `CSS` elements. Although they are designed for web use, different web-browsers may struggle to render certain fonts or may be unable to render certain font files.

Web-safe fonts operate similarly to web fonts but are more consistently found on different operating systems like Windows and Mac. The high availability of web-safe fonts lessens loading times and helps ensure the developers intended font is displayed.

*What is the importance of having fallback fonts or a font stack?*

Different operating systems, like Mac and Windows, come with different available fonts. If a developer choses a font that is not available on the end user’s computer, then the developer’s website may not display correctly. Including fallback fonts or a font stack helps developers control how their website will look if the font they originally planned on using is not available on some end users’ computers. For example, if Merriweather is not available on a user’s computer, including `serif`, or a different font in the serif family, will ensure the font the end user’s computer replaces the missing font with still works within the developer’s intended typography landscape.

*Free Response: Summarize your work cycle for this assignment.*
I began by creating my web page’s basic structure, by adding four elements of meta information, and by linking two CSS style sheets – one for fonts and one for general style. I chose to link two style sheets within the `head` element to get in the habit of separating font style elements from more general style elements.

In the body element I used `div’s` to break my content up into sections. I assigned most `div` elements the class `container` so that I could later select for those elements in the `css.style` sheet and give them a consistent style.
Positioning my image was difficult. I would have liked to vertically center the book title, author, and publication date next to my image, but the `vertically-align` element in my `font.css` style sheet seemed to have no effect on where my text displayed on my webpage. There is a chance this is because the image and the text I was trying to vertically align to the image were both in the same `div` element.

After adding content, structuring it, and giving it some color, I began to focus more on my webpage’s fonts. For the book title, I used Carbon Type which I downloaded from fontsquirrel. I used the `@font-face` element and included many different file types in the source attribute, to help ensure the font displays correctly across different web browsers and operating systems.

Once I had my `@font-face` element properly formatted I used the `carbontype` as an attribute in an element that styled the font in my webpages `#mainTitle{}`. Although I was sure that I included many types of font file formats, I also included some fallback fonts in the `font-family` element as a further back-up in case my intended font did not load correctly. On the course website, it says that system fonts, like the one I used for my webpage’s title, are difficult for screen readers to interpret as they must be exported as images. While I’m not sure this is correct, I added alt text to my `h1` element and I added a second `h1` which I made invisible by indenting it ‘off’ the page by giving the `text-indent` element a negative value. I hope one or the other technique will work with a screen reader.

Because I used a separate `font.css` style sheet, I decided to use the @import method of adding other fonts to my webpage. After adding the correct links from Googlefonts and Adobe Typekit to my `font.css` style sheet, I could then reference them in other `font.css` style elements.

When adding values to style attributes, like `text-size` I tried to use percentages as often as possible. Percentages ensure that if an end user zooms in or out of the web browser the size relationships between headers and body text will remain the same even if the increase or decrease in size.

Finally, I used pseudo elements and classes to add some more style to my text. The pseudo `visited` and `hover` style elements, change the link’s appearance based on if the mouse cursor is hovering over it or if it has been clicked on. I had to use the link element `a` selector, rather than a more specific `.` class selector. Using the `.` class selector changed my link’s style correctly, but did not change its color. Pseudo elements are also used to increase the size of the first letter of my first paragraph and to color the first line of my first paragraph. As both use the pseudo selector `first-child` `first-line`/`first-letter` even if a new preceding paragraph or letter are added, the style will shift to the new first letter or first line accordingly.
