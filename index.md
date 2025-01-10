# HTML CookBook

- [Basics](https://androcado.github.io/cookbook-html)


---


# Table of Contents
- [1. Variables](#1-variables)
- [2. Data Types](#2-data-types)
- [3. Operators](#3-operators)
  - [Arithmetic Operators](#arithmetic-operators)

---


## **1. Basic Structure**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<html>`            | Root element of an HTML document.                 |
| `<head>`            | Container for metadata and links to external resources. |
| `<title>`           | Specifies the title of the document (important for SEO). |
| `<body>`            | 	Contains the content of the HTML document.      |
| `<!DOCTYPE>`        | Declaration to define the HTML version.           |


### Examples:
```html
<!DOCTYPE html>
<html>
<head>
  <title>My Website</title>
</head>
<body>
  <h1>Welcome!</h1>
</body>
</html>
---


---


## **2. Metadata and SEO Tags**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<meta>`            | Provides metadata about the document.             |
| `<link>`            | Links to external resources like stylesheets.     |
| `<script>`          | Embeds or links to JavaScript files.              |
| `<style>`           | Embeds CSS directly in the document.              |


| **Tag**                   | **Description**                                   |
|-------------------------------|---------------------------------------------------|
| `<meta name="description">`   | Provides metadata about the document.             |
| `<meta name="keywords">`      | Links to external resources like stylesheets.     |
| `<meta name="author">`        | Embeds or links to JavaScript files.              |
| `<meta name="robots">`        | Embeds CSS directly in the document.              |
| `<link rel="canonical">`      | Embeds CSS directly in the document.              |


### Examples:
```html
<head>
  <title>SEO Optimized Page</title>
  <meta name="description" content="Learn how to optimize your website for SEO.">
  <meta name="author" content="John Doe">
  <meta name="robots" content="index, follow">
  <link rel="canonical" href="https://example.com/seo-page">
</head>
---


---


## **3. Content Tags**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<h1> to <h6>`      | Headings, with <h1> being the most important (SEO-relevant).            |
| `<p>`               | Defines a paragraph.                              |
| `<br>`              | Inserts a line break.                             |
| `<hr>`              | Inserts a horizontal rule (thematic break).       |
| `<blockquote>`      | Represents a block of quoted text.                |


### Examples:
```html
<h1>Main Heading</h1>
<p>This is a paragraph.</p>
<blockquote>“This is a quote.”</blockquote>
---


---


## **3. Text Formatting**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<strong>`          | Indicates strong importance (renders as bold).    |
| `<em>`              | Indicates emphasized text (renders as italic).    |
| `<b>`               | Renders text in bold (not semantically important). |
| `<i>`               | Renders text in italic (not semantically important). |
| `<mark>`            | Highlights text.                                  |
| `<small>`           | Displays smaller text.                            |
| `<sup>`             | Displays superscript text.                        |
| `<sub>`             | Displays subscript text.                          |


---


## **3. Text Formatting**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<ul>`              | Unordered list.                                   |
| `<ol>`              | Ordered list.                                     |
| `<li>`              | List item.                                        |
| `<dl>`              | Description list.                                 |
| `<dt>`              | Term in a description list.                       |
| `<dd>`              | Description of the term.                          |



### Examples:
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
<dl>
  <dt>HTML</dt>
  <dd>A markup language for creating web pages.</dd>
</dl>
---


---


## **4. Links and Navigation**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<a>`               | Defines a hyperlink.                              |
| `<nav>`             | Defines a section for navigation links.           |




### Examples:
```html
<nav>
  <a href="/home">Home</a>
  <a href="/about">About</a>
</nav>
---


---


## **5. Multimedia**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<img>`             | Embeds an image.                                  |
| `<audio>`           | Embeds audio content.                             |
| `<video>`           | Embeds video content.                             |
| `<source>`          | Specifies multiple media resources.               |

### Examples:
```html
<img src="image.jpg" alt="A descriptive text">
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>
<video controls>
  <source src="video.mp4" type="video/mp4">
</video>
---


---


## **8. Forms**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<form>`            | Defines a form for user input.                    |
| `<input>`           | Defines an input field.                           |
| `<textarea>`        | Defines a multiline text field.                   |
| `<button>`          | Defines a clickable button.                       |
| `<select>`          | Defines a dropdown list.                          |
| `<option>`          | Defines an option in a dropdown list.             |
| `<label>`           | Associates a label with an input element.         |

### Examples:
```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <button type="submit">Submit</button>
</form>
---


---


## **9. Semantic Elements**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<header>`          | Defines a header section.                         |
| `<footer>`          | Defines a footer section.                         |
| `<article>`         | Represents an independent piece of content.       |
| `<section>`         | Defines a section of the document.                |
| `<aside>`           | Represents content tangentially related to the main content. |
| `<main>`            | Represents the dominant content of the document.  |

### Examples:
```html
<header>
  <h1>Welcome to My Site</h1>
</header>
<main>
  <article>
    <h2>Article Title</h2>
    <p>Article content...</p>
  </article>
</main>
<footer>
  <p>&copy; 2025 My Website</p>
</footer>
---


---


## **10. Tables**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<table>`           | Defines a table.                                  |
| `<tr>`              | Defines a table row.                              |
| `<td>`              | Defines a table cell.                             |
| `<th>`              | Defines a table header cell.                      |
| `<thead>`           | Groups the header content.                        |
| `<tbody>`           | Groups the body content.                          |
| `<tfoot>`           | Groups the footer content.                        |

### Examples:
```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>30</td>
    </tr>
  </tbody>
</table>
---


---


## **11. Scripts**

| **Tag**         | **Description**                                   |
|---------------------|---------------------------------------------------|
| `<script>`          | Embeds or links to JavaScript.                    |
| `<noscript>`        | Content to display if JavaScript is disabled.     |



---


## **12. Deprecated Tags**

| **Tag**             | **Replaced By**                                   |
|---------------------|---------------------------------------------------|
| `<b>`               | <strong>                                          |
| `<i>`               | <em>                                              |
| `<font>`            | CSS styles                                        |
| `<center>`          | CSS styles                                        |
