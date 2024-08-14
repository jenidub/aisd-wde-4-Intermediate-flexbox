
# WDE04 Intermediate Flexbox

![Screenshot of the project](assets/images/example.png)

## Description
This assignment will cover how to create a responsive website using Flexbox. You will build a simple webpage that includes a navigation bar, a main section, and a footer. The website will be responsive, meaning it will look good on devices of all sizes.

## Project Structure

```
responsive_flexbox_website
│   index.html
│   style.css
```

## Steps

### Step 1: Create the Project Structure

1. Create a new folder for your project.
2. Inside the folder, create two files: `index.html` and `style.css`.

### Step 2: Set Up the HTML

Add the HTML boilerplate:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Flexbox Website</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>
```

**Explanation:**
- `<!DOCTYPE html>` declares the document type and version of HTML.
- The `<html lang="en">` tag defines the language of the document as English.
- `<meta charset="UTF-8" />` sets the character encoding to UTF-8, which supports most characters from various languages.
- The `<meta name="viewport" content="width=device-width, initial-scale=1.0" />` tag ensures the website is responsive by setting the viewport to the width of the device and scaling the content accordingly.
- The `<title>` tag sets the title of the webpage, which appears in the browser tab.
- The `<link rel="stylesheet" href="style.css" />` tag links the external CSS file (`style.css`) to the HTML document for styling.

#### Add the Navigation Bar

In `index.html`, within the `<body>` tag, add the following code for the navigation bar:

```html
<header>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>
```

**Explanation:**
- The `<header>` tag defines the header of the webpage, which typically contains the navigation menu.
- `<nav>` defines a navigation section and contains the `<ul>` (unordered list) element.
- The `<ul>` element holds a list of links, each contained within an `<li>` (list item) element.
- `<a href="#">Home</a>` is a hyperlink that, when clicked, will take the user to the specified URL. The `href="#"` attribute is a placeholder link.

#### Add the Main Section

In `index.html`, below the navigation bar code after the `</header>` tag, add the following code for the main section:

```html
<main>
  <section class="hero">
    <h1>Welcome to Our Website</h1>
    <p>This is a responsive website using Flexbox.</p>
  </section>
  <section class="content">
    <div class="box">Content Box 1</div>
    <div class="box">Content Box 2</div>
    <div class="box">Content Box 3</div>
    <div class="box">Content Box 4</div>
    <div class="box">Content Box 5</div>
    <div class="box">Content Box 6</div>
  </section>
</main>
```

**Explanation:**
- The `<main>` tag defines the main content area of the webpage. It contains two sections: the hero section and the content section.
- `<section class="hero">` defines a section with a class of "hero", used for the introductory content.
- `<h1>Welcome to Our Website</h1>` is a top-level heading that serves as the main title of the hero section.
- `<p>This is a responsive website using Flexbox.</p>` is a paragraph providing a brief description.
- `<section class="content">` defines a section with a class of "content", which will hold the individual content boxes.
- `<div class="box">Content Box 1</div>` represents a content box. The `div` element is a block-level container, and the `class="box"` applies the CSS styles associated with the "box" class.

#### Add the Footer

In `index.html`, below the main section code after the `</main>` tag, add the following code for the footer:

```html
<footer>
  <p>&copy; 2024 Your Website</p>
</footer>
```

**Explanation:**
- The `<footer>` tag defines the footer of the webpage, which typically contains copyright information or additional links.
- `<p>&copy; 2024 Your Website</p>` is a paragraph that displays the copyright symbol and the year.
