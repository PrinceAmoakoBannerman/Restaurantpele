# Project Explanation: Manpele Restaurant Website

## Project Overview
The project is a static website for a restaurant named "Manpele Restaurant." It includes multiple pages such as Home, Menu, About Us, Reservations, Contact, and Gallery. The website is styled using CSS and is designed to provide a user-friendly experience.

---

## File Structure
The project is organized as follows:
- `index.html`: The main homepage of the website.
- `css/style.css`: The stylesheet for the website.
- `pages/`: A folder containing additional pages:
  - `about.html`: About Us page.
  - `contact.html`: Contact page.
  - `gallery.html`: Gallery page.
  - `menu.html`: Menu page.
  - `reservations.html`: Reservations page.

---

## HTML Explanation
### `index.html`
1. **Doctype Declaration**:
   ```html
   <!DOCTYPE html>
   ```
   Declares the document type as HTML5.

2. **HTML Structure**:
   - `<html>`: The root element of the document.
   - `<head>`: Contains metadata and links to external resources.
   - `<body>`: Contains the visible content of the webpage.

3. **Head Section**:
   - `<meta charset="UTF-8">`: Specifies the character encoding.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures the website is responsive.
   - `<title>`: Sets the title of the webpage.
   - `<link rel="stylesheet" href="css/style.css">`: Links the external CSS file.

4. **Header Section**:
   - `<header>`: Contains the website's title and navigation bar.
   - `<h1>`: Displays the restaurant's name.
   - `<nav>`: Contains links to other pages.

5. **Main Section**:
   - `<main>`: Contains the main content of the page.
   - `<h2>`: A welcoming heading.
   - `<p>`: A paragraph describing the restaurant.
   - `<img>`: Displays an image with a width of 40%.

---

## CSS Explanation
### `style.css`
1. **Body Styling**:
   ```css
   body {
       font-family: 'Georgia', serif;
       background-color: red;
       margin: 0;
       padding: 0;
       color: white;
   }
   ```
   - Sets the font, background color, and text color.
   - Removes default margins and paddings.

2. **Header Styling**:
   ```css
   header {
       background-color: #8b0000;
       color: white;
       padding: 20px;
       text-align: center;
   }
   ```
   - Adds a dark red background and centers the text.

3. **Navigation Bar**:
   ```css
   nav {
       display: flex;
       flex-direction: row;
       position: fixed;
       top: 0;
       left: 0;
       width: 100%;
       background-color: #333;
       padding: 10px 0;
       z-index: 1000;
       justify-content: center;
   }
   nav a {
       color: white;
       text-decoration: none;
       margin: 0 15px;
   }
   nav a:hover {
       text-decoration: underline;
   }
   ```
   - Positions the navigation bar at the top in a horizontal layout.
   - Adds hover effects to links.

4. **Main Content**:
   ```css
   main {
       padding: 25px;
       margin-top: 60px;
   }
   ```
   - Adds padding and a top margin to avoid overlap with the fixed navigation bar.

5. **Footer Styling**:
   ```css
   footer {
       background-color: #8b0000;
       color: white;
       text-align: center;
       padding: 12px;
   }
   ```
   - Adds a footer with a dark red background and centered text.

---

## Navigation Bar
The navigation bar is implemented using the `<nav>` tag. It contains links to all the pages of the website. The CSS ensures it is fixed at the top and styled for a clean, modern look.

---

## Responsive Design
The website uses the `<meta name="viewport">` tag to ensure it is responsive. The CSS is designed to adapt to different screen sizes.

---

## Images
The `<img>` tag is used to display images. For example:
```html
<img src="home.jpg" alt="Welcome Image" style="width: 40%; height: auto; margin-top: 20px;">
```
- The `src` attribute specifies the image file.
- The `alt` attribute provides alternative text.
- Inline styles control the size and spacing.

---

## Deployment
The website can be deployed on platforms like Netlify. Since it is a static website, no build command is required. The root directory can be used as the publish directory.

---

## Conclusion
This project demonstrates a simple yet effective static website for a restaurant. It uses HTML and CSS to create a visually appealing and user-friendly design. The structure and styling ensure the website is easy to navigate and responsive.
