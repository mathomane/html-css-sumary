# html-css-sumary
What is HTML?

HTML is designed to structure and bridge the content between the human computer languages it is also a channel used to serve different types of content such as: videos, audios, words, images, forms and interactive experience.

FUNCTION OF HTML
It has 3 Web Core Languages:

HTML
* responsible for making up the content of the web.
* has straightforward structure without logic programming logic, loops or functions.
* it is simple to use, even if you misspelled elements, it would just guess what you were trying to say and run the page for you.
  
CSS
*	styling of the web
*	responsible for how the web looks for example: colours, fonts and sizes.
*	adding animations and interactions
  
JavaScript
  
*	Allows one to create and add interactives stuff.
*	It is behind the fancy and complex interface on the web.
*	It is a bit fragile, unlike HTML when you misspelled an element it does not even try to figure out what you were trying to say. It won’t run the page.
  
~TEXT FORMATNG & HTML SYNTAX

It is used to structure websites
It uses tags that are symbolized as greater than and less than to mark different elements. We have 2 types of tags e.g. open tag<> and close tag</> that can be differentiated by a forward slash for close tag.
Tags work together to define elements that are like packages containing contentz

HTML HEADLINES

Webpages contains various headlines, titles and subheadings which are normally divided into small chunks. Elements used for marking up headlines are in 6 different types such as: h1, h2, h3, h4, h5, and h6. 
*	Each headline has their own visual effect. Selecting the appropriate level is easy.
For example: <h1> Welcome to the Jungle</h1> h1 is for the entire article of the article or web.
*	H2 is the subtitle that is usually smaller and longer than the main title.
For example: <h2> Law of the jungle, survival of the fittest</h2> The choice of headline level is based on its meaning.

HTML Bold and Italics

* it has four related elements, 2 for bold and another 2 for italics.
Reasons for using italics in some scenarios is to make a string point and in some it is because the word emphasized is the title or the main topic.
*<i> to apply visual italics.
*<em> to emphasize
*they appear the same but have different meanings.

The same as italics, there are also 2 elements used to emphasize or make something BOLD in HTML.
*first element is <strong> used to show important words, seriousness, or and urgency. It adds meaning to the text.
*<b> generic and neutral. 
     does not carry any specific meaning.
     does not imply any alternative voice or words.

HTML Lists

HTML lists are divided into 3 categories: unordered list, ordered list, and definition list.
* Ordered list: they are normally used for recipes and following steps.
* For example: steps to follow when making banana bread.
* they are identified with an <ol>element as each step I marked with<li> element.
* Unordered list: they have no particular order
* For example: giving a list of ingredients to buy for making banana bread.
* they are identified with<ul>element,followed by each step marked with <li> element.

Definition list: they are not like <ul> or <ol>.
* normally used when creating list that rembles akey value pair in computer science.
* instead of just items, first term then corresponding description.
* <dt> stands for defining term.
* <dd> tag stands for description.
* each term is marked with <dd> tag or element then the entire lost is wrapped with a <dt> tag..
HTML Quotes
HTML has different types of quotes such as: Using quotes and cite block elements, Using block quotes, and Using inline quotes.

Using quotes and cite block:~<cite> and <block> serve semantic purpose.
* informs other computers.
* provide convenient way to apply custom styling.

Using block quotes in context: elements should be nested with each other in a way that makes sense.
* include any element within the block quote.
* one can even put list or headlines.
~ Using inline quotes: unlike block quotes, they appear within the texts.
* use ~<q> element in HTML question.
* Using ~<q> element makes browser autprovide appropriate quote mark.
* comparing block quote element with ~"<q>" element is a good example for understanding HTML.
* HTML elements like, "<strong>", "<b>", "<i>" and "<em>" are inline, they are meant to wrap around text phrases that are inline with each other content.
* their purpose is similar with the "<q>" element.

Using date elements a few time elements

To specify the accurate date and time in a language that a computer can understand.
* <time.datime=""><>

* # How to use comments in HTML

According to programmers, they enhance code readability by adding comments that explain its purpose. In HTML, comments are inserted by typing `<!--` at the start and `-->` at the end. These comments are disregarded by the browser. Code editors such as Notepad++ can display commented code or remarks in a grayed-out fashion, which proves to be quite handy. This feature helps us quickly identify when code is commented out and prevents any confusion when it does not function as expected.

For example, this is how a comment looks like in HTML:

```html
<!-- This is a comment -->
<p>This is a paragraph</p>

