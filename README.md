# HTML & CSS INTRODUCTION

## Introduction to HTML

**What is HTML?**

HTML, short for HyperText Markup Language, is responsible for marking up the content of a website. It informs the user's computer about various elements on the page. Moreover, HTML grants access to a wide range of built-in browser functionalities that can be utilized by incorporating specific HTML code.

The Web consists of three programming languages: HTML, CSS, and JavaScript.

CSS, short for Cascading Style Sheets, is like the stylist of a web page. It is responsible for how everything looks — the colors, fonts, and sizes. It is also capable of adding cool animations and interactions to spice things up.

JavaScript is a programming language that allows you to create really cool and interactive stuff. When you have a fancy and complex interface on a website, chances are JavaScript is behind the scenes making it work smoothly for the users.

## HTML Text Formatting

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


## HTML Capabilities

## HTML Navigation and Linking

## HTML Working with Graphics and Images

## HTML Working with Media

## HTML Content Identification

## HTML Working with Forms and Interactive Elements

## Organizing Tabular Information in HTML
