# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling Assignment</title>
    <style>
        /* Reset some default browser styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* BODY STYLES */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; /* Different font */
            line-height: 1.6;
            color: #333333;
            background-color: #f5f5f5;
            padding: 20px;
        }

        /* HEADER STYLES */
        header {
            text-align: center;
            margin-bottom: 30px;
            padding: 20px;
            background-color: #4a6fa5;
            border-radius: 8px;
        }

        /* ID SELECTOR */
        #main-title {
            color: white;
            font-size: 2.5rem;
            margin-bottom: 10px;
            font-family: 'Georgia', serif; /* Different font */
        }

        /* CLASS SELECTOR */
        .subtitle {
            color: #e0e0e0;
            font-style: italic;
        }

        /* NAVIGATION STYLES */
        .navigation {
            background-color: #333;
            padding: 10px 0;
            margin-bottom: 20px;
            border-radius: 5px;
        }

        .navigation ul {
            list-style-type: none;
            display: flex;
            justify-content: center;
        }

        .navigation li {
            margin: 0 15px;
        }

        .navigation a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .navigation a:hover {
            color: #4a6fa5;
        }

        /* SECTION STYLES */
        section {
            margin-bottom: 30px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #4a6fa5;
            margin-bottom: 15px;
            border-bottom: 2px solid #4a6fa5;
            padding-bottom: 5px;
        }

        /* IMAGE STYLING */
        .image-container {
            text-align: center;
        }

        .featured-image {
            max-width: 100%;
            height: auto;
            border: 5px solid #4a6fa5; /* Border */
            border-radius: 10px;
            margin: 15px auto; /* Margin */
            padding: 5px; /* Padding */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .featured-image:hover {
            transform: scale(1.03);
        }

        .image-caption {
            font-style: italic;
            color: #666;
            margin-top: 10px;
        }

        /* CONTACT BOX STYLING */
        .contact-box {
            background-color: #e9f0f9;
            padding: 15px;
            border-left: 5px solid #4a6fa5;
            margin: 15px 0;
        }

        /* FOOTER STYLES */
        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: white;
            border-radius: 5px;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1 id="main-title">Welcome to My Styled Page</h1>
        <p class="subtitle">This page demonstrates various CSS styling techniques</p>
    </header>
    
    <nav class="navigation">
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="about">
            <h2>About Section</h2>
            <p>Applying CSS to a HTML page. Style elements using: Classes and IDs. Color and typography. Margins, paddings, and borders.</p>
        </section>
        
        <section id="gallery">
            <h2>Image Gallery</h2>
            <div class="image-container">
                <img src="/api/placeholder/400/300" alt="Sample Image" class="featured-image">
                <p class="image-caption">my assignment</p>
            </div>
        </section>
        
        <section id="contact">
            <h2>Contact Information</h2>
            <div class="contact-box">
                <p>Email: favourrotich.com</p>
                <p>Phone: 0720765541</p>
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2025 week3 Assignment</p>
    </footer>
</body>
</html>



