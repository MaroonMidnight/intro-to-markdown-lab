![A computer with html code on the screen sitting on a grey desk near a window with green potted plants to the side of it](https://images.unsplash.com/photo-1555099962-4199c345e5dd?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
# Making an HTML Boilerplate

Making a boilerplate for an HTML document is important for formating and making a structure that you can build onto for web pages.
Firsty, we should make a Document Type Declaration.

1. ## Document Type Declaration
```HTML
<!DOCTYPE html>
```
+  **What does it do?**:
This tells the browser that this is an *HTML5 document* so it knows what to render.

2. ## Root Element
```html
<html lang="en">
    <!-- This makes sure that everything you type will be understood in English and will execute it as HTML.
 -->
</html>
```

3. ## Head Section
```html
<html>
<!-- This contains *meta-information* about the document and includes links to stylesheets and scripts.
 -->
</html>
```

  **Common Elements**
 ```html 
<meta charset="UTF-8">  <!-- Defines the character encoding -->
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Ensures the page is responsive and scales correctly on different screens -->
<title> <!-- Sets the title of the page, which appears in the browser tab.-->
<link> <!-- Links to external CSS files. -->
<style> <!-- Contains internal CSS for styling the page -->

```
4. ## Body Section
```html
<body>
    <!-- This is where most HTML is written that shows up on your web page like text,links,images and much much more -->
</body>
```

**Common Elements**
```html
<header>
    <!-- Used for the top of the web page -->
</header>

<main>
    <!-- The main content on the page -->
</main>

<footer>
    <!-- The bottom of the page the contains additional info -->
</footer>
```

5. ## Script Section
```html
<script>
    <!-- Includes Javascript code or links to external Javascript files -->
</script>
```

## Basic Example of an HTML boilerplate
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <script src="index.js"></script>
  </body>
</html>
```

For more information on HTML boiler plates check out the [MDN docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started).