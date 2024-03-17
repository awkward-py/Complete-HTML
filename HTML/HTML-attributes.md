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

# HTML Attributes Complete Reference

HTML Attributes: HTML attributes are special words placed inside the opening tags used to define the characteristics of an HTML element. Attributes consist of attribute names and their corresponding values, separated by an equal (=) operator. Attribute values are enclosed within double quotes (" ").

The complete list of HTML attributes is given below:

## HTML Attributes:

| Attribute        | Description                                                                                                |
|------------------|------------------------------------------------------------------------------------------------------------|
| accept           | This attribute can be used with `<input>` element only.                                                    |
| accept-charset   | Define character encoding and is used for form submission.                                                 |
| accesskey        | Keyboard shortcuts to activate/focus specific elements.                                                     |
| action           | Specify where the form data is to be sent to the server after submission of the form.                      |
| align            | Specify the alignment of text content of The Element.                                                       |
| alt              | Show or display something if the primary attribute.                                                         |
| async            | Only works for external scripts and used only when src attribute is present.                                |
| autocomplete     | Specify whether the input field has autocompleted would be on or off.                                       |
| autoplay         | The audio/video should automatically start playing when the web page is loaded.                             |
| autofocus        | The element should get focused when the page loads. It is a boolean attribute.                               |
| bgcolor          | Set the background color of an HTML element.                                                                |
| border           | Set visible border width to most HTML elements within the body.                                             |
| charset          | Define character encoding.                                                                                  |
| checked          | Indicate whether an element should be checked when the page loads up. It is a Boolean attribute.            |
| cite             | Specify the URL of the document that explains the quotes, message, or text which describes why the text was inserted. |
| class            | Specifies one or more class names for an HTML element.                                                      |
| cols             | The number of columns a cell should span.                                                                   |
| colspan          | HTML specifies the number of columns a cell should span.                                                    |
| content          | The values that are related to the http-equiv or name attribute.                                            |
| contenteditable  | Specify whether the content present in the element is editable or not.                                      |
| controls         | It is a Boolean attribute and also new in HTML5.                                                            |
| coords           | Specify the coordinate of an area in an image-map.                                                          |
| data             | Specify the URL of the Embedded file of the Object.                                                         |
| data-*           | Specific to HTML5 and you can use the data-* attribute on all HTML elements.                                |
| datetime         | Specify the date and time of the inserted and the deleted text.                                             |
| default          | Specify that the track will be enabled if the user’s preferences do not indicate that another track would be more appropriate. |
| defer            | Executed when the page has finished parsing.                                                               |
| dir              | The text direction of the element content.                                                                  |
| dirname          | Enable the text direction of the input and the Textarea Field after submitting the form.                     |
| disabled         | The disabled attribute in HTML indicates whether the element is disabled or not.                            |
| download         | Download the element when the user clicks on the hyperlink.                                                 |
| draggable        | Specify whether an element is draggable or not.                                                             |
| dropzone         | Specify whether the dragged data is copied, moved, or linked when it is dropped on any element.             |
| enctype          | That data will be present in the form and should be encoded when submitted to the server.                    |
| for              | For Attribute is used in both the `<label>` and the `<output>` element.                                      |
| form             | That the element can contain one or more forms.                                                             |
| formaction       | Specify where to send the data of the form. After submission of the form, the formaction attribute is called. |
| headers          | The HTML headers attribute specifies one or additional header cells a table cell is expounded to.           |
| height           | Height attribute is used to specify the height of the Element.                                              |
| hidden           | The hidden attribute in HTML is used to define the visibility of elements.                                   |
| high             | The range where the value of gauge is considered to be of high value.                                        |
| href             | It is used to specify the URL of the document.                                                              |
| hreflang         | The language for a linked document. It is used only when the href attribute is set.                          |
| http-equiv       | Provide header information or value of the content Attribute.                                               |
| id               | It is used by CSS and JavaScript to perform a certain task for a unique element.                             |
| ismap            | The HTML ismap attribute is a boolean attribute.                                                            |
| kind             | The kind of track. This attribute is only used in `<Track>` element.                                         |
| label            | The title of the Text Track is used by the browser when listing available text tracks.                       |
| lang             | Specify the language of the element content.                                                                |
| list             | List of pre-defined options for an `<input>` element to suggest the user.                                    |
| loop             | Restart the audio and video again and again after finishing it. It contains the Boolean value.               |
| low              | The range where the value of gauge is considered to be low.                                                  |
| max              | Specifies the maximum value of an element.                                                                  |
| maxlength        | The maximum number of characters in the `<input>` element. Its default value is 524288.                      |
| media            | Specify the media or device the coupled document is optimized for.                                           |
| method           | The HTTP method is used to send data while submitting the form.                                              |
| min              | Specify the lower bound of the gauge.                                                                        |
| multiple         | Allowed to select more than one value that is present in an element.                                          |
| muted            | The audio output of the video is muted, it is a Boolean attribute.                                            |
| name             | Specify a name for the element.                                                                              |
| novalidate       | That the form-data should not be validated when submitting the form.                                          |
| onblur           | That moment when the element loses focus.                                                                    |
| oncopy           | The user copied the content present in an element.                                                           |
| oncut            | The user cut or delete the content that has been present in the element.                                      |
| onkeypress       | When a user presses a key on the Keyboard.                                                                   |
| onmousedown      | Order of events occurs related to the onmousedown event.                                                     |
| onscroll         | This onscroll attribute works when an element scrollbar is being scrolled.                                    |
| optimum          | The optimum attribute in HTML indicates the optimal numeric value for the gauge.                             |
| pattern          | Specifies a short hint that describes the expected value of an input field/text area.                        |
| placeholder      | Specifies a short hint that describes the expected value of an input field/text area.                        |
| readonly         | Specify that the text written in input or text area Element is read-only.                                     |
| required         | Specify that the input element must be filled out before submitting the Form.                                 |
| reversed         | Ordered the list in Descending Order(9, 8, 7, 6 …..) instead of ascending order(1, 2, 3 ….)                  |
| rows             | The number of visible text lines for the control i.e the number of rows to display.                           |
| rowspan          | The number of rows a cell should span.                                                                       |
| selected         | Specify which option should be by default selected when the page loads.                                       |
| size             | Specify the initial width for the input field and a number of visible rows for the select element.           |
| spellcheck       | Applied to HTML forms using the spellcheck attribute.                                                         |
| srclang          | Specify the language of the track text.                                                                      |
| start            | The start value for numbering the individual list item.                                                       |
| step             | Set the discrete step size of the `<input>` element.                                                          |
| style            | There are 3 ways of implementing style in HTML.                                                              |
| tabindex         | When the tab button is used for navigating.                                                                  |
| target           | Specify where to open the linked document.                                                                   |
| title            | Specify extra information about the element.                                                                 |
| translate        | Specify whether the content of an element is translated or not.                                               |
| value            | Specify the value of the element with which it is used.                                                       |
| wrap             | Specify in which manner the text is to be wrapped in a text area when a form is submitted.                   |
