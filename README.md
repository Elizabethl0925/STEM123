<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
        }
        nav a {
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            background: #555;
        }
        .gallery-container {
            max-width: 900px;
            margin: 20px auto;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
        }
        .gallery-container img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.15);
        }
        footer {
            text-align: center;
            padding: 12px;
            background: #333;
            color: white;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>Gallery</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About Us</a>
    <a href="projects.html">Projects</a>
    <a href="gallery.html">Gallery</a>
    <a href="contact.html">Contact Us</a>
</nav>

<div class="gallery-container">
    <!-- Replace these src="imageX.jpg" with your real image files -->
    <img src="image1.jpg" alt="Gallery Image">
    <img src="image2.jpg" alt="Gallery Image">
    <img src="image3.jpg" alt="Gallery Image">
    <img src="image4.jpg" alt="Gallery Image">
    <img src="image5.jpg" alt="Gallery Image">
    <img src="image6.jpg" alt="Gallery Image">
    <img src="image7.jpg" alt="Gallery Image">
    <img src="image8.jpg" alt="Gallery Image">
    <img src="image9.jpg" alt="Gallery Image">
</div>

<footer>
    &copy; 2026 Your Name or Website Title
</footer>

</body>
</html>
