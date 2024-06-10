# landing-page-using-HTML-AND-CSS
         HTML
         
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h1>Welcome to Our Landing Page</h1>
        <p>Experience the best services with us.</p>
        <button>Learn More</button>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We provide top-notch services to help you achieve your goals.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="service-box">
            <h3>Service One</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <div class="service-box">
            <h3>Service Two</h3>
            <p>Phasellus nec sem in justo pellentesque facilisis.</p>
        </div>
        <div class="service-box">
            <h3>Service Three</h3>
            <p>Vestibulum ante ipsum primis in faucibus orci luctus.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Your Company. All rights reserved.</p>
    </footer>
</body>
</html>

   CSS

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.2rem;
}

#hero {
    background: #ff6f61;
    color: #fff;
    padding: 100px 20px;
    text-align: center;
}

#hero h1 {
    margin-bottom: 20px;
    font-size: 3rem;
}

#hero p {
    margin-bottom: 20px;
    font-size: 1.5rem;
}

#hero button {
    padding: 15px 30px;
    font-size: 1rem;
    color: #ff6f61;
    background: #fff;
    border: none;
    cursor: pointer;
}

#hero button:hover {
    background: #e9e9e9;
}

section {
    padding: 50px 20px;
    text-align: center;
}

#about {
    background: #fff;
}

#services {
    background: #f4f4f4;
}

#services .service-box {
    background: #fff;
    padding: 20px;
    margin: 20px;
    display: inline-block;
    width: calc(33% - 40px);
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    vertical-align: top;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

@media (max-width: 768px) {
    #services .service-box {
        width: calc(50% - 40px);
    }
}

@media (max-width: 480px) {
    #services .service-box {
        width: calc(100% - 40px);
    }
}


Explanation:
Reset and Base Styles:

Using * to reset margin and padding and set the box-sizing to border-box for all elements.
Setting the body background color to a light gray and default text color and line-height.  

Header:
A dark background with white text.
Navigation menu centered with inline list items.

Hero Section:
A standout background color with large text for the heading and a button The button changes background color when hovered.
About and Services Sections:

Simple padding and centered text.
Services section includes boxes that are inline-block elements, ensuring they stay aligned and evenly spaced. Using a calc() function to manage responsive widths.
Footer:

A fixed footer with a dark background and white text, aligned to the center.
Media Queries:

Adjusting the service boxes' widths based on the screen size for better responsiveness.
This structure ensures clean and well-aligned elements, proper padding, a cohesive color palette, and a responsive design.






