# Mr.-Ahmad-Elbasha-
Mr.Ahmad elbasha science for all stages
Made by Sedyka Mansour Elbatran 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mr. Ahmad El Basha - Educational Website</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #0056b3;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            margin: 0.5rem 0;
        }

        nav {
            background-color: #333;
        }

        nav ul {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            flex: 1;
            text-align: center;
        }

        nav ul li a {
            display: block;
            color: white;
            text-decoration: none;
            padding: 1rem;
        }

        nav ul li a:hover {
            background-color: #0056b3;
        }

        main {
            padding: 1rem;
        }

        main section {
            margin-bottom: 2rem;
        }

        main h2 {
            border-bottom: 2px solid #0056b3;
            padding-bottom: 0.5rem;
        }

        .video-container {
            display: flex;
            justify-content: center;
            margin-top: 1rem;
        }

        .video-container iframe {
            width: 80%;
            height: 400px;
            border: none;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Mr. Ahmad El Basha</h1>
            <p>Interactive Science Lessons for All Preparatory and Secondary Stages</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#first-prep">First Prep</a></li>
            <li><a href="#second-prep">Second Prep</a></li>
            <li><a href="#third-prep">Third Prep</a></li>
            <li><a href="#first-secondary">First Secondary</a></li>
        </ul>
    </nav>

    <main>
        <!-- First Prep Section -->
        <section id="first-prep">
            <h2>First Prep</h2>
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/videoseries?list=PL9G2b37WxBAJAGuIIozfiEGskRAzqUmz1" title="First Prep Playlist" allowfullscreen></iframe>
            </div>
        </section>

        <!-- Second Prep Section -->
        <section id="second-prep">
            <h2>Second Prep</h2>
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/LDqqrKPJI4w" title="Oscillatory Motion - Second Prep" allowfullscreen></iframe>
            </div>
        </section>

        <!-- Third Prep Section -->
        <section id="third-prep">
            <h2>Third Prep</h2>
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/videoseries?list=PL9G2b37WxBALhoERfgtFgve8xBTrUM04l" title="Third Prep Playlist" allowfullscreen></iframe>
            </div>
        </section>

        <!-- First Secondary Section -->
        <section id="first-secondary">
            <h2>First Secondary</h2>
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/jehCayKxqJ4" title="Full Mark Tips - First Secondary" allowfullscreen></iframe>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2024 Mr. Ahmad El Basha | Educational Content for Everyone</p>
    </footer>
</body>
</html>
