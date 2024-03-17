# HTML Paragraphs

The `<p>` tag in HTML defines a paragraph. These have both opening and closing tags. So anything mentioned within `<p>` and `</p>` is treated as a paragraph. A paragraph is a block-level element so a new paragraph always begins on a new line, and browsers naturally put some space before and after a paragraph to make it look neat and easy to read.

## Syntax:
```html
<p> Content </p>
```

## HTML Tag Reference:

### Properties of the `<p>` tag:
- The `<p>` tag automatically adds space before and after any paragraph, which is basically margins added by the browser.
- If a user adds multiple spaces, the browser reduces them to a single space.
- If a user adds multiple lines, the browser reduces them to a single line.
- By default, the display of the Paragraph element is set to “block” which you can change using CSS. This means that if you add another paragraph to the webpage the next paragraph will be inserted in the next line on the webpage.

### Example 1:
```html
<!DOCTYPE html>
<html>
<body>
    <h2>Welcome To IT-Off Topics</h2>
    <!-- Use of <p> tag -->
    <p>A computer science portal for IT-Off Topics.</p>
</body>
</html>
```

### Example 2:
```html
<!DOCTYPE html>
<html>
<body>
    <p>A Computer Science portal for IT-Off Topics.</p>
    <p>It contains well written, well thought articles.</p>
</body>
</html>
```

### Example 3:
```html
<!DOCTYPE html>
<html>
<body>
    <p>
        This paragraph has multiple lines.
        But HTML reduces them to a single line,
        omitting the carriage return we have used.
    </p>
    <p>
        This paragraph has multiple spaces.
        But HTML reduces them all to a single
        space, omitting the extra spaces and line we have used.
    </p>
</body>
</html>
```

### `<br>` tag:
The HTML `<br>` tag element creates a line break, giving you a new line without starting a new paragraph.

### Syntax:
```html
<br>
```

### Example:
```html
<!DOCTYPE html>
<html>
<body>
    <p>
        This paragraph has multiple
        <br />lines. But HTML reduces them
        <br />to a single line, omitting
        <br />the carriage return we have used.
    </p>
</body>
</html>
```

### `<hr>` tag:
The HTML `<hr>` tag is used to create a horizontal rule or line, visually separating content on a webpage.

### Syntax:
```html
<hr>
```

### Example:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Horizontal Rule Example</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>
        IT-Off Topics is a leading
        platform that provides computer
        science resources and coding challenges
    </p>
    <hr>
    <p>
        IT-Off Topics is a leading platform
        that provides computer science resources
        and coding challenges
    </p>
</body>
</html>
```

### `align` attribute:
The `<p>` tag specifically supports the alignment attribute and allows us to align our paragraphs in left, right, or center alignment. 

### Syntax:
```html
<p align="value">
```

### Example:
```html
<!DOCTYPE html>
<html>
<body>
    <p align="center">
        Welcome IT-Off Topics
    </p>
    <p align="left">
        A Computer Science portal for IT-Off Topics.
    </p>
    <p align="right">
        It contains well written, well thought articles.
    </p>
</body>
</html>
```

### `<pre>` tag: 
The HTML `<pre>` tag is used for pre-formatted text. It keeps the original spaces and line breaks exactly as they are in the code.

### Syntax:
```html
<pre> Content </pre> 
```

### Example:
```html
<!DOCTYPE html>
<html>
<body>
    <pre>
    This paragraph has multiple
    lines. But it is displayed 
    as it is unlike the paragraph 
    tag.
    </pre>
    <pre>
    This     paragraph has multiple
    spaces. But     it is displayed 
    as it is    unlike the paragraph 
         tag.
    </pre>
</body>
</html>
