# 🌐 HTML & CSS INTRODUCTION

## 👩‍💻 Introduction to HTML

**What is HTML?**

HTML, short for HyperText Markup Language, is responsible for marking up the content of a website. It informs the user's computer about various elements on the page. Moreover, HTML grants access to a wide range of built-in browser functionalities that can be utilized by incorporating specific HTML code.

The Web consists of three programming languages: HTML, CSS, and JavaScript.

CSS, short for Cascading Style Sheets, is like the stylist of a web page. It is responsible for how everything looks — the colors, fonts, and sizes. It is also capable of adding cool animations and interactions to spice things up.

JavaScript is a programming language that allows you to create really cool and interactive stuff. When you have a fancy and complex interface on a website, chances are JavaScript is behind the scenes making it work smoothly for the users.

## 🧾 HTML Text Formatting

HTML is a language used to structure web pages. It uses tags, which are enclosed in less-than and greater-than symbols, to mark different elements. Tags come in two types: opening tags and closing tags.

In fact, an entire HTML document is basically a bunch of HTML elements nested inside each other. If you are familiar with computer science, you might recognize that this nesting creates a tree structure, like a family tree with parents, children, and siblings. Technically speaking, it is called a DOM tree, which stands for Document Object Model. The DOM tree becomes important when you are working with CSS or JavaScript.

Let's discuss headlines.  
The HTML elements used for marking up headlines come in six different types: h1, h2, h3, h4, h5, and h6. When viewed in a browser, each headline has a distinct visual effect. These elements also convey a sense of hierarchy in how the browser interprets and communicates about the page. The h1 element is the largest and most prominent, while h6 is the smallest and least attention-grabbing.

**HTML Bold and Italics**

There are four HTML elements related to this, two for bold and two for italic. So, why do we have two of each?  
For Italics, we use `<em>` when we want to emphasize a word and `<i>` when we want to make a distinction, e.g., when we want to name a TV show.

For Bold, the first one is the `<strong>` element, which is used to show importance, seriousness, or urgency. It is like saying, "Hey, this needs to stand out!" This element adds meaning to the text. On the other hand, the `<b>` element is more generic and neutral. It does not carry any specific meaning.

It may seem like they look exactly the same visually, but they serve different purposes. We are not just playing with typography here; we are communicating semantic and human meaning.

**HTML Lists**

In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists.

Unordered lists are the most commonly used type. To define the entire list and specify its type, we wrap all the items in a `<ul>` element, which stands for unordered list. Then we use `<li>` elements to list individual items.

The next type of list is the ordered list, which is similar to the unordered list but with a slight difference. Instead of using `<ul>` to wrap the list items, we use `<ol>`. The term "ol" stands for ordered list, indicating that there is a specific order to the items on the list.

We can format unordered and ordered lists to be listed by bullets, circles, decimals, letters, etc.

In HTML, there is another type of list called the "definition list" or "description list." Unlike unordered or ordered lists with their list items, the definition list is used when we want to create a list that resembles a key-value pair in computer science. Instead of just items, we have terms and their corresponding descriptions.

To create a definition list, we use specific elements. The term or key is enclosed in a `<dt>` tag, which stands for definition term. The description or value is enclosed in a `<dd>` tag, which stands for definition description. You can have multiple descriptions for each term by using multiple `<dd>` tags. The entire list is wrapped in a `<dl>` tag, representing the definition list.

**HTML Quotes**

When we want to distinguish a qoute from surrounding text in HTML we wrap in the `<blockquote>` element and to attribute the quote we use the `<cite>` element.<br>
These two elements serve a semantic purpose. They tell the computer, "Hey, this is what this is".<br>
With CSS we can make these elements look however we want.

<p>
  Lets talk about qoutes that are not blockqoutes but appear within the text.  These quotes are simply typed in, but we believe they should be curly quotes, not straight ones. However, different languages and regions have their own conventions for displaying quote marks.<br>
  
