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
  
# TEXT FORMATNG & HTML SYNTAX

It is used to structure websites
It uses tags that are symbolized as greater than and less than to mark different elements. We have 2 types of tags e.g. open tag `<>` and close tag `</>` that can be differentiated by a forward slash for close tag.
Tags work together to define elements that are like packages containing contentz

HTML HEADLINES

Webpages contains various headlines, titles and subheadings which are normally divided into small chunks. Elements used for marking up headlines are in 6 different types such as: `h1`, `h2`, `h3`, `h4`, `h5`, and `h6`. 

For example:

`<h1>` Welcome to the Jungle `</h1>`, h1 is for the entire article of the article or web.
*	H2 is the subtitle that is usually smaller and longer than the main title.
  
For example: `<h2>` Law of the jungle, survival of the fittest `</h2>`, The choice of headline level is based on its meaning.

HTML Bold and Italics

* it has four related elements, 2 for bold and another 2 for italics.
Reasons for using italics in some scenarios is to make a string point and in some it is because the word emphasized is the title or the main topic.


* `<i>` to apply visual italics.
* `<em>` to emphasize

*they appear the same but have different meanings.

The same as italics, there are also 2 elements used to emphasize or make something BOLD in HTML.
*first element is <strong> used to show important words, seriousness, or and urgency. It adds meaning to the text.
*`<b>` generic and neutral. 
     does not carry any specific meaning.
     does not imply any alternative voice or words.

HTML Lists

HTML lists are divided into 3 categories: unordered list, ordered list, and definition list.
* Ordered list: they are normally used for recipes and following steps.
* For example: steps to follow when making banana bread.
* they are identified with an `<ol>` element as each step I marked with `<li>` element.
* Unordered list: they have no particular order
* For example: giving a list of ingredients to buy for making banana bread.
* they are identified with `<ul>` element,followed by each step marked with `<li>` element.

Definition list: they are not like `<ul>` or `<ol>`.
* normally used when creating list that rembles akey value pair in computer science.
* instead of just items, first term then corresponding description.
* `<dt>` stands for defining term.
* `<dd>` tag stands for description.
* each term is marked with `<dd>` tag or element then the entire lost is wrapped with a `<dt>` tag..
HTML Quotes

HTML has different types of quotes such as: Using quotes and cite block elements, Using block quotes, and Using inline quotes.

Using quotes and cite block: `<cite>` and `<block>` serve semantic purpose.
* informs other computers.
* provide convenient way to apply custom styling.

Using block quotes in context: elements should be nested with each other in a way that makes sense.
* include any element within the block quote.
* one can even put list or headlines.
  
#Using inline quotes: unlike block quotes, they appear within the texts.
* use `<q>` element in HTML question.
* Using `<q>` element makes browser autprovide appropriate quote mark.
* comparing block quote element with `<q>` element is a good example for understanding HTML.
* HTML elements like, `<strong>`, `<b>`, `<i>` and `<em>` are inline, they are meant to wrap around text phrases that are inline with each other content.
* their purpose is similar with the `<q>` element.

Using date elements a few time elements

To specify the accurate date and time in a language that a computer can understand.
* `<time.datime="2024-01-22"> January1,2022 </time>`.
* it starts with a year 4 digits followed by the month 2 digits and lastly the day also 2 digits

* on time elements,time is not necessary spelled ou on the website
* it uses time phases like 2 hours ago or 11 minutes ago
* but behind the scenes we still need to use a language that the computer understands.
* the time macine referes 24 hours format which inclued seconds and fractions
For example: 15:45, which means 3:45 PM it uses five hour behind the Greenwhich Mean Time

# Capabilities

Troubleshooting and Debuging

Troubleshooting and debuging in HTML comes with accessing developer tools. to do so you will have to right click on the page that you're in, then select inspect.
inspect has three sectons which are:

1. HTML on the left
2. CSS on the middle
3. More options on the right

HTML Attributes

HTML attributes add power to any element. There are four highly useful global attributes in HTMLthat work universaly. Class attributes is the most commonly used. It allows any elements which can be styled with the use of CSS for all lements that share the class.

Class and ID attributes

Known as on of the porpular attributes, similar to the class attribute. 
* they can be used for targeting CSS which can sometimes cause issues.
* they come in handy when addresing specific elements in Javascript or targeted links.
* its uniqueness ensures that there will always be one element with ID.
* CLASS and ID attributes nprovide a way to name HTML elements and reference them in onother parts of code stack.

ARIA ROLES

ARIA roles are exxtra attributs added ito HTML to make more meaningful and also assists the browser to understand what they representing.

Web or online accessibility image

ARIA Roles come in handy in providing essential information to assistive technologies like: screen readers, braille display, and magnifiers to ensure the website is fully accessible.
It came about when web began replacing native applications. 

