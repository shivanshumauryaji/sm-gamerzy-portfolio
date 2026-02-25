# sm-gamerzy-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>S.M Gamerzy Official | Gaming Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background: linear-gradient(-45deg,#0f0f0f,#111,#000,#1a1a1a);
    background-size:400% 400%;
    animation: bg 10s ease infinite;
    color:white;
    overflow-x:hidden;
}

/* Animated Background */
@keyframes bg{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

/* Navbar */
nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 50px;
    background:rgba(0,0,0,0.8);
    position:fixed;
    width:100%;
    backdrop-filter:blur(10px);
    z-index:1000;
}

nav h2{
    color:#00ffcc;
    text-shadow:0 0 15px #00ffcc;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    transition:0.3s;
}

nav a:hover{
    color:#ff0055;
}

/* Hero */
.hero{
    height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    transition:transform 0.2s;
}

.hero h1{
    font-size:55px;
    color:#ff0055;
    text-shadow:0 0 30px #ff0055;
}

.hero p{
    margin-top:15px;
    font-size:20px;
    color:#ccc;
}

.btn{
    margin-top:25px;
    padding:12px 30px;
    background:#00ffcc;
    border:none;
    cursor:pointer;
    border-radius:8px;
    transition:0.3s;
}

.btn:hover{
    background:#ff0055;
    color:white;
    box-shadow:0 0 25px #ff0055;
}

/* Sections */
section{
    padding:120px 50px;
    text-align:center;
}

h2{
    margin-bottom:50px;
    color:#00ffcc;
    font-size:32px;
}

/* Cards */
.cards{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:30px;
}

.card{
    background:#1a1a1a;
    padding:40px;
    width:280px;
    border-radius:20px;
    box-shadow:0 0 20px #00ffcc;
    transition:0.4s;
    transform-style:preserve-3d;
}

.card:hover{
    transform:rotateY(15deg) rotateX(10deg) scale(1.05);
    box-shadow:0 0 40px #ff0055;
}

/* YouTube Button */
.yt-btn{
    display:inline-block;
    padding:15px 35px;
    background:#ff0000;
    color:white;
    text-decoration:none;
    border-radius:10px;
    margin-top:20px;
    transition:0.3s;
}

.yt-btn:hover{
    transform:scale(1.1);
    box-shadow:0 0 25px red;
}

/* Email Button */
.email-btn{
    display:inline-block;
    margin-top:20px;
    padding:15px 35px;
    background:#00ffcc;
    color:black;
    text-decoration:none;
    border-radius:10px;
    font-weight:bold;
    transition:0.3s;
}

.email-btn:hover{
    background:#ff0055;
    color:white;
    box-shadow:0 0 25px #ff0055;
    transform:scale(1.1);
}

/* Footer */
footer{
    background:black;
    padding:25px;
    text-align:center;
}

/* Responsive */
@media(max-width:768px){
    nav{
        flex-direction:column;
    }
}
</style>
</head>

<body>

<nav>
    <h2>🎮 S.M Gamerzy</h2>
    <div>
        <a href="#about">About</a>
        <a href="#games">Games</a>
        <a href="#youtube">YouTube</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<div class="hero">
    <h1>LEVEL UP YOUR GAME</h1>
    <p>Minecraft • Survival • FPS • Adventure</p>
    <button class="btn" onclick="alert('Welcome Gamer 🔥')">Start Journey</button>
</div>

<section id="about">
    <h2>About Me</h2>
    <p>I am Shivanshu, creator of S.M Gamerzy Official.
       I create exciting Minecraft and gaming content.</p>
</section>

<section id="games">
    <h2>My Gaming Content</h2>
    <div class="cards">
        <div class="card">
            <h3>Minecraft</h3>
            <p>One Block Series & Survival Builds</p>
        </div>
        <div class="card">
            <h3>FPS Games</h3>
            <p>High intensity action gameplay</p>
        </div>
        <div class="card">
            <h3>Open World</h3>
            <p>Exploration and adventure series</p>
        </div>
    </div>
</section>

<section id="youtube">
    <h2>YouTube Channel</h2>
    <p>Subscribe and support my gaming journey 🚀</p>
    <a class="yt-btn" href="https://youtube.com/@s.mgamerzyofficial" target="_blank">
        Visit My Channel
    </a>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Want to collaborate? Let's connect!</p>
    <a class="email-btn" href="mailto:playzshivanshu@gmail.com">
        📧 Email Me
    </a>
</section>

<footer>
    © 2026 S.M Gamerzy Official | All Rights Reserved
</footer>

<script>
/* 3D Mouse Tilt Effect */
document.addEventListener("mousemove", function(e){
    const hero = document.querySelector(".hero");
    let x = (window.innerWidth / 2 - e.pageX) / 30;
    let y = (window.innerHeight / 2 - e.pageY) / 30;
    hero.style.transform = `rotateY(${x}deg) rotateX(${y}deg)`;
});
</script>

</body>
</html>

<section id="playlist" style="
    padding: 80px 20px;
    background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
    text-align: center;
">

    <h2 style="
        font-size: 36px;
        color: #00ffcc;
        margin-bottom: 40px;
        text-transform: uppercase;
        letter-spacing: 2px;
    ">
        🎮 My Gaming Playlist
    </h2>

    <div style="
        max-width: 900px;
        margin: auto;
        border-radius: 25px;
        overflow: hidden;
        box-shadow: 0 25px 60px rgba(0,0,0,0.8);
        transition: 0.5s ease;
    " class="playlist-box">

        <iframe 
            width="100%" 
            height="500"
            src="https://www.youtube.com/embed/videoseries?list=PLGbnbLddPO-fFqdgvhOXltamUhfjw0ofF"
            frameborder="0"
            allowfullscreen>
        </iframe>

    </div>

</section>