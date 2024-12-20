# HTML Basics Guide  
Author: Sai Immani  

## Introduction  
This document provides a concise overview of HTML basics, covering essential building blocks, structures, and elements necessary for creating and understanding HTML.  

---

## Table of Contents  
1. **Building Blocks of HTML**  
2. **Structure of HTML**  
3. **Text Formatting**  
4. **Creating Lists**  
5. **Hyperlinks in HTML**  
6. **HTML Form Elements**  
7. **HTML Media Elements**  
8. **HTML Page Layout**  
   - Semantic Elements  
   - Non-Semantic Elements  
9. **Understanding Block and Inline Elements**  
10. **Class and ID Attributes**  
11. **Additional Resources**  

---

## 1. Building Blocks of HTML  
HTML is the foundation of web development and includes elements such as:  
- Tags  
- Attributes  
- Content  

### Example: Basic HTML Structure  
```html  
<!DOCTYPE html>  
<html>  
<head>  
  <title>Page Title</title>  
</head>  
<body>  
  <h1>Welcome to HTML Basics</h1>  
</body>  
</html>  
```  

---

## 2. Structure of HTML  
The structure of an HTML page includes:  
- **Doctype Declaration** (`<!DOCTYPE html>`)  
- **Head Section**: Metadata, styles, and scripts.  
- **Body Section**: Visible content like text, images, and links.  

---

## 3. Text Formatting  
HTML provides tags for formatting text:  
- `<b>` (Bold), `<i>` (Italic), `<u>` (Underline)  
- `<h1>` to `<h6>` (Headings)  
- `<p>` (Paragraph), `<br>` (Line Break)  

---

## 4. Creating Lists  
### Ordered List  
```html  
<ol>  
  <li>Item 1</li>  
  <li>Item 2</li>  
</ol>  
```  

### Unordered List  
```html  
<ul>  
  <li>Item A</li>  
  <li>Item B</li>  
</ul>  
```  

---

## 5. Hyperlinks in HTML  
```html  
<a href="https://example.com">Visit Example</a>  
```  

---

## 6. HTML Form Elements  
### Common Tags:  
- `<form>`: Container for form inputs.  
- `<input>`: Collect user data.  
- `<label>`: Label for inputs.  
- `<textarea>`: Multi-line text input.  
- `<button>`: Action buttons.  
- `<select>`: Dropdown menus.  

### Example:  
```html  
<form>  
  <label for="name">Name:</label>  
  <input type="text" id="name" name="name">  
  <textarea name="message">Enter your message here...</textarea>  
  <button type="submit">Submit</button>  
</form>  
```  

---

## 7. HTML Media Elements  
### Images  
```html  
<img src="image.jpg" alt="Description">  
```  
### Audio  
```html  
<audio controls>  
  <source src="audio.mp3" type="audio/mpeg">  
</audio>  
```  
### Video  
```html  
<video controls>  
  <source src="video.mp4" type="video/mp4">  
</video>  
```  
### YouTube Embed  
```html  
<iframe width="560" height="315" src="https://www.youtube.com/embed/your_video_id" frameborder="0" allowfullscreen></iframe>  
```  

---

## 8. HTML Page Layout  
### Semantic Elements  
- **Header**: `<header>`  
- **Navigation**: `<nav>`  
- **Main Content**: `<main>`  
- **Section**: `<section>`  
- **Aside**: `<aside>`  
- **Article**: `<article>`  
- **Footer**: `<footer>`  

### Non-Semantic Elements  
- `<div>`: General-purpose container.  
- `<span>`: Inline container.  

---

## 9. Understanding Block and Inline Elements  
- **Block Elements**: Occupy full width (e.g., `<div>`, `<p>`, `<section>`)  
- **Inline Elements**: Occupy only the width of their content (e.g., `<span>`, `<a>`)  

---

## 10. Class and ID Attributes  
- **Class**: Used for grouping multiple elements.  
- **ID**: Used for identifying a unique element.  

### Example:  
```html  
<div class="container">  
  <p id="unique">Hello, world!</p>  
</div>  
```  

---

## 11. Additional Resources  
- [GeeksforGeeks HTML Tutorials](https://www.geeksforgeeks.org/)  
- [W3Schools HTML Guide](https://www.w3schools.com/)  

---

## Notes  
For more advanced understanding, refer to the above websites for detailed tutorials and examples. Happy coding!