Using the browser accessibility tree

* it is like a companion DOM tree that the browsr create from the website content.
* DOM tree represents the  structure of HTML
* accessibility tree is known or desinged sor assistive devices like screen readers.
* povides better experience to the user.
* it can however results or lead to poor experince e.g. letter "hello" be read out loud individually. To improve all this one can use ARIA
* aad aria label to HTML to specify the text that the screen reader will read.
* set ARIA label to "hello wold"
* hide individual letters by enclosing them with `<div>` element
* set ARIA hiddeen attribute to true.

~ Formatting HTML ~

 Formating HTML includes:
 
 1. Working with extra spaces
 2. Working with comments
 3. Working with uper and lowercases
 4. Working with long and short elements
 5. Working with self- closing elements

It has always been said in the beginning that HTML does not pay much attentions to spaces, tabs or line braeks, however now there are couple of exceptions.

 ~ How to use comments in HTML ~

According to programmers, they enhance code readability by adding comments that explain its purpose. In HTML, comments are inserted by typing `<!--` at the start and `-->` at the end. These comments are disregarded by the browser. Code editors such as Notepad++ can display commented code or remarks in a grayed-out fashion, which proves to be quite handy. This feature helps us quickly identify when code is commented out and prevents any confusion when it does not function as expected.

For example, this is how a comment looks like in HTML:

