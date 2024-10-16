<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Alles over TikTok - trending video's, creators en meer!">
    <title>Welkom bij TikTok Fansite</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>TikTok Fansite</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#popular-videos">Populaire Video's</a></li>
                <li><a href="#about">Over TikTok</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Ontdek de wereld van TikTok</h2>
        <p>TikTok is dé plek voor creatieve content, memes en video's. Volg je favoriete creators en ontdek nieuwe trends!</p>
        <button onclick="scrollToSection('about')">Lees Meer</button>
    </section>

    <section id="popular-videos">
        <h2>Populaire Video's</h2>
        <div class="video-gallery">
            <div class="video-card">
                <iframe width="300" height="200" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Populaire TikTok Video"></iframe>
                <p>#Trend1</p>
            </div>
            <div class="video-card">
                <iframe width="300" height="200" src="https://www.youtube.com/embed/xyz" title="Populaire TikTok Video"></iframe>
                <p>#Trend2</p>
            </div>
            <div class="video-card">
                <iframe width="300" height="200" src="https://www.youtube.com/embed/abc" title="Populaire TikTok Video"></iframe>
                <p>#Trend3</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>Over TikTok</h2>
        <p>TikTok is een sociaal platform waarmee gebruikers korte video's kunnen maken, bewerken en delen. Met een breed scala aan functies en muziek is het een van de snelst groeiende sociale netwerken ter wereld.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <form id="contact-form">
            <label for="name">Naam:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Bericht:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Verstuur</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 TikTok Fansite</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
Stap 2: CSS (stijl van de website)
css
Code kopiëren
/* style.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #25d366;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background: url('tiktok-background.jpg') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.hero h2 {
    font-size: 36px;
    margin: 0;
}

.hero p {
    font-size: 18px;
    margin: 10px 0;
}

.video-gallery {
    display: flex;
    justify-content: space-around;
    padding: 20px;
}

.video-card {
    text-align: center;
}

#about, #contact {
    padding: 20px;
}

#contact-form {
    display: flex;
    flex-direction: column;
    width: 300px;
    margin: 0 auto;
}

#contact-form input, #contact-form textarea {
    margin: 10px 0;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

#contact-form button {
    padding: 10px;
    background-color: #25d366;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px 0;
    margin-top: 20px;
}
 
