<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel and Tourism Website</title>
    <style>
        /* Global Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
    text-align: center;
}

nav li {
    display: inline;
    margin-right: 10px;
}

nav a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
}

form {
    margin-bottom: 20px;
}

label {
    font-weight: bold;
}

input[type='text'], input[type='file'], textarea {
    width: 100%;
    padding: 5px;
    margin-bottom: 10px;
}

input[type='submit'] {
    background-color: #333;
    color: #fff;
    padding: 5px 10px;
    border: none;
    cursor: pointer;
}

#destination-list {
    display: flex;
    flex-wrap: wrap;
}

.destination-card {
    width: 30%;
    margin: 10px;
    padding: 10px;
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.destination-card img {
    width: 100%;
    border-radius: 5px;
}

.destination-card h3 {
    margin-top: 10px;
}

/* Responsive Design */
@media screen and (max-width: 768px) {
    #destination-list {
        flex-direction: column;
    }

    .destination-card {
        width: 100%;
    }
}
    </style>
</head>
<body>
    <header>
        <h1>Welcome to our Travel and Tourism Website</h1>
        <!-• Navigation links -->
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
        
        <!-• Add form for users to input destination information -->
        <form>
            <label for="destination-name">Destination Name:</label>
            <input type="text" id="destination-name" name="destination-name"><br><br>
            
            <label for="destination-image">Destination Image:</label>
            <input type="file" id="destination-image" name="destination-image"><br><br>
            
            <label for="destination-description">Destination Description:</label><br>
            <textarea id="destination-description" name="destination-description" rows="4" cols="50"></textarea><br><br>
            
            <input type="submit" value="Add Destination">
        </form>
        
        <!-• Display added destinations here -->
        <div id="destination-list">
            <!-• Destination cards will be dynamically added here -->
        </div>
    </section>
    
    <!-• Other sections (Travel Guides, Travel Blog, etc.) -->
    
    <footer id="contact">
        <h2>Contact Us</h2>
        <!-• Add contact information and form here -->
    </footer>
</body>
</html>
        <h2>Contact Us</h2>
        <!-• Add contact information and form here -->
    </footer>
</body>
</html>
