<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For My Love 💜</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(-45deg, #2a003f, #6a0dad, #4b0082, #8a2be2);
    background-size: 400% 400%;
    animation: gradientBG 10s ease infinite;
    color: white;
    text-align: center;
    overflow: hidden;
}

/* Animated Background */
@keyframes gradientBG {
    0% {background-position: 0%}
    50% {background-position: 100%}
    100% {background-position: 0%}
}

.container {
    margin-top: 50px;
    animation: fadeIn 2s ease-in-out;
}

h1 {
    font-size: 2.8em;
    text-shadow: 0 0 10px #d8b4fe, 0 0 20px #c084fc;
}

p {
    font-size: 1.3em;
    max-width: 600px;
    margin: auto;
    line-height: 1.6;
}

/* Glow */
.glow {
    color: #f3e8ff;
    text-shadow: 0 0 5px #c084fc, 0 0 15px #9333ea;
}

/* Image Style */
.photo {
    margin-top: 25px;
}

.photo img {
    width: 220px;
    height: 220px;
    object-fit: cover;
    border-radius: 20px;
    border: 4px solid #d8b4fe;
    box-shadow: 0 0 20px #a855f7;
    transition: transform 0.4s;
}

.photo img:hover {
    transform: scale(1.1);
}

/* Floating Hearts */
.heart {
    position: absolute;
    bottom: -10px;
    color: #ff80ff;
    font-size: 20px;
    animation: floatUp linear infinite;
}

@keyframes floatUp {
    0% {
        transform: translateY(0) scale(1);
        opacity: 1;
    }
    100% {
        transform: translateY(-100vh) scale(1.5);
        opacity: 0;
    }
}

/* Fade */
@keyframes fadeIn {
    from {opacity: 0; transform: translateY(20px);}
    to {opacity: 1; transform: translateY(0);}
}
</style>
</head>

<body>

<div class="container">
    <h1 class="glow">Hey My Love 💜</h1>

    <p>
        I just want you to know how <span class="glow">amazing</span> you are 💜<br><br>

        You’ve been working so hard, and I see every effort you make 🥺<br>
        Thank you for being so <span class="glow">caring</span>, loving, and patient 💕<br><br>

        I’m so proud of you always ✨<br>
        And no matter what, I’ll always be here for you 🌸<br><br>

        <strong class="glow">I love you so much 💜</strong>
    </p>

    <!-- 💜 YOUR PHOTO HERE -->
    <div class="photo">
        <img src="your-photo.jpg" alt="Us 💜">
    </div>
</div>

<!-- Floating hearts generator -->
<script>
function createHeart() {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "💜";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = (3 + Math.random() * 5) + "s";
    document.body.appendChild(heart);

    setTimeout(() => {
        heart.remove();
    }, 8000);
}

setInterval(createHeart, 300);
</script>

</body>
</html>
