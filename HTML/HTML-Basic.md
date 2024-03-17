# HTML Basics

HTML Basics comprises essential HTML examples and serves as the cornerstone of web content creation. HTML, or HyperText Markup Language, is used to craft the structure or blueprint of web documents.

## Table of Contents

**1. Basic HTML Document**  
**2. HTML Headings**  
**3. HTML Paragraph and Break Elements**  
**4. HTML Horizontal Line**  
**5. HTML Images**  
**6. Viewing HTML Source Code**  

### Basic HTML Document

Every HTML document initiates with the declaration of an HTML document tag, `<!DOCTYPE html>`. While not mandatory, starting with this tag is a recommended convention. Below are fundamental HTML tags dividing the entire page into various sections like head, body, etc.

**Basic HTML Tags for Document Structure**

Tags | Descriptions
--- | ---
`<html>` | Encloses the entire HTML document, serving as the root element for all HTML content.
`<head>` | Contains header information about the webpage, including title, meta tags, and linked stylesheets. It's part of the document’s structure but isn't displayed on the webpage.
`<title>` | Used within the `<head>` section to define the title of the HTML document, appearing in the browser tab or window.
`<body>` | Encloses the visible content of the webpage, such as text, images, audio, videos, and links.

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
    <!-- Information about the webpage -->
    <!-- This is a comment tag -->
    <title>GeeksforGeeks</title>
</head>
<body>
    <!-- Contents of the webpage -->
    <p>GeeksforGeeks is an online study platform</p>
</body>
</html>
```

### HTML Headings

HTML Heading tags allow the inclusion of headings in webpage content. These tags are primarily written within the body tag. HTML provides six heading tags from `<h1>` to `<h6>`, each displaying the heading in varying font sizes.

**Syntax**
```html
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>
```

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Heading Tag</title>
</head>
<body>
    <h1>Heading 1 (h1)</h1>
    <h2>Heading 2 (h2)</h2>
    <h3>Heading 3 (h3)</h3>
    <h4>Heading 4 (h4)</h4>
    <h5>Heading 5 (h5)</h5>
    <h6>Heading 6 (h6)</h6>
</body>
</html>
```

### HTML Paragraph and Break Elements

HTML `<p>` tags facilitate the writing of paragraph statements on a webpage. They begin with the `<p>` tag and conclude with `</p>`. The `<br>` tag, on the other hand, inserts a single line break.

**Syntax**
```html
<!-- For Paragraph -->
<p>Content...</p>
<!-- For Break -->
<br>
```

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Example of Paragraph and Break Elements</title>
</head>
<body>
    <p>
        HTML stands for HyperText Markup Language.<br> 
        It is used to design web pages using a markup language.<br>
        HTML is a combination of Hypertext and Markup language.<br>
        Hypertext defines the link between web pages.<br>
        A markup language is used to define the text document within the tag which defines the structure of web pages.
    </p>
</body>
</html>
```

### HTML Horizontal Line

The `<hr>` tag in HTML breaks the page into various parts, creating horizontal margins with a line spanning from the left to the right side of the page. This is an empty tag and does not require any additional statements.

**Syntax**
```html
<hr>
```

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML <hr> tag</title>
</head>
<body>
    <h1>Hello GeeksforGeeks</h1>
    <p>
        A Computer Science portal for geeks<br>
        A Computer Science portal for geeks<br>
        A Computer Science portal for geeks<br>
    </p>
    <hr>
    <p>
        A Computer Science portal for geeks<br>
        A Computer Science portal for geeks<br>
        A Computer Science portal for geeks<br>
    </p>
    <hr>
    <p>
        A Computer Science portal for geeks<br>
        A Computer Science portal for geeks<br>
        A Computer Science portal for geeks<br>
    </p>
    <hr>
</body>
</html>
```

### HTML Images

The `<img>` tag is utilized to insert an image into a webpage. The image's source is placed within the `<img src="source_of_image">` tag.

**Syntax**
```html
<img src="image_source">
```

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML img tag</title>
</head>
<body>
    <img src="./awkwardpy/photo1.png">
</body>
</html>
```

### Viewing HTML Source Code

**View HTML Source Code of Entire Page:** To view the source code of a webpage, press `Ctrl + U` or right-click on the page and select the “view page source” option.

**Inspect an HTML Element on a Page:** Right-click on a page and select “Inspect” to view the HTML and CSS behind a specific element.

HTML Basics forms the foundation of web development, covering document structure, tags, attributes, and elements essential for creating webpages. Learning HTML from the ground up is facilitated by this guide, enabling the creation of a first HTML web page.

**Frequently Asked Questions on HTML Basics:**
1. What are the basics of HTML?
   Basic HTML includes mastering document structure, tags, and their attributes and elements.

2. What are the basic rules of HTML?
   Some basic rules of HTML are:

   - The basic HTML structure is fixed with doctype declaration, html, head, title, and body tags. The content then can be added to the body tag.
   - Tags are enclosed in < and >. A tag should have an opening tag (e.g., <h1>) and a closing tag (e.g., </h1>).
   - HTML Tags are not case-sensitive.
