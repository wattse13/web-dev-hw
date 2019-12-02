*Who was your imaginary client? How did they describe their site needs?*

When speaking with my client, they expressed that they were a writer currently experiencing debilitating amounts of writer’s block and that they would like those who visited their website to feel just as blocked.
To achieve this, I started with the site title. A large image divides the site title into two parts and pushes them apart, which makes it hard to read clearly. When scrolling, the website navigation bar scrolls with, and blocks out everything it sits on top of. In the library dropdown menu, I chose to include links that encourage the development of writer’s block in everyone who visits them. They include:

* The Library of Babel: Everything that can be written already has been, so why bother?

* Elsewhere.org: Even an algorithm can write now, so why can’t you?


* The Onion: Nothing like a healthy dose of cynicism to stop those creative juices.


I chose muted colors that felt like the life had been taken out of them and the layout itself is block shaped. When looking through some of my previous websites, my client mentioned that they liked the font I used in a previous project as it reminded them of typewriter font which is related to writing. I agreed and chose to use a monotype font for their website as well.

*What is the difference between display: block, display: inline, and display: inline-block?*

Changing an elements display property changes how an element will interact with other neighboring elements. Elements using the inline rule stop forcing new lines, ignore margins and width properties, and flow with the other elements on the screen. The inline-block rule mixes inline and block features. Elements using the inline-block rule can sit next to block elements that would otherwise force a new line, will respect margins of other elements, and will horizontally expand to fill parent elements unless their width property is defined. Finally, the block rule can turn inline elements into block elements that force new lines even when there is enough horizontal space to display the elements side by side.

*Free Response: Summarize your work cycle for this assignment.*

I struggled a lot with this assignment. I started and deleted at least three previous attempts before finally finishing the website I am now submitting. Positioning elements created many problems for me, especially when I zoomed in and out of my web browsers. I thought setting element sizes with percentages would give my website a more responsive design, but instead, it just led to a lot of positioning problems when I viewed my web page on different sized screens. In the end, I used a mixture of pixels and em’s to keep things positioned how I wanted them.

After creating each webpage’s basic structure and meta elements, I focused on things I wanted to include on every page, like the navigation bar. I created a `div` element and wrapped it around the all lines of code I used to create the navigation bar. Within the parent `div` I also wrapped each navigation bar element in a `div` which later gave me greater control on how I styled my navigation bar. In my `index.css` style sheet, I used both class and ID selectors to apply changes to different parts of the navigation bar. I used a fixed position, which causes the navigation bar to follow the user down they screen when they scroll, gave it a `z-index` value of 1, which causes it to appear above other elements, and forced the links to behave as `inline-blocks`, which allows them to sit next to each other and also to respect each other’s margin and width values.

Creating elements that reacted to a hovering cursor also proved a little difficult, especially the dropdown menu. Despite the pseudos I used to turn visited links a different color, their color does not change after being clicked on. I think this may be because the text used to write the links inherits a different color value from the `font.css` stylesheet. The dropdown menu took a lot of experimenting to get to work correctly. When I used the code provided on the website as a reference, I ended up creating a drop-down menu that disappeared before I could click on any of the hidden links. Changing, or removing some of the margin and padding properties eventually resulted in a usable dropdown menu.

After spending a lot of time creating the navigation bar, I began working on the rest of the site. I wanted a big picture to break up the site’s title. I accomplished this by breaking up the site’s title into separate `div` elements. In the stylesheet I could then use different text align properties to place the text where I wanted it.

On the contact page, I wrapped a `fieldset` element around all the individual parts of my contact form. I also gave it the property of `get` as most of the comments being left were short and did not contain sensitive information like passwords or financial information.

My website uses a total of three stylesheets. One for fonts, one for the home and contact page, and one for the library and about page. Originally, I planned on making my pages look different from one another, but the two non-font stylesheets ended up being almost identical. In the future, I think I will stay away from organizing stylesheets based on the webpages and lean more towards organizing them based on what they style, i.e. fonts, colors, etc.
