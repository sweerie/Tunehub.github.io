
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Music Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to tunehub</h1>
    </header>

    <main>
        <section class="music-player">
            <h2>Now Playing</h2>
            <audio controls>
                <source src="your-music-file.mp3" type="audio/mp3">
                Your browser does not support the audio element.
            </audio>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Your Name</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

h1 {
    font-size: 2.5em;
}

.music-player {
    text-align: center;
    padding: 50px;
}

audio {
    width: 100%;
    max-width: 600px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: #fff;
}

console.log('Welcome to the music website!');

<audio controls>
    <source src="music/your-song.mp3" type="audio/mp3">
    Your browser does not support the audio element.
</audio>

git add .
git commit -m "Initial commit for music website"
git push origin main

<iframe src="https://open.spotify.com/embed/track/your-track-id" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>

music-website/
│
├── index.html
├── style.css
├── script.js
├── your-music-file.mp3
└── README.md (optional)