```html``
`<!-- This is a comment -->`

The HTML Upper- and Lowercase Debate:

In the history of HTML, there was a shift from capitalizing all elements to using lowercase letters as the norm. Despite the evolution, browser support remains unaffected. Both old and new websites coexist with different letter case choices, showcasing that browsers handle it seamlessly. Although personal preferences vary, the contemporary practice leans towards using lowercase for better readability.

The Evolution of HTML Element Length:

HTML elements vary in length, with some like `<p>` or `<i>` being short, and others like ``<article>`` or ``<video>`` being longer. This difference originated from the early days of HTML when file size optimization was crucial due to limited computer resources. With advancements in technology and increased memory, the focus shifted to prioritizing code readability. Newer HTML elements now use complete words for better human understanding. Element length can serve as a clue to its historical timeline, indicating changes over time.

The Evolution of HTML Tag Formatting:

In HTML, most elements have both opening and closing tags, while some older ones lacked closing tags initially. For instance, the `<img>` element in the 90s didn't require a closing tag. However, the practice evolved, and adding a slash at the end became standard to self-close elements. Although this convention persisted for years, around 2010, its importance waned as browsers adapted to various formatting styles. Ultimately, the choice of including the closing slash is left to the developer's discretion.

# HTML Navigation and Linking

Working with Links:
  * Use the A element (anchor) to create links.
  * Add an href attribute with a URL enclosed in quotes.
  * "href" stands for Hypertext Reference.
* Linking Text and Images:
  * Place text or images between the opening and closing A tags to make them clickable.
* Link Placement:
  * A element is inline and can be used within paragraphs or other text.
* Versatility of URLs:
  * URLs can be simple (e.g., HTTPS://example.com) or more complex.
  * Absolute URLs point to precise locations on the web.
  * Include HTTP or HTTPS, standing for Hypertext Transport Protocol, in absolute URLs.
* HTTPS for Security:
  * HTTPS indicates a secure connection.
  * Experts recommend using HTTPS for enhanced security.
  * Modern browsers automatically add HTTPS:// when typing a URL.

HTML URL Pathway

* Absolute vs. Relative URLs:
  * Absolute URLs point to specific web locations.
  * Relative URLs are used for links within the same site/domain.
* Context of Usage:
  * Example scenario: developing a website locally before deployment.
  * Avoiding issues with absolute URLs trying to access the live site during development.
* Importance of Relative URLs:
  * Allow links to adapt to different environments (e.g., local development, testing servers).
  * Useful for referencing various file types, not just for linking with the A element.
 
# HTML Workinh with Graphics and Images
Adding an image to webpage, we use image element that is written as `<img>`.
Addding an image includes four attributes 
1. source attribute (src)-> it tells the browser which image file to upload.
2. alt attribute (alt)-> provides txt description of image.
3. width and height attribute-> determine the size.

in HTML it does not matter wether the height or the width is specified first, the order of the attribute can be whatever you prefer.

IMAGE FORMATS

There are four main image fomarts used on the web which are:
1. GIF
   * good for compressing illustrations that have larger areas of the same color.
   * if falls short when it comes to photographs.
   * it only supports 256 colors with the images looking pixaleted

2. SVG
   * perfect fo logos, icons and other type of illustrators.
   * vector file that contains instructions to drawing.
   * can be scaled to any size without losing quality.
   * programming laguage for graphics
   * can be exported

3. JPG
   * popular choice for compressing photographs
   * half compessed JPG can slow down the speed of loading in a web
     
4. PNG
  * works well when needing tranparency in photographs
  * outperforms GIF and JPG

RESPONSIVE IMAGES
With HTML we can deliver different image files to screens of different size. Wecan also create multiple image files and include them as option in HTML code.

# WORKING WITH MEDIA

* audio element is idifferernt from the image element, it has bothe openimg and closing tag
* has more power and flexibility
* there is an option to create your own control using JS and HTML media element API
* loops can also be used as media element, it will make the audio repeat from the start till the finish
* autoplay can aotomatically play audio as soon as the page loads
* MP3 are supported in modern browsers

WORKING WITH VIDEO

* Like audio element, video element also has opening and closing tag
* to display video, we use the source attribute to specify video file
* there are different codes that can be used to encide video files
* internet videos use a mechanism to cmpress all the adte into a small package.

WOKING WITH SUBTITLES AND CAPTIONS
  Working with video element and track element
* track element adds functionality to video players
* allows viewers to togglecaption on and off
* to display caption, insert track element within the video element
* use the source attribute to specify the file

EMBEDDING MEDIA VIA IFRAMES

Embedding refers to taking content from one site and placing it within the middle of another site's page.

WORKING WITH IFRAMES ELEMENT

Using content managemnt system (CMS) that has been set up by oter elements, you may not be able to copy and paste random embed codes from other websites.
CMS has a spcific way to allow URLS OR SHOTCODE FROM TRUSTED SOURCES
Security aspects elated to iframe elements should be considered when building website.

# HTML CONTENT IDENTIFICATION

HTML Lanuage Support

HTML has tool to indentify the language of your website. Search engines will understand which language
the website is in and also the spellcheckers will provide appropriate dictionaries.

The lang Attribute
Lang attribute is udes to specify the language of a website. If the whole website is in one language, it is quite simple.
To specify this you can use "en-US" in the land attribute which means U.S English. There is also "en-GB" for English in Great Britain.
It is also important to specify on the cintent direction.
Most languages flow from left to right horizontally but some flow from right to left.

 Introduction to Generic Elements:
  * HTML elements like div and span are versatile tools for various purposes.
* Purpose of Div and Span:
  * Grouping elements or highlighting phrases.
  * Targeting specific parts of the DOM with CSS or JavaScript.
* Common Usage:
  * Developers frequently encounter div and span when writing HTML.
 
* Pre-HTML5 Era:
  * Before HTML5, divs were extensively used for structuring web pages.
    
* Overuse of Divs and Spans:
  * Divs and spans are still commonly used for various purposes in HTML.
    
* Emphasis on Semantic HTML:
  * Importance of using semantic HTML elements over generic divs and spans.
* Proper Usage:
  * Avoid excessive use of divs and spans for every element.
  * Opt for appropriate HTML elements based on their semantic meaning.
  
* Functionality of Div and Span:
  * Div is a block-level element, while span is an inline element.
  * They serve as generic containers and require CSS or JavaScript for functionality.

* Grouping Paragraphs with Div:
  * Example scenario: adding a background color to paragraphs within an article.
  * Introduce a div with the class "boxes" to group paragraphs and target them with CSS.

* Specific Phrase Targeting with Span:
  * Example scenario: targeting a specific phrase within the text for language attribute adjustment.
  * Use the inline element span to mark the desired phrase for targeted adjustments.

* Utilization of Global Attributes:
  * Both div and span elements can utilize various global attributes like class, id, lang, and aria roles.
* Div and Span Usage:
  * They serve as last resort options when there isn't a suitable semantic element.
  * Exercise caution and use them wisely when no other alternative exists.

# HTML INTERGRATION

Importance of HTML in Web Development:
  * HTML plays a crucial role in marking up content on websites and web applications.
* Functionality of HTML Files:
  * HTML files are vital components of the web ecosystem.
* Website Access:
  * Visiting a website involves opening a web browser or web view and entering a URL.
  * The URL triggers the web server to respond by sending back the specific HTML file located at that address.

Standard HTML Page

  * In the past, everything needed for webpage display was in a single HTML file.
  * Presently, text is often stored in databases, and various files are combined in real-time for customization.
* File Distribution:
  * Visual styling resides in CSS files, JavaScript in separate files, and media content in respective files.
  * Multiple static files, including images, video, audio, and ads, contribute to webpage composition.
* User Interaction:
  * Users initiate webpage access by visiting a URL, prompting a request for an HTML file.
  * The server responds by returning a single HTML file, which the browser reads and executes.

Document Head
That is where you put all important information that the browser nees to know about the page or entire website.
Charset is not for users to see, but for the browser.
To convey this we use the meta element
Ensure that the meta elements are placed inside the head as they provide metadata for about the website or page.

HTML File Head Section

Webpage title is what appears on the browser tab when it is saved.
Also the name that appears under top sites when a new browser is opened

Meta Tag
Inform the browser that the layout has been adjusted to fit small screen, to making it a responsive website.
Without meta tag, the browser assumes the page follows an older layout

Content Structuring

1. Main
   * Tells the browser where the main content is located
2. Header
   * Mark the header and footer aeas on the page
   * It is where the files metadata lives and not display to users
   * Usually found at the top of most webpages and may also include logo, name and navigation bar
3. Footer
   * Signifiers that ther are extra things to convey, regardless of it's position on the page
4. Article
   * Starts with the title, subtitle, authors name and ublication date.
   * Wraps aroundany type of content unit, whether it is a long written article
5. Section
   * Used to mark sections of content
   * Useful for dividing different topics zones on a website.
6. Aside
   * Content the is off to the side, like sidebar information or additional information.
   * Advertisements can also be marked as an aside.

# Working with Forms and Interactive Elements
Form Fundamentals

Web Form Fields Importance:
* Essential for logging, purchasing, searching, and content addition.
* Semantic form elements in HTML leverage browser's built-in power.
* Avoids wasting time and effort on re-creating existing functionalities.
* Ensures compatibility with all devices and input/output hardware.

# WHAT IS CSS?
CSS is a file that holds all the styles for a website. It also holds visual appeal to the website.
CSS hastwo parts such as:
1. The selector
2. The delaration block

Selector specifies HMTL partten and it matches. The styles within the declaraton block are applied to the corresponding HTML elements.
In CSS each style declaration consists of two parts:
1. Property
2. Value

**CSS SELECTORS**
The parttens CSS uses to taget and apply to specific elements within an HTML document. They allow you to define rules for how different elements should be displayed on a web page.
Common types of selectors:
1. Element selector
   Matches all element within the same tag name. For example:
   `p{color: red;}`
   This will set the text color of all paragraphs element to red.
2. Class selector
   Matches elements that have the same class attribute value. For example:
   `.red{color: blue;}`
   This rule applies a blue color class= "blue"
3. ID selector
   Matches the elements with the same ID attibute value. For example:
   `#main{font-weight:bold;}`
  This rule makes the elel=ment with id= "main" bold.

