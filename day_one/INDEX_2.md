### **General Structure**
1. **`<!DOCTYPE html>`**  
   Declares the document type as HTML5. Essential for defining the version of HTML used.

2. **`<html>` Tag**  
   The root element that encapsulates all content on the page.

3. **`<head>` Tag**  
   Contains metadata about the document, such as the title, character set, and links to styles or scripts.

4. **`<title>` Tag**  
   Specifies the title of the document displayed in the browser tab. In this example, it is `"My page"`.

5. **`<body>` Tag**  
   Encloses all the visible content of the page.

---

### **Comments**
- Content within `<!-- -->` is a comment and is ignored by the browser. It is often used for explanations or temporary disabling of code.

---

### **Content Breakdown**
#### **Paragraph**
- `<p>`  
  Represents a block of text. This example uses inline styling for a span:
  - `<span style="color: brown;">`: Changes the text color to brown.

#### **Ordered List (`<ol>`)**  
- Displays items in a numbered list.  
- Example items: `One`, `Two`, `Three`, etc.

#### **Unordered List (`<ul>`)**  
- Displays items as a bullet-point list.

---

### **Buttons and Input Elements**
1. **`<button>`**  
   A clickable button, often used for user interactions.

2. **`<input>`**  
   Represents form controls. Examples shown include:  
   - Checkbox (`type="checkbox"`)  
   - Date picker (`type="date"`)  
   - Color picker (`type="color"`)  

---

### **Image (`<img>`)**  
- Displays an image. Attributes:  
  - `src`: Specifies the URL of the image.  
  - `alt`: Alternative text for accessibility.  
  - `width` and `height`: Dimensions of the image.  
  Example: A bird image with a width and height of 200px.

---

### **Textarea**
- `<textarea>`  
  Allows users to input multi-line text.

---

### **Select & Option**
1. **`<select>`**  
   Creates a dropdown menu with options to choose from.  
   Example options: `Year One`, `Year Two`, etc.

2. **`<form>`**  
   Groups input fields, dropdown menus, text areas, and buttons together to submit user data.

---

### **Table**
1. **`<table>`**  
   Represents tabular data.  
   - **`<thead>`**: Defines the table header.  
   - **`<tbody>`**: Defines the table body.  
   - **`<tr>`**: Represents a row in the table.  
   - **`<th>`**: Header cell with bold text.  
   - **`<td>`**: Standard table data cell.  
   - Inline styling is used to apply borders.

Example: A 6-column table with a single row containing repeated values of `1`.

---

### **Comments**
- Example comment: `"<!-- Leave a comment here -->"`. Used for notes or reminders.
