<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel and Tourism Website</title>
    <link href="https://fonts.googleapis.com/css2?family=Vollkorn:ital,wght@0,400;0,700;1,400;1,700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Vollkorn', serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: #333;
            overflow-x: hidden;
        }

        header {
            background-color: #3b5998;
            color: white;
            padding: 20px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ff7e5f;
        }

        section {
            height: 100vh;
            padding: 80px 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            transition: background 0.3s;
        }

        section:nth-child(odd) {
            background: rgba(255, 255, 255, 0.8);
        }

        section:nth-child(even) {
            background: rgba(255, 255, 255, 0.9);
        }

        h1, h2 {
            margin-bottom: 20px;
        }

        h1 {
            font-size: 2.5em;
        }

        h2 {
            font-size: 2em;
        }

        .content {
            max-width: 600px;
            text-align: center;
        }

        footer {
            background-color: #3b5998;
            color: white;
            text-align: center;
            padding: 10px 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to our Travel and Tourism Website</h1>
        <nav>
            <ul>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#travel-guides">Travel Guides</a></li>
                <li><a href="#travel-blog">Travel Blog</a></li>
                <li><a href="#travel-packages">Travel Packages</a></li>
                <li><a href="#reviews">Reviews</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
   
   <section id="destinations">
    <h2>Destinations</h2>
    <div class="content">
        <!-• Add destination information and pictures here -->
        <p>Explore the world's most beautiful destinations. Discover unique cultures, breathtaking landscapes, and unforgettable experiences.</p>
        <img src="destination.jpg" alt="Beautiful Destination" style="max-width: 100%; height: auto;">
    </div>
</section>

<section id="travel-guides">
    <h2>Travel Guides</h2>
    <div class="content">
        <!-• Add travel guides and pictures here -->
        <p>Find comprehensive travel guides for your next adventure. Plan your trip with helpful tips and insights.</p>
        <img src="guide.jpg" alt="Travel Guide" style="max-width: 100%; height: auto;">
    </div>
</section>

<section id="travel-blog">
    <h2>Travel Blog</h2>
    <div class="content">
        <p>Read our latest travel stories and tips to inspire your next journey. Join our community of travelers.</p>
        <img src="blog.jpg" alt="Travel Blog" style="max-width: 100%; height: auto;">
    </div>
</section>

<section id="travel-packages">
    <h2>Travel Packages</h2>
    <div class="content">
        <p>Discover our exclusive travel packages tailored to your needs. Whether you're looking for a romantic getaway or a family vacation, we've got you covered!</p>
        <ul>
            <li>Beach Escapes</li>
            <li>Adventure Trips</li>
            <li>Cultural Tours</li>
        </ul>
    </div>
</section>

<section id="reviews">
    <h2>Reviews</h2>
    <div class="content">
        <p>See what our customers are saying about their experiences with us. Your feedback is important!</p>
        <blockquote>"An unforgettable journey! Highly recommend!" • Sarah J.</blockquote>
        <blockquote>"Amazing service and beautiful destinations!" • Mike T.</blockquote>
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <div class="content">
        <p>If you have any questions or need assistance, feel free to reach out to us!</p>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <br>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <br>
            <input type="submit" value="Send Message">
        </form>
    </div>
</section>
