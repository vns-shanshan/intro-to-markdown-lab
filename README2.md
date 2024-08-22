# HTML Boilerplate

![HTML code with a laptop](https://images.unsplash.com/photo-1656827992336-f8e520486515?q=80&w=1326&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

This guide provides the essential structure of a basic HTML document, often referred to as an HTML boilerplate. The boilerplate serves as a starting point for creating any HTML page.

### 1. Basic HTML Boilerplate
Here is the minimal HTML structure:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Link to CSS file -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Main content goes here -->
    <h1>Hello, World!</h1>

    <!-- Link to JavaScript file -->
    <script defer src="script.js"></script>
</body>
</html>
```

##### Explanation of the HTML Boilerplate
- `<!DOCTYPE html>`: Declares the document type and version of HTML.
- `<html lang="en">`: The root element of the HTML document, with the lang attribute specifying the language.
- `<head>`: Contains meta-information about the document, such as character set, viewport settings, and the document's title.
    - `<meta charset="UTF-8">`: Sets the character encoding to UTF-8, which supports most characters from all languages.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures proper scaling on different devices by setting the viewport width.
    - `<title>Document</title>`: Defines the title of the document, which appears in the browser's title bar or tab.
    - `<link rel="stylesheet" href="styles.css">`: Links to an external CSS file for styling the document.
- `<body>`: Contains the visible content of the document.
    - `<h1>Hello, World!</h1>`: An example of a heading element within the body.
    - `<script defer src="script.js"></script>`: Links to an external JavaScript file that adds interactivity to the document.
        > - *defer* : If the defer attribute is set, it specifies that the script is downloaded in parallel to parsing the page, and executed after the page has finished parsing.
### 2. Usage
You can copy and paste this HTML boilerplate into your new HTML files as a starting point for your projects. Customize the **title**, **styles**, and **scripts** to suit your specific needs.

For more information on HTML Boilerplate, check out the [MDN docs: HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics).