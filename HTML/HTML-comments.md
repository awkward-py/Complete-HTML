# HTML Comments in GitHub Readme

HTML comments are essential for enhancing code readability and facilitating collaboration among developers. They are annotations or notes added within HTML code that browsers ignore, serving the purpose of providing explanations, reminders, or instructions for fellow developers working on the same project.

## What are HTML Comments?

HTML comments, like comments in other programming languages, are meant to enhance code comprehension and collaboration. They don't affect the appearance of the webpage since browsers do not render them. Instead, they provide additional information within the source code.

## Ways to Comment in HTML

There are two ways to add comments in HTML:

### Single-line Comment

Single-line comments are enclosed within `<!--` and `-->` tags.

```html
<!-- This is a single line comment -->
```

### Multi-line Comment

Multi-line comments are useful for commenting out multiple lines of code.

```html
<!--
    This is a multi-line
    comment
-->
```

## HTML Comments Example

Let's explore examples of both single-line and multi-line comments:

```html
<!DOCTYPE html> 
<html> 
<body> 
    <!-- This is heading Tag -->
    <h1>Awkwardpy</h1> 

    <!-- This is single line comment -->
    <h2>This is <!-- given for --> single line comment</h2> 
</body> 
</html>
```

In this example, neither the heading nor the comment will render in browsers.

```html
<!DOCTYPE html> 
<html> 
<body> 
    <!-- This is heading tag -->
    <h1>Awkwardpy</h1> 

    <!-- This is multi-line comment -->
    <h2>This is multi-line comment</h2> 
</body> 
</html>
```

Similar to the previous example, both the heading and comment are not displayed on browsers.

## Conclusion

Comments in HTML play a crucial role in communicating within your codebase. They are invaluable for collaboration and serve as reminder notes for necessary changes. By not appearing on the frontend, they ensure that the webpage's appearance remains unaffected. Adding comments to your web projects is a recommended practice followed by many developers.

This README covers single-line and multi-line comments, along with examples, and also mentions keyboard shortcuts for adding comments in HTML code.
