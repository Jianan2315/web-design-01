# Jianan's Demo Website

This project is a simple demo website created to showcase various HTML elements and CSS styling. The website displays information about skills, media elements (audio, video, images), and provides contact information via `mailto:` and `tel:` links.

## HTML Tags Used and Their Descriptions

### 1. `<!DOCTYPE html>`
Specifies the document type and version of HTML (HTML5).

### 2. `<html lang="en">`
Defines the root element of the HTML document and specifies the language as English.

### 3. `<head>`
Contains metadata about the webpage such as character encoding, viewport settings, and links to external resources like the favicon and CSS stylesheet.

### 4. `<meta charset="UTF-8">`
Defines the character encoding for the document as UTF-8.

### 5. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
Ensures that the webpage scales properly on different devices, especially mobile devices.

### 6. `<title>`
Specifies the title of the webpage that appears in the browser tab.

### 7. `<link rel="icon" href="rev.ico" type="image/x-icon">`
Links to the favicon of the website.

### 8. `<link rel="stylesheet" href="styles.css">`
Links an external CSS file for styling the webpage.

### 9. `<body>`
Defines the main content of the HTML document.

### 10. `<header>`
Defines the header section of the page, usually containing introductory content or navigation links.

### 11. `<nav>`
Represents a section of navigation links.

### 12. `<menu>`
Contains a list of navigation links or options.

### 13. `<li>`
Defines an individual list item.

### 14. `<a>`
Defines a hyperlink, which can link to different sections within the page or external pages. Special attributes used include:
- `href="#projects"`: Links to a section within the same page.
- `href="mailto:ni.jian@noirtheastern.edu"`: Creates an email link.
- `href="tel:+12345678910"`: Creates a phone number link.

### 15. `<div>`
A container element used for grouping and styling content.

### 16. `<p>`
Defines a paragraph of text.

### 17. `<h1>` to `<h2>`
Headings used for titles or section headings. `<h1>` is the main title, and `<h2>` is used for subheadings.

### 18. `<table>`
Represents tabular data. The `<table>` tag contains child elements:
- `<tr>`: Defines a row within the table.
- `<th>`: Defines a header cell.
- `<td>`: Defines a standard table data cell.

### 19. `<img>`
Embeds images in the webpage. The `src` attribute specifies the image path, and `alt` provides alternative text.

### 20. `<audio>`
Embeds audio content. Includes `controls` and `autoplay` attributes for playback control and automatic start.

### 21. `<video>`
Embeds video content. Includes `controls` to enable playback controls.

### 22. `<button>`
Creates a clickable button. The `onclick` attribute specifies an action when the button is clicked.

### 23. `<form>`
Defines a form that allows the user to submit information via `mailto:`. The form contains:
- `<input type="text">`: Text input field.
- `<input type="email">`: Email input field.
- `<textarea>`: A multi-line text input field.
- `<button type="submit">`: A submit button for the form.

### 24. `<details>`
Creates a collapsible content section that can be expanded or collapsed by the user. It contains:
- `<summary>`: Visible heading for the collapsible content.

### 25. `<footer>`
Defines the footer section of the webpage.

### 26. `<script>`
Contains JavaScript code used to dynamically change the content inside `<summary>` when clicked.

## CSS Used

### 1. `body`
Applies basic styles for the body element including font family, margin, and padding.

### 2. `header, footer`
Styles the header and footer with background color, text color, and alignment.

### 3. `table, th, td`
Defines styles for the table, including border, padding, and layout.

### 4. `img`
Ensures images are responsive by setting their maximum width to 100%.

### 5. `form`
Adds margin to the form for spacing.

### 6. `.container`
Centers the content on the page and sets padding and width.

### 7. `button`
Styles the button with background color, text color, padding, and hover effects.

### 8. `nav, menu, li, a`
Styles the navigation menu and links, including hover effects and text formatting. Links created using `mailto:` and `tel:` have custom colors applied.

### 9. `details p`
Adds margin for paragraphs within `<details>`.

---

This `README.md` provides an overview of the HTML tags and CSS styles used in the demo website.
