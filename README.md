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
</p>

To make things easier, we can use the `<q>` element in HTML, which stands for quote. By using this element, the browser will automatically provide the appropriate quote marks for us.
<p>
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
<p>
Sometimes you might want to showcase code on a webpage. Let's say you are writing an article on webpage creation or you want to explain some code syntax. Here is an example: we have a sentence with CSS code in the middle. We want to highlight that code and make it look like actual code. For this, use the code element. Put an opening `<code>` tag before the CSS snippet and a closing code tag afterward. </p>
Let's discuss the br and pre elements. Usually, when we write code, we can add as many spaces and line breaks as we want, and the browser will ignore them. <br>
The `<br>` element adds a line break and `<pre>` elements maintains the space between the tags.

**HTML Superscripts, Subscripts and Small text**
<p>
Subscripts, superscripts, and small text can be used where you need to mark up certain bits of content as having a different meaning than the rest. Subscripts are characters that are set below the normal baseline for text. Did you ever take a chemistry class and learn how to write the formula for water, H2O, where the two are lower down than the H and the O? The two characters are typeset as a subscript. It is set lower down. Superscripts are characters that are set above the normal baseline of text. </p>

We use `<sup>`, `<sub>` elements to achieve this. And then we use `<small>` to achieve small text in webpage.

## 📚 HTML Capabilities

**Troubleshooting and Debugging HTML Code**

In popular desktop browsers like Firefox, there is a hidden treasure trove of information that reveals what is going on with a website's code and performance. 

To access the developer tools, we can either right-click on the demo and select "inspect element," or opt to go to "tools," then "web developer," and choose "inspector." This will open up the developer tools, which offer a wide range of tabs with different tools or controls as it is sometimes also referred to.<br>
Whenever you are unsure about what is happening, just turn to the developer tools in your browser to figure things out.

**HTML Attributes**

<p>
  We have already explored one attribute when discussing the time element. Keep in mind that certain attributes are specific to particular elements, such as the daytime attribute, which we only use with the time element. On the other hand, some attributes work with multiple elements but not all of them.<br>
When looking at global attributes in HTML that work universally, we will focus on four highly useful ones. The class attribute is the most commonly used. It allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class. 
</p>
Another popular attribute is the ID. It is similar to the class attribute, but we can only use unique names once on an entire HTML page. IDs can be used for CSS targeting, but are more specific, which can sometimes cause issues. As a result, CSS developers usually prefer using classes. <br>
However, IDs come in handy when we need to address specific elements in JavaScript or targeted links. <br>
HTML offers many attributes that enhance user interaction and provide hooks into browser power. These attributes, such as "content editable," allow interaction with the screen, keyboard, and assistive devices. <br>

**ARIA Roles**

<p>
ARIA Roles are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent. The goal is to rely on proper HTML elements to convey the right message about the content's meaning, without needing ARIA Roles.<br>
ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to ensure a website is fully accessible. ARIA came about when the web began replacing native applications, and it is particularly valuable for ensuring that everyone can use the full functionality of a complex interface in an app.
</p>
Developer tools in Browsers like firefox and Chrome have an Accesibility Inspector. The accessibility tree is like a companion to the DOM tree, which the browser creates from the website's content. While the DOM tree represents the structure of the HTML, the accessibility tree is crucial for assistive devices like screen readers. It allows them to provide a better experience to users. 

**Formatting HTML**

Remember how we said that HTML does not pay much attention to spaces, tabs, or line breaks? Well, there are a couple of exceptions. <br>
In HTML, comments are inserted by typing `<!--` at the start and `-->` at the end. These comments are disregarded by the browser.

**Unusual Characters**

The symbols <, >, and & are important characters in HTML, but what happens when we want to actually use them in our content?<br>
If we write these symbols with spaces around them, they will appear as regular content. However, if we start writing something that resembles an HTML element, it magically disappears. The browser assumes that it is part of HTML code and does not display it. Now, if you are using a content management system like WordPress or a tool like markdown, chances are it will handle these characters for you without any issues but there may be times when you need to take care of it yourself.<br>
We can use the code `&nbsp;` to insert a non-breaking space between the two names, ensuring they stay on the same line. <br>
The [W3C](https://www.w3schools.com/html/html_symbols.asp) has a handy reference chart for all these character entities that you can use. 

## 🔗 HTML Navigation and Linking

**HTML Links**

When we want to create a link, we use the A element, which stands for anchor. To do this, we need to add an href attribute with a URL enclosed in quotes. This URL is where the link will take us. The term href stands for Hypertext Reference, a nerdy phrase from the past. Between the opening and closing A tags, we can place text or images, or both, to make them clickable. For example, we can turn the phrase "this is a link" into an actual link that takes us to example.com when clicked.

**HTML Url Pathways**

When it comes to forming links, absolute URLs are just one option. When linking to something within the same site and domain as the page containing the link, a relative URL can be used instead.
<p>
  Creating a relative URL is not only useful for the A element (linking), but it is also a skill used to reference image files, video files, CSS, JavaScript files, or any other where a file’s path is specified. <br>
To create a relative URL, omit the domain name but include the initial slash at the beginning. This tells the browser to start from the root level of the file structure, which is the outermost top level. Alternatively, we can write the path to be relative to the file where the link is written.
</p>
<p>
  Here is an example to help understand how URLs work. Imagine there is a file called styles.css in a directory named CSS. Let's say we want to include a link in our CSS file that points to the logo.gif file, which is located in the images folder. We have two options to write the URL: 

/images/logo.gif 
../images/logo.gif
The first version, /images/logo.gif, creates a URL that is relative to the root level. It means the browser will start looking for the file from the root of the website. On the other hand, the second version, ../images/logo.gif, creates a URL that is relative to the location of the file where the URL is written. The ".." followed by a slash means going up one level in the directory structure.
</p>

**Navigation**

Let's explore common ways to make menus or navigation bars. Imagine we want to make a main menu bar for our website. We have four links: home, people, prices, and contact. <br>
```
  <nav role="navigation" aria-lable="main-menu">
    <ul class="navbar">
      <li><a href="/">Home</a></li>
      <li><a href="People">People</a></li>
      <li><a href="Prices">Prices</a></li>
      <li><a href="Contact">Contact</a></li>
    </ul>
  </nav>
```
<p>
  Each link is wrapped in an element with the correct URL, and then enclosed in an "li" element to create a list of links. To maintain the order, wrap the whole list in a "ul" element, which represents an unordered list. Finally, encompass the entire menu in a "nav" element to indicate that it is the site's navigation.
To give the menu a visual appearance, apply CSS styling. Without the styling, it appears as a plain list, however, we also want screen readers and assistive devices to understand that it is the main menu. Now add some attributes to convey its purpose. Assign the role "navigation" to the "nav" element, which signifies that it represents the main navigation of the page. Additionally, include an "aria label" for the main menu, providing a descriptive label that can be read aloud by a screen reader. Remember, this is not the only way to correctly mark up a main navigation menu. 
</p>


## 🖼 HTML Working with Graphics and Images

## 🎥 HTML Working with Media

## 🔍 HTML Content Identification

## 📚 HTML Working with Forms and Interactive Elements

## 📊 Organizing Tabular Information in HTML
