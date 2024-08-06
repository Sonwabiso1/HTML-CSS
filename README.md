# 🌐 HTML & CSS INTRODUCTION

## 👩‍💻 Introduction to HTML

**What is HTML?**

HTML, short for HyperText Markup Language, is responsible for marking up the content of a website. It informs the user's computer about various elements on the page. Moreover, HTML grants access to a wide range of built-in browser functionalities that can be utilized by incorporating specific HTML code.

The Web consists of three programming languages: HTML, CSS, and JavaScript.

CSS, short for Cascading Style Sheets, is like the stylist of a web page. It is responsible for how everything looks — the colors, fonts, and sizes. It is also capable of adding cool animations and interactions to spice things up.

JavaScript is a programming language that allows you to create really cool and interactive stuff. When you have a fancy and complex interface on a website, chances are JavaScript is behind the scenes making it work smoothly for the users.

## 🧾 HTML Text Formatting

HTML is a language used to structure web pages. It uses tags, which are enclosed in less-than and greater-than symbols, to mark different elements. Tags come in two types: opening tags and closing tags.

An entire HTML document is essentially a bunch of HTML elements nested inside each other, creating a tree structure known as the DOM tree (Document Object Model). This structure becomes important when working with CSS or JavaScript.

Let's discuss headlines.  
The HTML elements used for marking up headlines come in six different types: h1, h2, h3, h4, h5, and h6. When viewed in a browser, each headline has a distinct visual effect. These elements also convey a sense of hierarchy in how the browser interprets and communicates about the page. The h1 element is the largest and most prominent, while h6 is the smallest and least attention-grabbing.

**HTML Bold and Italics**

There are four HTML elements related to this, two for bold and two for italic. So, why do we have two of each?  
For Italics, we use `<em>` when we want to emphasize a word and `<i>` when we want to make a distinction, e.g., when we want to name a TV show.

For Bold, the first one is the `<strong>` element, which is used to show importance, seriousness, or urgency. It is like saying, "Hey, this needs to stand out!" This element adds meaning to the text. On the other hand, the `<b>` element is more generic and neutral. It does not carry any specific meaning.

Visually, they may look the same, but they serve different purposes by communicating semantic and human meaning.

**HTML Lists**

In HTML, there are three types of lists: unordered lists, ordered lists, and definition lists.

Unordered lists are the most commonly used type. To define the entire list and specify its type, we wrap all the items in a `<ul>` element, which stands for unordered list. Then we use `<li>` elements to list individual items.

The next type of list is the ordered list, which is similar to the unordered list but with a slight difference. Instead of using `<ul>` to wrap the list items, we use `<ol>`. The term "ol" stands for ordered list, indicating that there is a specific order to the items on the list.

We can format unordered and ordered lists to be listed by bullets, circles, decimals, letters, etc.

In HTML, there is another type of list called the "definition list" or "description list." Unlike unordered or ordered lists with their list items, the definition list is used when we want to create a list that resembles a key-value pair in computer science. Instead of just items, we have terms and their corresponding descriptions.

To create a definition list, we use specific elements. The term or key is enclosed in a `<dt>` tag, which stands for definition term. The description or value is enclosed in a `<dd>` tag, which stands for definition description. You can have multiple descriptions for each term by using multiple `<dd>` tags. The entire list is wrapped in a `<dl>` tag, representing the definition list.

**HTML Quotes**

When we want to distinguish a quote from surrounding text in HTML we wrap it in the `<blockquote>` element and to attribute the quote we use the `<cite>` element. These two elements serve a semantic purpose, telling the computer what they represent.

For quotes that are not block quotes but appear within the text, we use the `<q>` element. The browser will automatically provide the appropriate quote marks for us.

Comparing the `<blockquote>` element to the `<q>` element is a good example of understanding HTML. Some HTML elements, like `<strong>`, `<b>`, `<i>`, and `<em>`, are called "inline" because they are meant to wrap around phrases of text that are inline with other content, similar to the `<q>` element. Block-level elements, like block quotes, paragraphs, and unordered lists, create separate blocks on the page.

