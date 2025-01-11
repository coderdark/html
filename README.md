# HTML

## Semantic HTML
The semantic elements in html are the following:  `<header>, <nav>, <main>, <article>, <aside>, <section>, <footer>, <details>, <summary>, <figure>, <figcaption>, <mark>, <time>, and <progress>`. Why use semantic html? Semantic html is easier to read and maintain the html in a page, better for screen readers and accessability and better for SEO (searcch engine optimization).

### Resources: 
+ https://cs.fyi/guide/writing-semantic-html
+ https://www.youtube.com/watch?v=bOUhq46fd5g

## Usage
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A sample semantic HTML page following best practices for accessibility and SEO.">
    <title>Semantic HTML Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header with Navigation -->
    <header>
        <h1>My Website</h1>
        <nav aria-label="Main Navigation">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>

        <!-- Hero Section -->
        <section id="hero">
            <h2>Welcome to My Website</h2>
            <p>Your one-stop solution for web development and design.</p>
            <button onclick="location.href='#contact'">Get in Touch</button>
        </section>

        <!-- About Section -->
        <section id="about">
            <h2>About Us</h2>
            <p>We provide high-quality digital solutions to small businesses.</p>
        </section>

        <!-- Services Section -->
        <section id="services">
            <h2>Our Services</h2>
            <article>
                <h3>Web Development</h3>
                <p>We build responsive and accessible websites using modern technologies.</p>
            </article>
            <article>
                <h3>Graphic Design</h3>
                <p>We create stunning visuals and branding materials.</p>
            </article>
        </section>

        <!-- Blog Section -->
        <section id="blog">
            <h2>Latest Blog Posts</h2>
            <article>
                <h3>Understanding Semantic HTML</h3>
                <p>Learn why semantic HTML matters for SEO and accessibility.</p>
                <a href="#">Read More</a>
            </article>
        </section>

        <!-- Sidebar -->
        <aside>
            <h2>Quick Links</h2>
            <ul>
                <li><a href="#">Privacy Policy</a></li>
                <li><a href="#">Terms of Service</a></li>
            </ul>
        </aside>

    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>

</body>
</html>
```
