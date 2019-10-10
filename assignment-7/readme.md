# Assignment 7

## Created by Eli Watts for MART 341, Sect. 50

### Questions:

*Briefly describe the difference between divs, classes, ids, and spans.*

Divs, classes, ids, and spans all help web developers section off parts of their website. Divs are useful for blocking off large blocks of elements like headers, paragraphs, and other associated content. Divs can contain other nested divs, classes, ids, and spans. Classes are used to define groups of specific elements. Elements may have multiple class distinctions and using classes makes styling similar elements with CSS easier. Ids use strings to add a unique identifying attribute to an element. They work similarly to classes, but provide allow web developers to identify single important elements rather than groups. Spans are like divs, but they create inline groups rather than block groups. Spans are useful for marking text that needs to be styled differently from surrounding text.

*What is "alt text," and why do we use it?*

Alt text is a written description of an image. Unlike an image caption, alt text does not appear on the webpage unless there is a problem loading the image it describes, or an individual is using screen reading technologies. Alt text is used as an alternative for people who cannot see the intended image due to a slow internet connection that cannot load the image, or due to physical limitations like blindness.

*Free Response: Summarize your work cycle for this assignment.*

I started this assignment by creating my webpage's essential structure and adding some meta information. The meta information provides information about who made my webpage, what kinds of contents it contains, and how it should be displayed. As instructed, I created a `<style>` element in the `<header>` and copy pasted some provided code.

Using `<div>` elements I created different sections for my webpage. These sections contained different kinds of content like embedded videos, contact information, and lyrics. The `<div>` elements allowed me to style my webpage sections in different ways and also helped keep my code organized.

To embed videos, audio players, and a google map I used the `<iframe>` element. Unfortunately, the music video I embedded does not play, as there is some sort of frame killer preventing it from running outside of YouTube.

 When adding the video with the `<video>` element, I wanted to include information about the file type so that my webpage would have an easier time telling different web browsers if the file was compatible. I was able to include file type information but could not find out what type of codec information was used. As a back-up, I used multiple video file types to try and ensure accessibility across different browser types and used a poster attribute image to display the UofM Media Arts Logo on the video player. I chose not to turn on autoplay, because autoplaying videos are the worst.

 To make sure my lyric content did not use any characters that are usually reserved for coding, like the &#91; bracket &#93; characters, I copied my chosen lyrics into a word document. There I used the find and replace function to replace all problematic characters with their corresponding escape characters.

 Finally, I made sure my `<image>` element had alt text that described the image, which makes it more accessible to people using screen readers or people whose internet cannot load the image.
