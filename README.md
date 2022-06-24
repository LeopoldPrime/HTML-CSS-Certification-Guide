# What is HTML

HTML stands for Hyper Text Markup Language,
HTML is the standard markup language for creating Web pages,
HTML describes the structure of a Web page,
HTML consists of a series of elements.

# HTML Basics 

HTML elements tell the browser how to display the content
HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc. Below is an example of elements defining content

```HTML
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

### Example Explained

The ```<!DOCTYPE html>``` declaration defines that this document is an HTML5 document.
The ```<html>``` element is the root element of an HTML page.
The ```<head>``` element contains meta information about the HTML page.
The ```<title>``` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).
The ```<body>``` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
The ```<h1>``` element defines a large heading.
The ```<p>``` element defines a paragraph.

### Example

```HTML
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

## The <!DOCTYPE> Declaration

The ```<!DOCTYPE>``` declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The ```<!DOCTYPE>``` declaration is not case sensitive.

The ```<!DOCTYPE>``` declaration for HTML5 is:
```HTML
<!DOCTYPE html>
```
## HTML Headings

HTML headings are defined with the ```<h1>``` to ```<h6>``` tags.

```<h1>``` defines the most important heading. ```<h6>``` defines the least important heading: 

### Example
```HTML
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```

## HTML Paragraphs
HTML paragraphs are defined with the ```<p>``` tag:

### Example
```HTML
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

## HTML Links
HTML links are defined with the ```<a>``` tag:

### Example
```HTML
<a href="https://www.rootkit.org">This is a link</a>
```
The link's destination is specified in the href attribute. 

Attributes are used to provide additional information about HTML elements.

You will learn more about attributes in a later section of the guide.

## HTML Images
HTML images are defined with the ```<img>``` tag.

The source file (src), alternative text (alt), width, and height are provided as attributes:

### Example
```HTML
<img src="rootkit.jpg" alt="rootkit.org" width="104" height="142">
```
## How to View HTML Source?
Have you ever seen a Web page and wondered "Hey! How did they do that?"

### View HTML Source Code:
Right-click in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

### Inspect an HTML Element:
Right-click on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.

## HTML Editors

Web pages can be created and modified by using professional HTML editors.

However, for learning HTML we recommend a simple text editor like Notepad (PC) or TextEdit (Mac).

We believe in that using a simple text editor is a good way to learn HTML.

## Starting an HTML Document

All HTML documents must start with a document type declaration: ```<!DOCTYPE html>```.

The HTML document itself begins with <html> and ends with ```</html>```.

The visible part of the HTML document is between <body> and ```</body>```.
  
## Making Your First HTML Document

### Step 1: Open Notepad (PC)
Windows 8 or later:

Open the Start Screen (the window symbol at the bottom left on your screen). Type Notepad.

Windows 7 or earlier:

Open Start > Programs > Accessories > Notepad


### Step 1: Open TextEdit (Mac)
Open Finder > Applications > TextEdit

Also change some preferences to get the application to save files correctly. In Preferences > Format > choose "Plain Text"

Then under "Open and Save", check the box that says "Display HTML files as HTML code instead of formatted text".

Then open a new document to place the code.


### Step 2: Write Some HTML
Write or copy the following HTML code into Notepad:

```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>
```

![img_notepad](https://user-images.githubusercontent.com/87269058/175576691-373ca9cd-5879-4d9b-a7e1-ecb3c355b4ad.png)

### Step 3: Save the HTML Page
Save the file on your computer. Select File > Save as in the Notepad menu.

Name the file "index.html" and set the encoding to UTF-8 (which is the preferred encoding for HTML files).

![img_saveas](https://user-images.githubusercontent.com/87269058/175576934-76e94514-12b6-4b40-893e-69d62bba4dab.png)

### Step 4: View the HTML Page in Your Browser
Open the saved HTML file in your favorite browser (double click on the file, or right-click - and choose "Open with").

The result will look much like this:

![img_chrome](https://user-images.githubusercontent.com/87269058/175577041-d2e8016a-eefd-49cd-8523-512471eefd0b.png)

# HTML Elements
The HTML element is everything from the start tag to the end tag:

```<tagname>Content goes here...</tagname>```
Examples of some HTML elements:
```
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

## Nested HTML Elements
HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.

The following example contains four HTML elements (```<html>```, ```<body>```, ```<h1>``` and ```<p>```):

### Example
```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

### Example Explained
The <html> element is the root element and it defines the whole HTML document.

It has a start tag ```<html>``` and an end tag ```</html>```.

Then, inside the ```<html>``` element there is a ```<body>``` element:
```
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
```

The ```<body>``` element defines the document's body.

It has a start tag ```<body>``` and an end tag ```</body>```.

Then, inside the ```<body>``` element there are two other elements: ```<h1>``` and ```<p>```:

```
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

The ```<h1>``` element defines a heading.

It has a start tag ```<h1>``` and an end tag ```</h1>```:

```
<h1>My First Heading</h1>
```

The ```<p>``` element defines a paragraph.

It has a start tag ```<p>``` and an end tag ```</p>```:

```
<p>My first paragraph.</p>
```

## Never Skip the End Tag
Some HTML elements will display correctly, even if you forget the end tag:

### Example
```
<html>
<body>

<p>This is a paragraph
<p>This is a paragraph

</body>
</html>
```
However, never rely on this! Unexpected results and errors may occur if you forget the end tag!

## Empty HTML Elements
HTML elements with no content are called empty elements.

The ```<br>``` tag defines a line break, and is an empty element without a closing tag:

### Example
```
<p>This is a <br> paragraph with a line break.</p>
```
