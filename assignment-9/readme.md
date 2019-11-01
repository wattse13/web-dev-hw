# Assignment 9

## Created by Eli Watts for MART 341, Sect. 50

### Questions:

*Describe the difference between the universal, element, class, and id selector types. When might you choose one over the other to style content?*


Universal, element, class, and id selector types create a spectrum of specificity – universal being the most general and id being the most specific. Using the universal selector will apply style to all elements, the element selector will apply style to all instances of the selected element, the class selector will apply style to all instances of the selected class, and the id selector will apply style only to the element with the selected id. Style choices, like font or background color, that need to be the same across multiple webpages can be styled using general selectors, like the universal or element selector, whereas style choices that may only apply once to a single element can be styled with specific selectors like id selectors.


*Briefly discuss your color palette, including the 3 colors you chose. List their color names, rgb values, or hex codes.*


#F22786 pink/red, #05DBF2 light blue, and #F2B705 orange yellow, dominate the large background image I chose for my website. Like many color palettes in the 1980’s, this color palette is aggressively bright. Using [Adobe Color Wheel](https://color.adobe.com/create), I was able to submit the image and find the individual hex codes for reach color. This helped me use colors found in the background in other aspects of my website, like the heading and opaque background. Originally, I used the #F2B705 orange yellow to write out, “in the” in my heading, but that pushed my website from playfully tacky and kitsch into actually headache inducing.


*Free Response: Summarize your work cycle for this assignment.*

After setting up the standard parts of my webpage – basic structure, header, meta elements, and body – I struggled for a long time to set up a background image that took up the entire browser background, but created neither vertical nor horizontal scroll bars.

First, I began by creating an HTML `div` element, in which I used the `img` element to source, describe, and title the image I wanted to use for my background. Then, after creating a link to a stylesheet in the HTML `head` element, I created some style elements within the style sheet to position my image correctly.

I looked at some outside sources, like Stack Overflow, and found some suggestions on how to make it work. In my CSS style sheet, there are two style elements that both select the html element with the ID name backgroundImage. In the first CSS style element the `<div id=”backgroundImage>` is selected for using the `#` symbol. The backgroundImage element is fixed in place and extends beyond the left and bottom part of the browser window. This ensures no white spaces will be left between the image and the borders of the browser window. The next CSS element, `# backgroundImage img {}` targets the image within the `<div id=”backgroundImage>` element. It is positioned absolutely using the top, bottom, left, and right properties. The min-width and min-height properties ensure the image remains at full size.

With the background image placed where I wanted, I began working on the rest of my website. I uploaded a picture to the [Adobe Color Wheel](https://color.adobe.com/create) and used the hex codes and rgb codes to add color to my website’s text. Much of this is done in the `.container {}` `h1 {}` and `h3 {}` elements. Using properties like background color, and color I was able to add more color to my already overwhelmingly colorful website. In the `.container {}` element, I used the font-family property and gave it a value of sans-serif. This value is then inherited by other elements like the `h1 {}` and `h3 {}`. 
