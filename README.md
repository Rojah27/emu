<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Multimedia Blog</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Multimedia Blog</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#gallery">Gallery</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Latest Blog Post</h2>
            <p>Welcome to my blog where I share multimedia content...</p>
        </section>
        <section id="gallery">
            <h2>Gallery</h2>
            <img src="image.jpg" alt="Sample Image">
            <video controls>
                <source src="video.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <audio controls>
                <source src="audio.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </section>
    </main>
    <footer>
        <p>© 2024 My Multimedia Blog</p>
    </footer>
</body>
</html>



body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}
header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}
nav a {
    color: white;
    margin: 0 1rem;
    text-decoration: none;
}
main {
    padding: 2rem;
}
section {
    margin-bottom: 2rem;
}
footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 1rem 0;
}