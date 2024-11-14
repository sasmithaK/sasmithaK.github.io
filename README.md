# sasmithaK.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nature's Wonders</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: #2b2b2b;
        }

        /* Header */
        header {
            background: url('https://source.unsplash.com/1600x900/?nature,landscape') no-repeat center center/cover;
            color: white;
            padding: 80px 0;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }

        nav a {
            text-decoration: none;
            color: #2b2b2b;
            font-weight: bold;
            padding: 5px 15px;
            border: 1px solid #2b2b2b;
            border-radius: 5px;
        }

        nav a:hover {
            background-color: #2b2b2b;
            color: white;
        }

        /* Main Content */
        section {
            padding: 40px 20px;
            text-align: center;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #2b7a78;
        }

        section p {
            font-size: 1rem;
            line-height: 1.6;
            max-width: 600px;
            margin: 0 auto 20px;
        }

        /* Image Gallery */
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .gallery img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.1);
        }

        /* Footer */
        footer {
            background-color: #2b7a78;
            color: white;
            padding: 20px;
            text-align: center;
        }

        footer p {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Nature's Wonders</h1>
        <p>Explore the beauty of the natural world</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Nature's Wonders</h2>
        <p>Nature's Wonders is dedicated to showcasing the stunning landscapes, vibrant wildlife, and serene environments found around the world. Join us in celebrating the beauty of nature and the importance of preserving it for future generations.</p>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery">
            <img src="https://source.unsplash.com/random/300x200/?forest" alt="Forest">
            <img src="https://source.unsplash.com/random/300x200/?mountain" alt="Mountain">
            <img src="https://source.unsplash.com/random/300x200/?ocean" alt="Ocean">
            <img src="https://source.unsplash.com/random/300x200/?desert" alt="Desert">
            <img src="https://source.unsplash.com/random/300x200/?wildlife" alt="Wildlife">
            <img src="https://source.unsplash.com/random/300x200/?river" alt="River">
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you would like to learn more about our work or get involved, please reach out to us at <a href="mailto:nature@wonders.com">nature@wonders.com</a>.</p>
    </section>

    <footer>
        <p>&copy; 2024 Nature's Wonders | All rights reserved.</p>
    </footer>

    <script>
        document.addEventListener("DOMContentLoaded", function () {
            const header = document.querySelector("header p");
            const hour = new Date().getHours();
            let greeting;

            if (hour < 12) {
                greeting = "Good Morning! Explore the beauty of nature!";
            } else if (hour < 18) {
                greeting = "Good Afternoon! Enjoy nature's wonders!";
            } else {
                greeting = "Good Evening! Discover nature at night!";
            }

            header.textContent = greeting;
        });
    </script>
</body>
</html>

