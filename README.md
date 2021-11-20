# html_story
# Chapter 1

## HTML Introduction 

- The Web is made out of three programming languages, HTML, CSS and Javascript. HTML stands for HyperText Markup Language. HTML marks up the content of a site. Basically it tells the user's computer what things are. CSS stands for Cascading Style Sheets. CSS provides visual styling and layout for everything on the web page. It makes each web page look the way that it looks, color, typography and size. And we can add simply animations and interactions through CSS. JavaScript is a programming language that provides the ability to create more powerful interactivity.

<!-- [Quiz 1](https://github.com/user/repo/blob/branch/Quiz.md) -->

# Chapter 2

## HTML looks like this
```html
<p>Hello World</p>
```
- In this case, p stands for paragraph. We make this HTML by starting out with a less-than symbol, followed by the correct letter, or word, or abbreviated word, and finishing with a greater-than symbol. That makes what's called a tag, an HTML tag. Basically, all HTML markup looks like this. The syntax itself is fairly simple. The trickier part is knowing which tags to use when. There are actually two kinds of tags, two flavors, opening tags and closing tags. This p is an opening tag. The closing tag is very similar, but it has a slash in it. Less-than symbol, a forward slash, the letter or word that matches the tag that we're closing, and a greater-than symbol. Don't forget, include the closing tag.

### The HTML p element defines a paragraph. [codepen](https://codepen.io/fetian/pen/Exvomor)


```html
<p> Weclome From Egypt.</p>
```

### HTML headings are defined with the h1 to h6 tags. [codepen](https://codepen.io/fetian/pen/ZEJvKrM)

- &lt;h1> defines the most important heading. &lt;h6> defines the least important heading.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

```

### HTML Formatting Elements [codepen](https://codepen.io/fetian/pen/bGraWMr)

- Formatting elements were designed to display special types of text:

```html
<b> - Bold text </b>
<strong> - Important text </strong>
<i> - Italic text </i>
<em> - Emphasized text </em>
<mark> - Marked text </mark>
<small> - Smaller text </small>
<del> - Deleted text </del>
<ins> - Inserted text </ins>
<sub> - Subscript text </sub>
<sup> - Superscript text </sup>
```

### HTML Lists [codepen](https://codepen.io/fetian/pen/OJjzmEp)
- HTML lists allow web developers to group a set of related items in lists.

- There are three kinds of lists. Unordered lists, ordered lists, and definition lists. 

### 1. Unordered HTML List

```html 
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

```

### 2. Ordered HTML List

```html
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

```

### 3. Definition HTML Lists

```html
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>

```

### HTML blockquote for Quotations [codepen](https://codepen.io/fetian/pen/OJjzmwm)

- The HTML &lt;blockquote> element defines a section that is quoted from another source.

- Block Elements.


```html
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature.
The world's leading conservation organization,
WWF works in 100 countries and is supported by
1.2 million members in the United States and
close to 5 million globally.
</blockquote>

```


### HTML q for Short Quotations [codepen](https://codepen.io/fetian/pen/ZEJvKqm)

- The HTML &lt;q> tag defines a short quotation.

- Inline Elements

```html
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>

```


### Block Elements VS Inline Elements

| Block                        | Inline                     |
| ---------------------------- | ---------------------------|
| Always starts on a new line  | Not start on a new line    |
| Takes up the full width      | Takes up as much width     |
| Example:                     | Example:                   |
| &lt;blockquote>              | &lt;a>                     |
| &lt;div>                     | &lt;em>                    |
| &lt;form>                    | &lt;q>                     |
| &lt;h1>                      | &lt;cite>                  |
| &lt;li>                      | &lt;small>                 |
| &lt;ol>                      | &lt;img>                   |
| &lt;ul>                      | &lt;span>                  |
| &lt;table>                   | &lt;strong>                |
| &lt;dd>                      | &lt;df>                    |
| &lt;dl>                      | &lt;br>                    |


### HTML Dates and Times [codepen](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time)

- DATE : YYYY:MM:DD

- TIME : hh:mm:ss

```html
<time datetime="2020-05-8">May 8, 2020</time>
<time datetime="20:15"> 8:15 pm</time>
``` 

### Code , pre and br [codepen](https://codepen.io/fetian/pen/KKvgYzK)

- The &lt;code> element defines a piece of computer code.

- The &lt;pre> element defines preformatted text.

- The &lt;br> tag inserts a single line break.


### subscripts , supscripts and small

- The &lt;sub> tag character below the normal line like H<sub>2</sub>O.

- The &lt;sup> tag character above the normal line like 5<sup>2<sup>.

- The &lt;small> tag defines smaller text like <small>copyright</small>.


Notes : MathML for mathematical and scientific content.

<!-- [Quiz 2](https://github.com/user/repo/blob/branch/Quiz.md) -->

# Chapter 3

### Debugging HTML
-  Powerful debugger,that will help track and eliminate bugs, This debugger is browser Chrome.

- To open Chrome DevTools:

   * Select More Tools > Developer Tools from Chrome’s Main Menu.
   * Right-click a page element and select Inspect.
   * Press Command+Option+I (Mac) or Control+Shift+I (Windows, Linux).

### HTML Attributes

* All HTML elements can have attributes
* Attributes provide additional information about elements
* Attributes are always specified in the start tag
* Attributes usually come in name/value pairs like: name="value"

- most important Global Attributes: Class, ID, Lang and Dir.

```html
<p lang='ar' dir='rtl'>هذه الفقره باللغه العربيه ، لذا يجب الانتقال من اليمين لليسار.</p>

<p lang='en' dir='ltr'>This Paragraph is in English. It flows from left to right.</p>

```
<p lang='ar' dir='rtl'>هذه الفقره باللغه العربيه ، لذا يجب الانتقال من اليمين لليسار.</p>

<p lang='en' dir='ltr'>This Paragraph is in English. It flows from left to right.</p>

### ARIA Roles HTML

- HTML attributes that provide accessible information about that specific element, make web content more accessible to people with disabilities.

```
<h1 aria-label="Hi">
	<div aria-hidden="true">
	<span>H</span>
	<span>i</span>
	</div>
</h1>

```

### HTML Comments

- You can add comments to your HTML source by using the following syntax:

```html
<!-- Write your comments here -->

```

### HTML Entities

*  HTML entity is a piece of text that begins with an ampersand (&) and ends with a semicolon (;), Entities used to display reserved characters. 

| Result | Description         | Entity Name	| Entity Number	|
|--------|---------------------|----------------|---------------|
|	     | non-breaking space  |	&amp;nbsp;  |	  &amp;#160;|
|   <    |  less than	       |     &amp;lt;   |	  &amp;#60; |
|   >	 |greater than	       |     &amp;gt;   |     &amp;#62; |
|   &    |ampersand            |	&amp;amp;   |     &amp;#38; |
|   "    |double quotation mark|	&amp;quot;	|     &amp;#34; |
|   '	 |single quotation mark|	&amp;apos;  |	  &amp;#39;	|
|   ¢    |cen                  |	&amp;cent;  |	  &amp;#162;|
|   £    |pound	               |    &amp;pound;	|     &amp;#163;|
|   ¥    |	yen                |     &amp;yen;  |	  &amp;#165;|
|   €    |euro                 |     &amp;euro; |	 &amp;#8364;|
|   ©	 |copyright            |	&amp;copy;  |	  &amp;#169;|
|   ®	 |trademark            |	&amp;reg;	|     &amp;#174;|


<!-- [Quiz 3](https://github.com/user/repo/blob/branch/Quiz.md) -->

# Chapter 4

### HTML Links

The HTML &lt;a> tag defines a hyperlink.

<a href="https://example.com">This is a link.</a>
```html
 <!-- Absolute URL -->
<a href="https://example.com">This is a link.</a>
<p><a href="https://example.com"><img src="https://tinyurl.com/y3ycfl3e"></a></p>

<!-- Relative URL -->
<a href="/page2.html">Go to page 2</a>

```
### Navigation

<nav role="navigation" aria-label="main menu">
  <ul class="navbar">
    <li><a href="#">Home</a></li>
    <li><a href="#">People</a></li>
    <li><a href="#">Prices</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>

```html
 <!-- Navigation -->
<nav role="navigation" aria-label="main menu">
  <ul class="navbar">
    <li><a href="/">Home</a></li>
    <li><a href="/people">People</a></li>
    <li><a href="/prices">Prices</a></li>
    <li><a href="/contact">Contact</a></li>
  </ul>
</nav>

 <!-- Breadcrumb -->
<nav role="breadcrumb">
  <ol class="breadcrumbs">
    <li><a href="/">Home</a></li>
    <li><a href="/people">Blog</a></li>
    <li><a href="/contact">March</a></li>
    <li>March 9th Update</li>
  </ol>
</nav>
<!-- Home > Blog > March > March 9th Update -->

 <!-- footer links  -->
 
<footer>
  <a href="/about/privacy">Privacy Policy</a>
  <a href="/about/legal">Terms of Service</a>
</footer>
<!-- Privacy Policy | Terms of Service -->

```
<!-- [Quiz 4](https://github.com/user/repo/blob/branch/Quiz.md) -->

# Chapter 5

### Html Images 

The HTML &lt;img> tag is used to embed an image in a web page.

```html
<img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/maggie.jpg" alt="shiny black dog looking pensive" width="400" height="300">
```

### Images Formats

- The goal is to have the highest quality possible with the smallest file size possible. Each file format takes a different approach to solving this. Each uses a different technique for compressing the image. There are four main file formats commonly used on the web today.Each is good at compressing certain types of images and not as good at compressing others. 

* GIF : It's good at compressing illustrations that have large areas of a single color.

* SVG : SVG is great for logos, icons, and other kinds of illustration.

* JPG : It's good solution when you have a photograph and you need part of the photo to be transparent. 

* PNG :  PNGs are newer format for the web than GIFs or JPGs. 

### Responsive Image 

- The simplest way to support different screens is to create multiple copies of our image in different resolutions and then tell the browser that those copies are available. Using Attribute srcset.

```html
<!-- depend on pixel density -->
<img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog-480.jpg" 
     alt="shiny black dog looking pensive" 
     width="480" height="360"
     
     srcset="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog-960.jpg 2x, 
	   	  	 https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog-1440.jpg 3x, 
		 	 https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog-1920.jpg 4x" 
>

<!-- depend on viewport width -->
<img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog-480.jpg" 
		 alt="shiny black dog looking pensive" 
		 width="480" height="360"
         
     srcset="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog-480.jpg  480w, 
	   	  	https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog-960.jpg 960w, 
	   	  	https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog-1440.jpg 1440w, 
		 	https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog-1920.jpg 1920w" 
>
```
### Picture 

* The &lt;picture> tag uses to more flexibility in specifying image resources.

```html

<picture>
  <source media="(min-width:600px)"
    srcset="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-320.jpg  320w,
            https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-480.jpg  480w, 
            https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-720.jpg  720w,
            https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-960.jpg  960w, 
            https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-1440.jpg 1440w, 
            https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-1920.jpg 1920w" >
  <source srcset="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-cropped-320.jpg 320w,
    https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-cropped-480.jpg 480w, 
    https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-cropped-720.jpg 720w,
    https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-cropped-960.jpg 960w" >
 
 <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/dog2-480.jpg" 
       alt="smiling black dog" height="360px" width="480px">
</picture>

```
### Image Figure and Figcaption

Use a &lt;figure> element to mark up a photo in a document, and a &lt;figcaption> element to define a caption for the photo:

```html
<figure>
  <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/maggie2.png" width="960" height="720" alt="shiny black dog in the sun">

  <figcaption>Maggie the dog enjoys resting in a field, after a long day of chasing squirrels.</figcaption>
</figure>
```
<!-- [Quiz 5](https://github.com/user/repo/blob/branch/Quiz.md) -->

# Chapter 6

### HTML Audio [codepen](https://codepen.io/fetian/pen/QWMdbOG)

* The &lt;audio> HTML element is used to embed sound content in documents. It may contain one or more audio sources, represented using the src attribute or the &lt;source> element: the browser will choose the most suitable one.

#### Media Types

| File Format  |  Media Type |
| ------------ | ----------- |
|  MP3         | audio/mpeg  |
|  OGG         | audio/ogg   |
|  WAV         | audio/wav   |

### Attributes Audio
* controls : To allow the user to control audio playback, including volume, seeking, and pause/resume playback.

* autoplay : the audio will automatically begin playback.

* loop : the audio player will automatically seek back to the start upon reaching the end of the audio.

```html
<audio controls>
  <source  src="http://example.com/birds.ogg" type="audio/ogg">
  <source src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/birds.mp3" type="audio/mpeg">
  
  Sorry your browser doesn't not support audio.
</audio>

<!-- codec=opus; https://opus-codec.org/ -->
```
### HTML Video [codepen](https://codepen.io/fetian/pen/jOLybqZ)

* The &lt;video> HTML element embeds a media player which supports video playback.

```html
<video controls>
	<source src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.480p.vp9.webm" type="video/webm">
	<source src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.480p.h264.mp4" type="video/mp4">
</video>
```

<!-- Video Compression 
H.264 -> not opensource -> to mp4 
WebM -> from Google https://www.webmproject.org/tools/
AV1 -> s an open, royalty-free video coding format initially designed for video transmissions over the Internet.
switching from one resolution to another Using technology: ABS
Adaptive bitrate streaming dynamically tracks CPU, memory capacity, and network conditions, and then delivers video quality to match. -->

### Captions and Subtitles For Video [codepen](https://codepen.io/fetian/pen/WNERrwP)

* The &lt;track> HTML element is used as a child of the media elements, &lt;audio> and &lt;video> . It lets you specify time-based data, for example to automatically handle subtitles.

- Attributes For track

 * default : This attribute indicates that the track should be enabled unless the user's preferences indicate that another track is more appropriate. This may only be used on one track element per media element.

 * kind : How the text track is meant to be used.The following keywords are allowed:
  * subtitles 
   * Subtitles provide translation of content that cannot be understood by the viewer.
   * Subtitles may contain additional content, usually extra background information.
  * captions
   * Closed captions provide a transcription and possibly a translation of audio.
   * It may include important non-verbal information such as music cues or sound effects.
   * Suitable for users who are deaf or when the sound is muted.

 * label : title of the text track which is used by the browser when listing available text tracks.

 * src : Address of the track (.vtt file). Must be a valid URL
 * srclang : Language of the track text data.


```html
<video controls>
  <source src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.480p.vp9.webm" 
    type="video/webm">
  <source src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.480p.h264.mp4" 
    type="video/mp4">
  
  <track src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.vtt"
         kind="captions"
         label="English"
         srclang="en"
         default>
  
   <track src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.es-la.es.vtt"
         kind="subtitles"
         label="Español"
         srclang="es">
  
  <p>This would be a video of a moonwalk, if your device supported playing this video.</p>
</video>
```

### Embedding other media through iframes

* The &lt;iframe> HTML element represents a nested browsing context, embedding another HTML page into the current one.


```html
<iframe width="560" height="315" 
        src="https://www.youtube-nocookie.com/embed/5wpp3vFM41U" 
        title="YouTube video player" 
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
```

<!-- [Quiz 6](https://github.com/user/repo/blob/branch/Quiz.md) -->

# Chapter 7

### lang

* lang Attribute : define the language of the Web page or element.

* dir Attribute : Specifies the direction for text to be written.
    * ltr : left to right
    * rtl : right to left
- charset Attribute : Defines the alphabet or set of characters for the script language.
    - ASCII : An encoding standard limited to 128 characters, focused on the needs of certain European languages.   
    - Unicode : A Universal encoding standard for characters encompassing many languages.

```html

<html lang="en-US" dir="ltr">
    <meta charset="UTF-8">
    ...

    <p lang="ar" dir="rtl">

        مرحبا بالعالم
        <span lang="en" dir="ltr">Hello world !</span>
    </p>
</html>

```

### Generic elements: div and span [codepen](https://codepen.io/fetian/pen/ZEJvQOB)

* The &lt;div> is a generic block-level container for flow content. It has no effect on the content.
* The &lt;span> is a generic inline container for phrasing content, It can be used to group elements for styling purposes.
    * Global Attributes : div and span can take global attributes
        - id
        - class
        - lang
        - aria roles 

---
**NOTE**
Don't use divs and spans for everything.Use the proper HTML element for the task at hand.
When should you use a div? You answered it yourself: when a more specific element is unavailable.
---
###  Major sectioning elements that typically go directly in the &lt;body> element

* &lt;header> element represents introductory content,It may contain some heading elements but also a logo, a search form, an author name, and other elements.

* &lt;footer> typically contains information about the author of the section, copyright data or links to related documents.

* &lt;section> element represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it.

* &lt;nav> element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents.

* &lt;article> lement represents a self-contained composition in a document, Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment.

* &lt;aside>  element represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars.

* &lt;main>  element represents the dominant content of the body of a document. The main content area consists of content that is directly related to or expands upon the central topic of a document.

* [and more!](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

<!-- [Quiz 7](https://github.com/user/repo/blob/branch/Quiz.md) -->

# Chapter 8

### HTML page

* HTML files are key building block of the web. Anytime anyone wants to go to a website, they start by opening up some kind of web browser or web view and going to a URL, hitting that URL sends a request for an HTML file, a server returns a single HTML file, the browser reads the HTML file and does what it says. 


### HTML Page Structure

* All HTML 5 documents must start with a &lt;!DOCTYPE html> declaration. 
* The &lt;html> element is the container for all other HTML elements.
* The &lt;head> element is a container for metadata (data about data).
    - &lt;title> tag defines the title of the document.
    - &lt;meta> tag defines metadata about an HTML document.
    - &lt;link> tag defines the relationship between the current document and an external resource.


* The &lt;body> element contains all the contents of an HTML document, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

```html
<!DOCTYPE html>
<html>
<head>
    
    <title>Page Title</title>
    <meta charset="UTF-8">
    <meta name="description" content="description page">
    <meta name="keywords" content="keywords for search engines">
    <meta name="author" content="author page">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="mystyle.css">

</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

<script src="myscripts.js"></script>
</body>
</html>

```
* The &lt;script> tag is used to embed a client-side script (JavaScript), put it at the end of an HTML document so the browser loads JavaScript after everything else has loaded.

<!-- [Quiz 8](https://github.com/user/repo/blob/branch/Quiz.md) -->

# Chapter 9 

### The Form element [1](https://codepen.io/fetian/pen/gOxoLWM)[2](https://codepen.io/fetian/pen/OJjzbmb)

* The &lt;form> element represents a document section containing interactive controls for submitting information.

* The &lt;form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.



```html
<form action="" method="get"> 
			<div>
				<label for="name">Name</label>
				<input name="name" id="name" type="text" >
			</div>
			<div>
				<label for="email">Email</label>
				<input name="email" id="email" type="email" placeholder="me@example.com" required >
			</div>
			<button type="submit">Sign up</button>
		</form>
```


* The &lt;label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.
* An &lt;input> element can be displayed in many ways, depending on the type attribute.

* To associate the &lt;label> with an &lt;input> element, you need to give the &lt;input> an id attribute. The &lt;label> then needs a for attribute whose value is the same as the input's id. or you can nest the &lt;input> directly inside the &lt;label>


### Form Attributes

* The action attribute defines the action to be performed when the form is submitted.

* The method attribute specifies the HTTP method to be used when submitting the form data. form-data can be sent as URL variables (with method="get") or as HTTP post transaction (with method="post").

### Input Attributes

* The name attribute is used to reference elements in a JavaScript, or to reference form data after a form is submitted.

* The input value attribute specifies an initial value for an input field.
* The input placeholder attribute specifies a short hint that describes the expected value of an input field.works with input types: text, search, url, tel, email, and password.

* The input required attribute specifies that an input field must be filled out before submitting the form. works input types: text, search, url, tel, email, password, date pickers, number, checkbox, radio, and file.

* The input autofocus attribute specifies that an input field should automatically get focus when the page loads.

* The input autocomplete attribute specifies whether a form or an input field should have autocomplete on or off.

<!-- [Quiz 9](https://github.com/user/repo/blob/branch/Quiz.md) -->

# Chapter 10 

### The Table element [codepen](https://codepen.io/fetian/pen/JjyMbdw)

* The &lt;table> element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.

```html
<table>
  <tr>
    <th>Language</th>
    <th>Description</th>
    <th>Authore</th>
  </tr>
  <tr>
    <td>JavaScript</td>
    <td>JavaScript is a lightweight, cross-platform, and interpreted scripting language.</td>
    <td>Brendan Eich</td>
  </tr>
  <tr>
    <td>Python</td>
    <td>Python is an interpreted, object-oriented, high-level programming language with dynamic semantics</td>
    <td>Guido van Rossum</td>
  </tr>
</table>

```
### Table Element

| Element                | Name              | Purpose                         | Attributes              |
| -----------------------| ------------------|---------------------------------|-------------------------|
| &lt;table>&lt;table/>  | Table             | Wraps the whole table           |                         |
| &lt;tr>&lt;tr/>        | TR - table row    | Wraps around a set of elements  | colspan, rowspan,header |
| &lt;th>&lt;th/>        | TH - table header | Defines a header for a column   | colspan, rowspan,scope  |
| &lt;td>&lt;td/>        | TD - table data   | Marks the actual bits of data   |                         |

<!-- [Quiz 10](https://github.com/user/repo/blob/branch/Quiz.md) -->


written by [Fetian Ans](https://fetian-ans.firebaseapp.com/)
