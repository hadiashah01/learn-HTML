# Assignment 01 — HTML Fundamentals

## Objective
The objective of this assignment is to practice **basic HTML concepts**
by creating an HTML document that resembles a GitHub README file.

This assignment focuses on **structure, semantics, and linking**, not styling.

---

## What Was Implemented

The following concepts were used in this assignment:

- HTML document structure
- Headings and paragraphs
- Lists and nested lists
- Anchor tags
- Anchoring to same page sections
- Linking to other files
- Basic formatting tags

---

## HTML Structure Used

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>
  Content goes here
</body>
</html>
```
>[!IMPORTANT]
>```<!DOCTYPE html>``` declares the document as HTML5.

# Elements & Tags

## Paired Tags
```html

<p>Paragraph</p>
<h1>Main Heading</h1>
```

## Self-closing Tags
```html
Copy code
<br />
<hr />
<img />
```

>[!NOTE]
>Self-closing tags do not contain content.

## Lists

### Unordered List
```html
Copy code
<ul>
  <li>Item One</li>
  <li>Item Two</li>
</ul>
```

### Nested List
```html
Copy code
<ul>
  <li>Main Item
    <ul>
      <li>Sub Item</li>
    </ul>
  </li>
</ul>
```

## Anchor Tags
### Same Page Linking

```html
Copy code
<a href="#section-id">Go to Section</a>

<h2 id="section-id">Target Section</h2>
```
### Linking to Another File

```html
Copy code
<a href="about-me.html">About Me</a>
```
>[!IMPORTANT]
>```href``` value must match the target ```id```.

## Development Environment
| Tool |	Usage | 
|--------------|-------------|
| Visual Studio Code | Writing HTML |
| Live Server	| Local testing |
| Web Browser |	Rendering HTML |


## Implementation Reference
HTML file:  
[Assignment-01/index.html](../assignments/assignment-01/index.html)

>[!TIP]
>This document explains what and why.
The actual code demonstrates how.