HTML elements can have attributes that provide additional information. For example, the `datetime` attribute allows us to specify the date or time in a format that computers can understand: `<time datetime="2025-05-08">May 8, 2025</time>`.

**HTML Date and Time Inputs**

This element is used to mark anything that specifies a time of day, a date, or a duration. To format a specific moment or range in time in a way that computers can understand, we use the `<time>` element.

Use this link to learn more about Date and Time Inputs: [The (Date) Time element reference mdn web docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time)

**HTML Code, pre and br**

Sometimes you might want to showcase code on a webpage. For this, use the `<code>` element to highlight and format code snippets.

The `<br>` element adds a line break, and the `<pre>` element maintains the spaces and line breaks as written within the tags.

**HTML Superscripts, Subscripts, and Small text**

Subscripts, superscripts, and small text can be used where you need to mark up certain bits of content as having a different meaning than the rest. Subscripts are characters set below the normal baseline for text, like in the chemical formula H₂O. Superscripts are characters set above the normal baseline of text.

We use `<sup>` for superscripts, `<sub>` for subscripts, and `<small>` to achieve small text in a webpage.

## 📚 HTML Capabilities

**Troubleshooting and Debugging HTML Code**

In popular desktop browsers like Firefox, there are developer tools that reveal the code and performance details of a website. Access these tools by right-clicking on the page and selecting "Inspect Element" or through the browser's menu.

**HTML Attributes**

We have explored the `datetime` attribute for the `<time>` element. Some attributes are specific to particular elements, while others, like `class` and `id`, are more universal.

The `class` attribute allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class.

The `id` attribute is similar but unique to the entire HTML page. IDs are useful for CSS targeting and JavaScript.

**ARIA Roles**

ARIA Roles are additional attributes that add meaning to HTML elements, helping browsers and assistive technologies understand their purpose. Proper HTML elements should convey the right message, but ARIA Roles are useful for complex interfaces and ensuring accessibility.

Developer tools in browsers like Firefox and Chrome have an Accessibility Inspector. The accessibility tree complements the DOM tree, representing the structure of HTML and providing information for assistive devices.

**Formatting HTML**

HTML does not pay much attention to spaces, tabs, or line breaks, except in a few cases. Comments in HTML are inserted by typing `<!--` at the start and `-->` at the end, and they are ignored by the browser.

**Unusual Characters**

Special characters like `<`, `>`, and `&` can be used in content by using character entities, such as `&lt;`, `&gt;`, and `&amp;`. The [W3C](https://www.w3schools.com/html/html_symbols.asp) provides a reference chart for these entities.

## 🔗 HTML Navigation and Linking

**HTML Links**

To create a link, use the `<a>` element with an `href` attribute containing the URL. For example: `<a href="https://example.com">This is a link</a>`.

**HTML URL Pathways**

Absolute URLs include the full domain name, while relative URLs link to something within the same site. For example: `/images/logo.gif` is an absolute URL, while `../images/logo.gif` is a relative URL.

**Navigation**

To create a navigation menu, use a combination of `<nav>`, `<ul>`, and `<li>` elements, with links inside `<a>` elements. For example:
```html
<nav role="navigation" aria-label="main-menu">
  <ul class="navbar">
    <li><a href="/">Home</a></li>
    <li><a href="People">People</a></li>
    <li><a href="Prices">Prices</a></li>
    <li><a href="Contact">Contact</a></li>
  </ul>
</nav>
```
This menu can be styled with CSS and includes ARIA attributes for accessibility.

## 🖼 HTML Working with Graphics and Images

## 🎥 HTML Working with Media

## 🔍 HTML Content Identification

## 📚 HTML Working with Forms and Interactive Elements

## 📊 Organizing Tabular Information in HTML
