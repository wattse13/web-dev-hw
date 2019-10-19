# Assignment 8

## Created by Eli Watts for MART 341, Sect. 50

### Questions:

*Briefly recap your experience learning HTML. What was old, new, interesting, or difficult to learn?*

Before starting this class, I knew nothing about HTML. I had previously taken an introduction class to JavaScript so some topics were familiar, like git-hub, version control, and text editors, but most things were completely new to me. When I first signed up for this class, I was a little worried that I would find it as difficult as I found learning JavaScript. However, I feel somewhat confident that I understood most of the topics covered so far.
One topic I found particularly interesting, and somewhat difficult, are elements like `<div> and <span>`. I like the idea of being able to section off different parts of a website in order to group similar things together, and to make styling easier to apply consistently across all parts of a website. While I find grouping elements interesting, I still struggle with using the `<style>` element to change the appearance of referenced elements. Part of this confusion may be because I am not always sure which grouping element to use, I do not know how to reference elements based on their `<div> id=””`, and I am not always sure what elements I should group together.

*Next module we begin CSS and expand on styling, which helps us "decorate" HTML. Is there anything you're anxious or excited to learn about in this new section?*

For the most part, I am looking forward to learning more about CSS. One aspect I am excited to learn about in particular is positioning. When putting together this assignment, I often felt like my solutions to formatting problems were kind of hack-y. For example, the images I used often laid over the top of other elements. To get around this problem, I used the `<br />` element to give everything adequate space. Using the `<br />` element worked, but I feel like there must be more elegant solutions to making sure everything is positioned correctly.
I am a little worried that things are going to ramp up in complexity. While I am fairly confident I understand most of what we learned, I feel like I still struggle with the `<style>` element and id/class tags.

*Free Response: Summarize your work cycle for this assignment.*

As with all webpages, I began with the four main document elements -- `<html>, <head>, <title>, and <body>` --, and then added the four main meta elements inside the `<head>` element. The four main document elements add basic structure to my webpages and the four main meta elements describe the content of my webpages.

Next, I began adding content and additional structure to the main page of my instructables website. To make styling my website easier and more consistent, I broke the content of my website down into different sections using `<div> and `<span>` tags. Nested `<div>` tags also allowed me to style elements within other elements.

Positioning the pictures on my homepage was difficult. To position them, I gave them different class tags, that referred to different style elements in the header. While I was able to move pictures around, I was unable to successfully move captions along with them. Originally, I planned on displaying each picture’s source in a caption, but when I was unable to properly position each image’s caption, I had to resort to using the image title attribute to display where each image came from.

In the spirit of making coffee more accessible, I decided to use a list format for displaying navigation links as screen readers can more easily access them than navigation links arranged horizontally.

After creating my homepage’s content and structure, I began creating `<style>` elements in the header. By using `<style>` elements in the header, I was able to reference specific class attributes to style elements in certain ways. For example, each picture uses one of two alignment `<style>` elements and a size `<style>` element. I liked the look of the website we made in assignment seven, and I decided to use a similar container set-up as it separates individual sections nicely.

As I wrote in a previous paragraph, while I was able to use `<style>` elements, positioning was still an issue. My images often overlapped other content, which meant I had to use many `<br />` tags to give everything enough space. Although it worked, I feel like there are better ways to position elements.

I also was not always successful in using `<style>` elements to size pictures properly. For example, to get the right size I had to use width and height attributes in the first image on my homepage rather than a referenced `<style>` element.
Once I had my content positioned mostly correctly, I decided to add some color. I went for a coffee theme, as the website I made is meant to display instructions for one method of coffee brewing.

Now that I finished my homepage, I created and styled my about and contact pages. Compared to the home page, these pages were much more straight forward as they did not require too much complicated positioning work and I could re-use the `<style>` and `<div>` elements from my home page. In the about page, I embedded a YouTube video using the `<iframe>` element because I thought it would be nice to see a couple other coffee preparation methods. In the contact page, I used the `<form>` element to create a place where webpage visitors can type in and send feedback on my website.