**Writing Your First Comment and Element**
Formating colors in css

Hex values have six digits
they consits of numbers from zero to nine and letters from A to F
the fisrt two letters represent red, next two epresent green, then the final two is blue.
the digits corresponds to numbers ranging from 0 to 255
color name and hex values are the mostly commonly used methods fo woking with colors in the web.

RGB Syntax
rgb colors are written out using base 10 numbers to specify Red,Green,Blue channels
the format can also be represented as an 8 dits hex number
the last number 0.8 in RGB valuen correspinds to Alpha
it relates to opacity and transparency of color

Understanding Images in CSS

1. GIF
   Has limited colors but could include transparency and animation
2. PNG
   Has more colorsand transparency but no animation, it is alos suitable for illustartions like logos or cartoons
3. JPEG
   Joint Photographic Experts Group, optimized for photographs, surppoted millions of colors but lacked transparency and animation

WebP Formats
can be used for any image type, it offers high compession for smaller sizes. Savind an image as GIF results in color loss and potentially larger file sizes. tinypng.com and Adobe can also ve used to reduce image sizes.

**Understanding Types in CSS**
Font Types

Usually there are two types of  fonts designers categorize
1. Serif
   have small lines at the end of the letters called serif.
   they were used for printed materials with long text blocks.
   serifs help connect the letters, making the text easier to read
2. Sans Serif
   they have a morden appearence
   they are mainly used on the web for extended text becaus they look cclean and are easy to read

Web Fonts
web fints are more complicated thsn print fonts. They depend on where the fonts come from. If your  looking for a differrent font, the option is Google Fonts.
Google provides wide selection of more than thousand fonts that can be added to any website. The fonts are sourced from the internet and loaded into web browser. This is to ensure that they dispaly on web page even if the user does not have them installed on their device.

**Understanding and Applying size in CSS**
Font measurement and sizes

Absolute vs Relative
* Points
* Pixels
* Dont change with screen size

Relative
* Percentage
* Rems- adujust bade on the page size
* Change with screen size

Font Size Conversion
* 1 rem= 16px
* 1.5 rem 16px= 24px
* 0.8 rem 16px= 13px

Understanding the Box Model in CSS
Explanation of different parts

The box model allows us to add elements and define space between elements
1. Content- it is where the images and the text appear
2. Padding- clears an area around the content and padding and it is transparent
3. Border- goes arround the content and padding
4. Margin- clears an area outside the boder and the margin is transparent












