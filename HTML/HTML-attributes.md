# HTML Attributes in GitHub Readme

HTML Attributes facilitate meta-information related to HTML Elements. They are defined with the start tag and usually specified as name/value pairs like `name="value"`. It's essential to note that every attribute name must have a corresponding value written within quotes. The use of single or double quotes is recommended, especially when the value of an attribute itself contains double quotes.

## Table of Content

- [W3 Recommendations for Attributes](#w3-recommendations-for-attributes)
- [HTML Global Attributes](#html-global-attributes)
  - [HTML src Attribute](#html-src-attribute)
  - [HTML alt Attribute](#html-alt-attribute)
  - [HTML width and height Attribute](#html-width-and-height-attribute)
  - [HTML id Attribute](#html-id-attribute)
  - [HTML title Attribute](#html-title-attribute)
  - [HTML href Attribute](#html-href-attribute)
  - [HTML style Attribute](#html-style-attribute)
  - [HTML lang Attribute](#html-lang-attribute)

## W3 Recommendations for Attributes

- Lowercase attribute names are not necessary according to HTML standards but are recommended, especially for stricter document types like XHTML.
- Quote attribute values are suggested according to W3C recommendations.

## Syntax

```html
<element attribute_name="attribute_value">
```

## HTML Global Attributes

List of global attributes supported by all tags.

### HTML src Attribute

The `src` attribute is used to insert an image into a webpage. It specifies the address of the image.

#### Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>src Attribute</title>
</head>
<body>
    <img src="https://media.example.com/image.jpg">
</body>
</html>
```

### HTML alt Attribute

The `alt` attribute is used to display alternative text if the primary attribute (`<img>` tag) fails to display the assigned value. It also serves to describe the image for developers.

#### Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>alt Attribute</title>
</head>
<body>
    <img src="https://media.example.com/image.jpg" alt="Image Description">
</body>
</html>
```

### HTML width and height Attribute

The `width` and `height` attributes adjust the width and height of an image in pixels.

#### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Width and Height</title>
</head>
<body>
    <img src="https://media.example.com/image.jpg" width="300px" height="100px">
</body>
</html>
```

### HTML id Attribute

The `id` attribute provides a unique identification for an element, allowing for targeted access, especially in CSS.

#### Example

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        #element_id {
            color: green;
        }
    </style>
</head>
<body>
    <h1 id="element_id">Welcome to IT-Off Topics</h1>
</body>
</html>
```

### HTML title Attribute

The `title` attribute provides an element explanation when hovering the mouse over it.

#### Example

```html
<!DOCTYPE html> 
<html> 
<head> 
    <title>title Attribute</title> 
</head> 
<body> 
    <h3 title="Hello IT-Off Topics">Hover to see the effect</h3> 
</body> 
</html>
```

### HTML href Attribute

The `href` attribute specifies a link to an address, used primarily with the `<a>` tag.

#### Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>link Attribute</title>
</head>
<body>
    <a href="https://www.example.com/">Click to open in the same tab</a><br>
    <a href="https://www.example.com/" target="_blank">Click to open in a different tab</a>
</body>
</html>
```

### HTML style Attribute

The `style` attribute provides various CSS effects to HTML elements.

#### Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>style Attribute</title>
</head>
<body>
    <h2 style="font-family:Chaparral Pro Light;">Hello IT-Off Topics.</h2>
    <h3 style="font-size:20px;">Hello IT-Off Topics.</h3>
    <h2 style="color:#8CCEF9;">Hello IT-Off Topics.</h2>
    <h2 style="text-align:center;">Hello IT-Off Topics.</h2>
</body>
</html>
```

### HTML lang Attribute

The `lang` attribute specifies the language of the HTML page.

#### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>lang attribute</title>
    <style>
        body {
            text-align: center;
        }
        h1 {
            color: green;
        }
        .lang-info {
            font-style: italic;
        }
    </style>
</head>
<body>
    <h1>IT-Off Topics</h1>
    <h2>lang attribute</h2>
    <p lang="en">A computer science portal for IT-Off Topics</p>
    <p lang="fr" class="lang-info">A computer science portal for IT-Off Topics</p>
    <p lang="es" class="lang-info">A computer science portal for IT-Off Topics</p>
</body>
</html>
```

