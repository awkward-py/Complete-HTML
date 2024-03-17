# HTML Headings

HTML heading tags play an essential role. They not only organize information but also impact search engine rankings. In this article, we’ll learn about the significance of heading tags, their hierarchy, and best practices for optimizing them. The HTML heading tag is used to define the headings of a page.

HTML provides six levels of heading elements, ranging from `<h1>` (highest level) to `<h6>` (lowest level).

## Purpose and Usage of Heading Tags:

1. `<h1>` – Main Heading (Largest):
   - Represents the primary topic of the page.
   - Use it sparingly to maintain clarity.

2. `<h2>` – Subheadings:
   - Ideal for dividing content into sections.
   - If further subsections exist, employ `<h3>` elements.

3. `<h3>` to `<h6>` – Smaller Headings:
   - Gradually decrease in size.
   - Use them for finer subdivisions.

### Syntax:
```
<!-- the 'h' inside the tag should be in small case only. -->
<h1>Heading1</h1>
<h2>Heading2</h2>
...
<h6>Heading6</h6>
```

## Why are Headings Important?

1. **SEO Impact:**
   - Search engines index headings to understand content structure.
   - Well-organized headings enhance visibility and ranking.

2. **Highlighting Key Topics:**
   - Headings emphasize essential information.
   - Readers quickly grasp the document’s structure.

### Example:
This example illustrates the HTML heading tags.

![Screenshot-2023-12-17-130848](screenshot-url)

```html
<!DOCTYPE html>
<html>
  <body>
      <h1>This is heading h1</h1>
      <h2>This is heading h2</h2>
      <h3>This is heading h3</h3>
      <h4>This is heading h4</h4>
      <h5>This is heading h5</h5>
      <h6>This is heading h6</h6>
  </body>
</html>
```

## Customization in HTML Heading Tags
The default size of HTML headings can be changed using the style attribute.

### Example:
This example explains the HTML heading tags by specifying the size of the font.

```html
<!DOCTYPE html>
<html>
<body>
     
    <h1>H1 Heading</h1> 
     
    <!-- With the help of Style attribute you can customize
           the size of the heading, As done below-->
     
    <h1 style="font-size: 50px">H1 with new size.</h1> 
   
    <!-- Here font-size is the property by which  we can 
           modify the heading. Here we kept it 50px i.e. 50 pixels -->
 
</body>
</html>
```

![Styling the tag with different font-size](screenshot-url)

## Supported Browsers: 
- Google Chrome 1
- Microsoft Edge 12
- Firefox 1
- Opera 15
- Safari 4