To make things easier, we can use the `<q>` element in HTML, which stands for quote. By using this element, the browser will automatically provide the appropriate quote marks for us.<br>
Comparing the block quote element to the `<q>` element is a good example of understanding HTML. Some HTML elements, like `<qstrong>`, `<b>`, `<I>`, and `<em>`, are called "inline" because they are meant to wrap around phrases of text that are inline with other content. They serve a similar purpose as the `<q>` element. `<br>`
There are certain elements in HTML known as block-level elements, like block quotes, paragraphs, and unordered lists. These elements essentially create separate blocks on the page. You can think of them as standalone entities that can be followed by another block. <br>
HTML elements can have attributes provide additional information to HTML elements.<br>
An example would be the datetime attribute which allows us to specify the date or time in a format that computers can understand. We write it like this: `<time datetime="2025-05-08">May 8, 2025</time>`.
</p>

**HTML Date and Time Inputs**


This element is used to mark anything that specifies a time of day, a date, or a duration.<br>
To format a specific moment or range in time in a way that computers can understand, we use the `<time>` element.
Use this link below to learn more about Date and Time Inputs. <br>
[The (Date) Time element reference mdn web docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time)

**HTML Code, pre and br**

Sometimes you might want to showcase code on a webpage. Let's say you are writing an article on webpage creation or you want to explain some code syntax. Here is an example: we have a sentence with CSS code in the middle. We want to highlight that code and make it look like actual code. For this, use the code element. Put an opening `<code>` tag before the CSS snippet and a closing code tag afterward. <br>
Let's discuss the br and pre elements. Usually, when we write code, we can add as many spaces and line breaks as we want, and the browser will ignore them. <br>
The `<br>` element adds a line break and `<pre>` elements maintains the space between the tags.

**HTML Superscripts, Subscripts and Small text**

Subscripts, superscripts, and small text can be used where you need to mark up certain bits of content as having a different meaning than the rest. Subscripts are characters that are set below the normal baseline for text. Did you ever take a chemistry class and learn how to write the formula for water, H2O, where the two are lower down than the H and the O? The two characters are typeset as a subscript. It is set lower down. Superscripts are characters that are set above the normal baseline of text. <br>

We use `<sup>`, `<sub>` elements to achieve this. And then we use `<small>` to achieve small text in webpage.

## 📚 HTML Capabilities

**Troubleshooting and Debugging HTML Code**

In popular desktop browsers like Firefox, there is a hidden treasure trove of information that reveals what is going on with a website's code and performance. 

To access the developer tools, we can either right-click on the demo and select "inspect element," or opt to go to "tools," then "web developer," and choose "inspector." This will open up the developer tools, which offer a wide range of tabs with different tools or controls as it is sometimes also referred to.<br>
Whenever you are unsure about what is happening, just turn to the developer tools in your browser to figure things out.

**HTML Attributes**

We have already explored one attribute when discussing the time element. Keep in mind that certain attributes are specific to particular elements, such as the daytime attribute, which we only use with the time element. On the other hand, some attributes work with multiple elements but not all of them.<br>
When looking at global attributes in HTML that work universally, we will focus on four highly useful ones. The class attribute is the most commonly used. It allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class. <br>
Another popular attribute is the ID. It is similar to the class attribute, but we can only use unique names once on an entire HTML page. IDs can be used for CSS targeting, but are more specific, which can sometimes cause issues. As a result, CSS developers usually prefer using classes. <br>
However, IDs come in handy when we need to address specific elements in JavaScript or targeted links. <br>
HTML offers many attributes that enhance user interaction and provide hooks into browser power. These attributes, such as "content editable," allow interaction with the screen, keyboard, and assistive devices. <br>

**ARIA Roles**
ARIA Roles are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent. The goal is to rely on proper HTML elements to convey the right message about the content's meaning, without needing ARIA Roles.<br>
ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to ensure a website is fully accessible. ARIA came about when the web began replacing native applications, and it is particularly valuable for ensuring that everyone can use the full functionality of a complex interface in an app.


## 🔗 HTML Navigation and Linking

## 🖼 HTML Working with Graphics and Images

## 🎥 HTML Working with Media

## 🔍 HTML Content Identification

## 📚 HTML Working with Forms and Interactive Elements

## 📊 Organizing Tabular Information in HTML
