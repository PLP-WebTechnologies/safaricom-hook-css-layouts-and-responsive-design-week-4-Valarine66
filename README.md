# Assignment: Responsive Web Design

## Objective:
Create a responsive webpage using modern CSS techniques, specifically Flexbox, Grid, and Media Queries. The goal is to ensure the webpage adapts gracefully to various screen sizes.

## Assignment Tasks

### Designing a Responsive Layout
a. Create a webpage with the following sections:

Header (including a logo and navigation links).
Main content area (with two columns: one for text content and the other for an image).
Footer (with links to social media and a copyright notice).
b. Use Flexbox to style the navigation menu in the header.
c. Use CSS Grid to structure the main content area.

### Creating Media Queries for Responsiveness
a. Implement media queries to ensure the webpage looks good on the following screen sizes:

Small screens (up to 600px): Stack all sections vertically.
Medium screens (601px to 1024px): Keep the header and footer horizontal, but stack the main content columns.
Large screens (above 1024px): Display the layout as designed with Flexbox and Grid.

### Bonus

Add animations or transitions when resizing the screen.



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">MyLogo</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section class="content">
            <div class="text">
                <h1>Welcome to Our Website</h1>
                <p>Our website provides the latest insights and trends in web development, covering topics such as responsive design, accessibility, and performance optimization. Stay ahead with expert tutorials, industry news, and innovative techniques.</p>
            </div>
            <div class="image">
                <img src="https://via.placeholder.com/400" alt="Placeholder Image">
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2025 MyWebsite | Follow us on 
            <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
        </p>
    </footer>
</body>
</html>

