# Assignment 6

## Created by Eli Watts for MART 341, Sect. 50

### Questions:

*Describe any forms you've come across while browsing the web. What purposes do the serve?*

During my time on the web, I have come across a lot of different forms. As a distance only student, two forms that I encounter often are the file input box and the text area form. Both these forms allow me to turn in assignments to the Moodle website. The file input box allows me to upload files, like word documents or pdfs, and the text area form allows me to either comment on my submitted assignment or turn in short response questions.

*List examples of a text, selection, and button input, and where they might be used.*

A text input creates a single line field where users can type text. This form can be used as a place for return visitors to type in their username when signing into a website. Selection inputs give webpage visitors a few options to chose between when answering a question. Checkbox buttons, a kind of selection input, allow users to chose one or multiple options. This is helpful in situations where more than one answer is applicable, for example when asking customers which company services they interacted with as they may have interacted with multiple. Finally, button inputs create a clickable button that webpage visitors click to send a form to a server. A subscribe button, for example, would send the webpage visitor’s email address to a server which would then place them in a mailing list directory so that they could receive email updates from that company.

*Free Response: Summarize your work cycle for this assignment.*

I began this assignment by creating my webpage’s basic structure. This included the four basic elements – doctype, header, title, and body – and their respective meta information.

After creating my webpage’s basic structure, I began adding more content and structure to the body element. I chose to use a table to layout my chosen store’s opening hours as the table structure makes it very easy to understand when the store is open or closed. After creating the table content and structure, it was necessary to create a` <style>` element in the header to make the table content easier to read as the table’s default setting scrunched the cell’s up too close together. Increasing the padding and adding borders helped keep all the content separated and easy to understand.

To keep some separation between different kinds of contact information, for example, address information and opening hours, I used horizontal rules and header elements. A fieldset also helps give the review section a more unified look.

When creating my form, I decided to use the `get` method as the information visitors supply is short, does not include sensitive data, and does not require users to upload any files.

The first time I created my form, I used the `<form>` element for each individual input element. When I checked my webpage in a browser, it appeared to work out fine, however, when I compared my work with the example on page 171 of Jon Duckett’s *HTML and CSS* textbook, I noticed only one `<form>` function was used for all input elements.

Considering the above paragraph, a question I currently have about forms is: was my original method, a new `<form>` element for every input function, legitimate or, is it better to call a single `<form>` function for all input elements. I am assuming the latter is better as it removes redundancy and allows a single button to submit all input elements to a server.
