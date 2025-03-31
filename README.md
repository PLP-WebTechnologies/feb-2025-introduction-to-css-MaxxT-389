# Introduction to CSS

#HTML FILE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Webpage</title>
    <link rel="stylesheet" href="style.css"> <!-- Link to the external CSS file -->
</head>
<body>

    <header class="header">
        <h1>Welcome to My Stylish Webpage</h1>
    </header>

    <section class="content">
        <h2>About Us</h2>
        <p>This is a simple webpage demonstrating CSS styling with external files. We will style fonts, add padding, margins, borders, and style images.</p>
    </section>

    <section id="image-section">
        <h2>Our Image</h2>
        <img src="https://via.placeholder.com/400" alt="Placeholder Image" class="styled-image">
    </section>

    <footer>
        <p>Contact us at: <a href="mailto:contact@example.com">contact@example.com</a></p>
    </footer>

</body>
</html>


#CSS FILE

body {
    font-family: 'Arial', sans-serif; /* Default font */
    background-color: #f4f4f4; /* Light grey background */
    color: #333; /* Dark grey text */
    margin: 0;
    padding: 0;
}

.header {
    background-color: #4CAF50; /* Green background */
    color: white;
    padding: 20px;
    text-align: center;
}

.content {
    padding: 20px;
    margin: 20px;
    background-color: #ffffff; /* White background */
    border: 1px solid #ddd; /* Light grey border */
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
}

#image-section {
    margin-top: 30px;
    padding: 15px;
    background-color: #e0e0e0; /* Light grey background */
    text-align: center;
}

.styled-image {
    width: 100%; /* Make the image responsive */
    max-width: 400px; /* Maximum width */
    border: 5px solid #ddd; /* Light border around the image */
    padding: 5px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}

a {
    color: #4CAF50; /* Green color for links */
    text-decoration: none;
}

a:hover {
    text-decoration: underline; /* Underline on hover */
}
