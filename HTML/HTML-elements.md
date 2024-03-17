# HTML Elements

HTML Elements are fundamental components of web pages, comprising start and end tags enclosing content. They represent various types of content such as headings, paragraphs, links, and images.

## Table of Content

- [Syntax](#syntax)
- [Nested HTML Elements](#nested-html-elements)
- [Necessity of Adding an End Tag](#necessity-of-adding-an-end-tag)
- [HTML Empty Element](#html-empty-element)
- [Supported Browsers](#supported-browsers)

## Syntax

An HTML element consists of opening and closing tags with content enclosed between them.

```html
<tagname> Contents... </tagname>
```

### Components

#### HTML Element

**Descriptions**

- **Opening tag (`<tagname>`)**: Indicates the start of content.
- **Closing tag (`</tagname>`)**: Marks the end of content.
- **Content**: The actual content within the tags.

Combining these parts creates an HTML element.

### Example 1

In this example, `<p>` is the opening tag, `</p>` is the closing tag, and content is enclosed between them, forming an element.

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Elements</title>
</head>
<body>
    <h2>Welcome To IT-Off Topics</h2>
    <p>Hi IT-Off Topics!</p>
</body>
</html>
```

### Example 2

This example demonstrates the use of the HTML paragraph element.

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Elements</title>
</head>
<body>
    <p>Welcome to IT-Off Topics!</p>
</body>
</html>
```

## Nested HTML Elements

An HTML element used inside another HTML element is termed a nested HTML element.

Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Elements</title>
</head>
<body style="text-align: center">
    <h1>IT-Off Topics</h1>
    <p>Information Technology community</p>
</body>
</html>
```

## Necessity of Adding an End Tag

It's essential to include the end tag of an element to ensure proper rendering of content.

Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Elements</title>
</head>
<body>
    <h2>Welcome To IT-Off Topics</h2>
    <p>Hi IT-Off Topics!
</body>
</html>
```

## HTML Empty Element

HTML elements without content, known as empty elements, don't have an ending tag.

Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Empty HTML Elements</title>
</head>
<body>
    <h2>Welcome To IT-Off Topics</h2>
    <br />
    <p>Hello IT-Off Topics.</p>
</body>
</html>
```

## Supported Browsers

HTML elements are supported across all modern web browsers.
