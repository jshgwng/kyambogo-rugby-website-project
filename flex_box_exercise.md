### **Flexbox Navigation Exercise**  

#### **Objective:**  
Build a responsive **navigation bar** using **CSS Flexbox**. This exercise will help you understand how to align elements dynamically with Flexbox.  

---  

## **Step 1: Create the HTML File**  
1. Create a new file called **`index.html`**.  
2. Add the basic HTML structure:  

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Navigation</title>
</head>
<body>

</body>
</html>
```  

---  

## **Step 2: Add the Navigation Structure**  
Inside the `<body>` tags, add the following navigation menu:  

```html
<nav class="nav">
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
</nav>
```  

---  

## **Step 3: Add Basic CSS**  
Inside the `<head>` section, add **style** tags and include the following CSS:  

```html
<style>
    /* Remove default margin */
    body {
        margin: 0;
    }

    /* Basic styling for navigation */
    .nav {
        background-color: #333;
        padding: 20px;
    }

    /* Style the links */
    .nav a {
        color: white;
        text-decoration: none;
        padding: 10px;
    }
</style>
```  

---  

## **Step 4: Add Flexbox Properties**  
Modify the `.nav` class to **enable Flexbox** and align the navigation items properly:  

```css
.nav {
    background-color: #333;
    padding: 20px;
    display: flex;              /* Enable Flexbox */
    justify-content: space-around; /* Space items evenly */
}
```  

---  

## **Step 5: Enhance the Design (Optional)**  
Add **hover effects** and improve the link appearance:  

```css
.nav a {
    color: white;
    text-decoration: none;
    padding: 10px 20px; /* Increased padding */
    border-radius: 5px; /* Rounded corners */
}

.nav a:hover {
    background-color: #555;
}
```  

---  

## **Final Complete Code**  

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Navigation</title>
    <style>
        body {
            margin: 0;
        }

        .nav {
            background-color: #333;
            padding: 20px;
            display: flex;
            justify-content: space-around;
        }

        .nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
        }

        .nav a:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <nav class="nav">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>
</body>
</html>
```  

---  

## **Experiment with These Modifications:**  

🔹 **Try different `justify-content` values:**  
Modify `.nav` to see how Flexbox changes the alignment:  

```css
justify-content: flex-start;    /* Align items to the start */
justify-content: center;        /* Center items */
justify-content: space-between; /* Equal space between items */
justify-content: space-around;  /* Equal space around items */
```  

🔹 **Try different background colors:**  
Change `.nav`'s background color:  

```css
background-color: #2196F3;  /* Blue */
background-color: #4CAF50;  /* Green */
background-color: #f44336;  /* Red */
```  

🔹 **Make the navigation bar responsive:**  
Modify `.nav` to **stack items vertically** on smaller screens:  

```css
@media (max-width: 600px) {
    .nav {
        flex-direction: column;
        align-items: center;
    }
    .nav a {
        margin: 5px 0;
    }
}
```  
