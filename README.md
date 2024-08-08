# 🌐 HTML & CSS INTRODUCTION

# Table of Contents
- [👩‍💻 Introduction to HTML](#-introduction-to-html)
- [🧾 HTML Text Formatting](#-html-text-formatting)
- [📚 HTML Capabilities](#-html-capabilities)
- [🔗 HTML Navigation and Linking](#-html-navigation-and-linking)
- [🖼 HTML Working with Graphics and Images](#-html-working-with-graphics-and-images)
- [🎥 HTML Working with Media](#-html-working-with-media)
- [🔍 HTML Content Identification](#-html-content-identification)
- [🧠 HTML Integration](#-html-integration)
- [📚 HTML Working with Forms and Interactive Elements](#-html-working-with-forms-and-interactive-elements)
- [📊 Organizing Tabular Information in HTML](#-organizing-tabular-information-in-html)



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

**Images**

When we want to add an image to a webpage, we use the image element, which is simply written as IMG.<br>
Here is the cool part: there are four attributes that need to be included for every image. 

- First, we have the source attribute (SRC), which tells the browser which image file to load. 
- Then we have the alt attribute (ALT), which provides a text description of the image. 
- Lastly, we have the width and height attributes, which determine the size of the image. So, every image should have all four of these attributes.

Key things to note: An ALT attribute, serves as a replacement for the image when it cannot be seen. Make the ALT text interesting. Adding the dimensions of the image gives the browser a headstart in loading webpage content.

**Image Format**

The image file itself is a crucial aspect to consider when putting an image on a webpage. It needs to be in a file format that web browsers can understand, and there are various options available. <br>
There are four main file formats commonly used on the web these days, each with its own strengths and weaknesses when it comes to compressing images. <br>
- GIF: GIFs are great for compressing illustrations that have large areas of the same color, but it falls short when it comes to photographs. It only supports 256 colors, and images can end up looking pixelated, unless you want that retro vibe.
- SVG: SVGs are perfect for logos, icons, and other types of illustrations. Unlike GIF, SVG is a vector file that contains instructions for drawing rather than individual pixels. This means it can be scaled to any size without losing quality, and the file size remains small.
- JPG: JPGs are a popular choice for compressing photographs. Most digital cameras save images in JPG format, but when placed on the web, it is important to resize and compress them appropriately. Avoid using gigantic, half-compressed JPGs on your websites as they will slow the loading speed.
- PNG: PNG is a newer format that works well when you need transparency in a photograph. It sometimes outperforms both GIF and JPG in compressing certain types of images. When manually compressing files, try different options to find the smallest file size.

**Responsive Images**

Images have different resolutions, some higher than others. In your `<img>` element you can set a source set attribute to accomodate different media sreens. This can help make your webpage faster and increase accessability for devices with different pixel densities, storage and network connections.

**Responsive Width**

If we know the image will be much smaller than the whole page, we should give the browser more information to make a better choice. Use the sizes attribute in HTML to specify which image to use at different breakpoints. This way, the browser can download the right-sized image for your layout.

**Responsive Pictures**

When you want to display a photo on different screens with varying levels of detail, the `<picture>` element is a powerful tool. It allows you to show different parts of the image based on the screen size, optimizing the viewing experience. Here's how it works:

1. **Basic Setup**: Start with the `<img>` element, providing ALT text and the URL of the image. This ensures compatibility with older browsers like Internet Explorer 11.

2. **Wrap with `<picture>`**: Place the `<img>` element inside a `<picture>` element. The `<picture>` element acts as a container for different image sources.

3. **Define Sources**: Use multiple `<source>` elements within the `<picture>` element to specify alternative images for different screen sizes.
   - For smaller screens, use the `srcset` attribute in a `<source>` element to point to a cropped version of the photo, sized at 320 pixels wide. Set the `media` attribute to a condition like `max-width: 600px` to load this version when the viewport is smaller than 600 pixels.
   - For larger screens, use another `<source>` element with a media query like `min-width: 600px` to load a landscape version of the photo when the viewport is at least 600 pixels wide.

4. **Responsive Switching**: The browser will use the appropriate image based on the screen size and resolution, switching between the cropped and wide versions as needed.

By using the `<picture>` element with `<source>` and `srcset`, you can provide optimized images for various screen sizes, enhancing performance and user experience.

**Figcaption and Figures**

After discussing how to add an image to a web page, let's explore how to match a caption to that image. We have two additional elements to consider when it comes to images, or specifically, figures. Here is a straightforward illustration to understand this better.

```html
<figure>
  <img src="path/to/dog.jpg" alt="A happy dog playing in the park">
  <figcaption>A happy dog playing in the park</figcaption>
</figure>
```

**Explanation**

- **`<figure>`**: This element is used to group the image and its caption, providing a semantic meaning to the browser and search engines.
- **`<img>`**: The image element where `src` is the path to the image file and `alt` provides alternative text for the image.
- **`<figcaption>`**: This element provides a caption for the image, which is clearly associated with the image through its placement within the `<figure>` element.

This markup ensures that the image and caption are semantically connected, enhancing accessibility and search engine understanding.

## 🎥 HTML Working with Media

**Working with Audio**

The audio element is different from the image element because it has both an opening and a closing tag. This makes it more modern and gives it more power and flexibility. Just like the image element, we use a source attribute to provide the URL of the audio file. <br>

`<audio controls src="audio.mp3"></audio>` <br>

<p>
  You might wonder why there is both an opening and closing tag for the audio element. Well, that is because the source element can be used to specify multiple audio files, similar to how the picture element was used. 
</p>
<p>
  This can be helpful if a new file format is used that is not supported in all browsers while providing a fallback for older ones. To achieve this, remove the source attribute from the audio element and place it on a separate source element. This accomplishes the same outcome as the previous example but allows for the addition of other source elements with alternative audio file formats.<br>

```html
  <audio controls>
    <source src="audio1.mp3" type="audio/ogg">
    <source src="audio2.mp3" type="audio/mpeg">
    Your browser does not support this type of audio.
  </audio>
```
</p>

Furthermore, it is possible to provide fallback text within the audio element, which will only be displayed if the browser does not understand the audio element at all. 

**Working with Video**

<p>
  Just like the audio element, the video element has an opening and closing tag. To display a video, use the source attribute to specify the video file. And if the controls attribute is added, the browser will automatically create a video player.<br>

```html
<video controls>
  <source src="video1.mp3" type="video/mp4">
  <source src="video2.mp3" type="video/webm">
</video>
```
</p>

<p>
  Just like with image formats like PNG, JPEG, GIF, or SVG, there are different codecs that can be used to encode video files. Video files contain a lot of data, and if not compressed, they become too large to be efficiently transmitted over the internet. Internet videos, therefore, use a mechanism to compress all the data into a smaller package. 
</p>

<p>
  There are a couple of issues that come with working with videos in HTML. One of them is that a commonly used video codec H.264 is patented and may increase in pricing. HTML also does not have a mechanism to switch video quality based on screen sizes and internet connections. Major streaming platforms such as Netflix, Hulu, HBO, YouTube, and Vimeo tackle this issue using a technique called adaptive bitrate streaming. This complex process involves a server farm of transcoding robots, ensuring seamless switching between different resolutions as users watch videos.
</p>

Due to the intricacies involved, it is common for websites to utilize embed codes from video hosting services rather than directly employing the video element. This choice is often made to simplify the process and leverage the capabilities provided by such services. 

**Working with Captions and Subtitles**

<p>
  It is quite amazing how audio and video can be added to a website, but not everyone can always hear or understand it. Some people may be deaf, while others may have intermittent hearing or difficulty understanding content due to various other factors. Even for those who can hear, it is not always convenient to listen. 
</p>

<p>
  For example, you might want to watch a video, but you cannot use speakers or headphones in certain places. Or perhaps you are listening, but the speaker's accent or fast pace makes it hard to comprehend. You might be experiencing one of these situations right now while using captions for a video. Luckily, the web gives the power to provide content in multiple ways at the same time. 
</p>

<p>
  We use the track element and link it to a text file to add captions to the video. This element adds functionality to the video player, allowing viewers to toggle captions on and off or switch between different subtitle options. On the web, a file format called ibvtt, which stands for web video text tracks, will be used. It is a simple text file with a vtt extension that follows a specific convention for providing information. In the file, each line of text is accompanied by a time code, indicating when it should be displayed in the video.
</p>
<p>
  To display these captions on the video, insert a track element within the video element. Similar to the source element, it is one of the options the browser uses to render the video player. On the track element, use the source attribute to specify the file, the kind attribute to indicate that it contains captions, and a label attribute to display the caption option as "English" in the player. Additionally, use the source lang attribute to indicate the language and add a default attribute to make this track the default choice when captions are enabled.
</p>

Captions and subtitles are often required by law to be included.<br>

**Embessing Media via Iframes**

Embedding refers to taking content from one site and placing it within the middle of another site's page. 

<p>
  There is a wide range of content that can be embedded on a page. For instance, a map from Google or Mapbox, a code demo from CodePen or Glitch, or even a slide deck from Speaker Deck or Notist. It is common practice to embed complex content from a service that handles the technical aspects.
</p>

Syntax:<br>
`<iframe src="url" title="description"></iframe>`

<p>
  When using a content management system (CMS) that someone else has set up, like WordPress or Drupal, you might not be able to simply copy and paste random embed codes from other websites. These CMS platforms usually have specific ways to allow URLs or shortcodes from trusted sources. To embed things like YouTube videos, it is best to consult someone who knows how to use the CMS effectively.
</p>

When adding Iframes always think about the security issues.

## 🔍 HTML Content Identification

**HTML Language Support**

<p>
  The internet is worldwide, and people speak various languages. In HTML, there are tools to indicate the language of your content. By setting things up correctly, search engines will understand which language websites are in. Spell checkers will provide the appropriate dictionaries, and when a browser reads the content aloud, it will pronounce the words correctly. 
</p>

```html
<html lang="en-US">
  ...
</html>
```
<p>
  The lang attribute is used to specify the language of a webpage. If the whole page is in one language, it is quite simple. Set the language on the main element that wraps everything else, which is usually the HTML element. It may only be required to set it once, like in a template file that applies to the entire site, but do not forget to do it! 
</p>

<p>
   If your webpage has multiple languages, specify the language for each part of the content. Use the lang attribute on any element. For example, if most of the page is in Mexican Spanish but there are block quotes in Nahuatl, use lang="es-mx" on the outer HTML element and lang="nah" on the block quote elements. 
</p>

<p>
  It is also important to specify the content's direction. Most languages flow from left to right horizontally, but some flow from right to left. Use the dir attribute to indicate the direction, and it can be applied to any element. If all the content on your page follows the same direction, define it once on the outer HTML element.
</p>

`<html lang="en-gb" dir="ltr">`<br>
`<html lang="ar" dir="rtl">`<br>
<p>
According to the examples, one of them is indicated that the content will be in British English and it goes left to right. The other example shows that this page is in Arabic and the content flows from right to left. When there is a mix of content, ensure to indicate the change in direction for each phrase is set.  
</p>

`<meta charset="UTF-8">`<br>
<p>
 To wrap things up, do not forget to set the charset for your project. What is that? Well, each language uses its own set of characters or alphabet. In the past, computer character sets were limited and mainly focused on the Latin alphabet. You may have heard of ASCII, which was created in the 1960s and consisted of only 128 characters from English typewriters. Nowadays, Unicode, particularly UTF-8, is widely used. It is like a massive specification that encodes content to support a vast range of characters, scripts, and even emojis. Unicode started with around 7,000 characters in 1991 and has now expanded to over 137,000, aiming to encompass all languages, scripts, and communication forms like Braille and musical notation.
</p>

<p>
  To specify the charset in HTML, simply include a meta charset tag that equals UTF-8. Place this meta element within the head element on every page of the website, which will be explained further in the chapter eight: HTML Integrations.
</p>

**HTML Generic Elements, Div and Span**

<p>
  Sometimes we simply need a method to group elements or highlight a phrase. Other times, we need to target a specific part of the DOM with CSS or Javascript, even if there is no real meaning behind it. In such cases, we have two trusty elements at our disposal: div and span. If you have worked as a developer writing HTML, chances are you have come across these elements before.
</p>

`<div>` Block level element<br>
`<span>` Inline element

<p>
  Technically you can get away with using divs and spans for everything. Some developers even put their titles in divs and make spans pretend to be buttons. The HTML will not give an error, and the browser will still try its best to do its job and parse the page. But to be honest, it is not good practice. It adversely affects many users. We strongly urge you to avoid using divs and spans for every little thing. Opt for the appropriate HTML element that serves the purpose. 
</p>

<p>
  Now, with that being said, there are times when a generic element is needed. Div is a block-level element, while span is an inline element. They essentially do nothing until CSS or Javascript is applied to them.
</p>

## 🧠 HTML Integration

**HTML Page**

<p>
  When you want to visit a website, you open a web browser or web view and enter a URL. You can either type it in the address bar, click on a search result or link, or even open an app that triggers it. Regardless, a URL is involved. The web server responds by sending back the specific HTML file located at that address. 
</p>
<p>
  In the early days of the web, everything needed to display a webpage was contained in a single HTML file, along with images, but things have gotten more complex now. Text is often stored in databases, and multiple static files are combined in real-time, customized for each user. Visual styling is in CSS files, JavaScript is in separate JavaScript files, and there are additional files for images, video, audio, and ads.
</p>

<p>
  Nowadays, what users see when a page loads is usually a mix of different files. However, the basic process of the web remains the same. Users visit a URL, which prompts a request for an HTML file, and the server returns a single HTML file. The browser reads the HTML file and follows its instructions. This process is consistent every time. So, that initial HTML file that is returned when a web page is requested is incredibly important. It serves as the central hub for everything that happens after the site first loads.
</p>
Once the HTML file is built, there are a few crucial parts that every web page needs. 

1. Firstly, the file should begin with a doctype statement, which indicates the era of this HTML file. In the past, there were different doctype declarations for older HTML versions. By including this one, we are saying, "Hey, this is a modern web page, so follow modern best practices and treat it accordingly." 
2. Next, we enclose everything else on the page within an HTML element, which means an element named HTML. It tells us that all the content within it is HTML. Place the opening HTML tag at the top and the closing HTML tag at the bottom. 

<p>
Inside the HTML element, there are two main parts where everything goes: the head and the body. Create them using the head and body elements. The head contains all the metadata that the browser needs to know but will not display on the page. The body, on the other hand, is for all the content and is composed of various elements already discussed in this course. 
</p>

**Document Head**

<p>
  The Head of a html file is where you put additional information about the webpage such as the language, character set attribute, title and search engine optimization tags. You may also include links to different file e.g a Content Delivery Network(CDN), CSS and JavaScript files etc. 
</p>
<p>
  The link element is a crucial component used extensively within the head section. It serves to connect various assets that should load, such as CSS files, fonts, and favicons. To inform the browser about the type of asset, utilize the rel attribute.
</p>
<p>
  The script tag is a commonly used element in an HTML document's head. It instructs the browser to load a JavaScript file. Although it is typically placed at the end of the document, some also include it in the head. <br>

  `<script src="index.js"></script>`
  
</p>

**Content Structuring**

<p>
  Lets discuss the typical structure inside the body.
</p>

1. The main element is used once per webpage and tells the browser where the main content is located.
2. The header and footer elements mark the header and footer areas on the page. Do not confuse header with head though. Head is where the file's metadata lives and is not displayed to users. Header is used for site headers, article headers, and headers within the content. A header is usually found at the top of most web pages and may include a logo, site name, and navigation.
3. The footer signifies that there are extra things to convey, regardless of its position on the page.
4. The article element wraps around any type of content unit, whether it is a long written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content.
5. The section element is used to mark sections of content. For example, in a long essay with subheadings, each segment can be wrapped in a section element. It is also useful for dividing different topic zones on a website. Each section typically starts with its own headline.
6. Lastly, the aside element is for content that is off to the side, like sidebar information or additional details that accompany an article but are not part of its main flow. Advertisements can also be marked as an aside. Although the position on the page does not matter, the semantic meaning of these elements is crucial. 

## 📚 HTML Working with Forms and Interactive Elements

**Form Fundamentals**

<p>
  Form fields have been an essential part of the web for a long time. They are used for various tasks like logging into websites, making purchases, conducting searches, and adding content. 
</p>
<p>
  It is important to use semantic form elements in HTML instead of divs and spans because it allows us to leverage the built-in power of the browser. This way, we avoid wasting time and effort trying to recreate functionalities that already exist in the browser. Moreover, by using HTML form elements, we ensure that forms will be compatible with all devices and input/output hardware, even those we may not be familiar with. 
</p>


**Basic Elements**


1. **Form Element**:
   - Use the `<form>` element to define the form.
   - Example:
     ```html
     <form>
       <!-- form contents go here -->
     </form>
     ```

2. **Input Fields**:
   - Include two input fields for the user's name and email.
   - Example:
     ```html
     <label for="name">Name:</label>
     <input type="text" id="name" name="name">

     <label for="email">Email:</label>
     <input type="email" id="email" name="email">
     ```

3. **Submit Button**:
   - Use the `<button>` element to create a submit button.
   - Example:
     ```html
     <button type="submit">Sign Up</button>
     ```

**Functional Form**
- Add `action` and `method` attributes to the `<form>` element.
- Note: Using the "get" method is not secure for real websites.
- Example:
  ```html
  <form action="response_page.html" method="get">
    <!-- input fields and button -->
  </form>
  ```

**Input Names**
- Ensure input fields have `name` attributes to capture the data.
- Example:
  ```html
  <input type="text" id="name" name="name">
  <input type="email" id="email" name="email">
  ```

**Accessibility**
- Ensure labels are properly connected to input fields for accessibility.

**Option 1: Using `for` Attribute**
- Add a `for` attribute to the `<label>` that matches the `id` of the `<input>`.
- Example:
  ```html
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  ```

**Option 2: Wrapping Input with Label**
- Wrap the `<input>` element inside the `<label>`.
- Example:
  ```html
  <label>Name:
    <input type="text" name="name">
  </label>
  ```

**Testing Accessibility**
- Verify functionality by clicking on the label to ensure focus jumps to the corresponding input.

<p>
  Inputs for forms can have placeholders and buttons "type" can be used to distinguish what the button is for. Forms can be styled using CSS to look better.
</p>

## 📊 Organizing Tabular Information in HTML

**HTML Tables**

<p>
  You might have heard somewhere along the way that HTML tables are evil, that you should never use a table, or at least that is what some people have heard or thought they heard but it is not true. It is not bad to use an HTML table for tabular data. In fact, you should use an HTML table when your content is a table, absolutely. What you should not do is misuse HTML table elements and pretend that you are making a table when you are not. 
</p>

**Building HTML Tables**

To create an HTML table, you use several different HTML elements in just the right combination. Table, TR, TH, and TD. 

<p>
  The table element wraps around the whole table, around all our content and markup for that table, marking the beginning and end of the table itself. The TR element stands for table row and wraps around a set of elements, defining them as belonging to the same row. The TH element stands for table header and defines a header for a column. The TD element stands for table data and marks up the cells of data. 
</p>
<p>
  Those are the basics of table markup. There is a lot more that can be done to create a complex HTML table, ways to have content span multiple rows, or multiple columns. We could define a header, body, and footer for the table, or add a caption. There are many courses readily available that go deeper into HTML tables, including how to make an HTML email template. For this course, what is covered is the basics of an HTML table, the table element, TR for table rows, TH to mark content that is in a header, and TD for marking up the content of each table cell.
</p>

--
