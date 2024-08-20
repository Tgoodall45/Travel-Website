<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel and Tourism Website</title>
    <style>
       /* Reset some default styles */
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
