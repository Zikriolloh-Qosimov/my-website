<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,
     initial-scale=1.0">
     <link rel="stylesheet" href="styles.css">
    <title>Document</title>
</head>
<body>
    <header>
        <nav>
            <div class="Logo">Zikr Web</div>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h2>Welcom to my Stylist Website</h2>
        <p>This website is made using HTML ,CSS and Javascript. <br>
            <br>Click the button below to see a message.</p>
            <button onclick="Showmessage()"Click me>
            </button>
        </section>
        <footer>
            <p> 2025 Zikriolloh Qosimov. All right reserved.
            </p>
        </footer>
        <script src="script1.js"></script>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(to right,#74ebd5, #ACB6E5);
    color: #333;
}
header {
    background-color: #fff;
    padding: 20px 0;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    top: 0;
    z-index: 1000;
}
nav {
    max-width: 100px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}
.logo {
    font-size: 24px;
    font-weight: bold;
    color: #2c3E50;

}
ul {
    list-style: none;
    display: flex;
}
ul li {
    margin-left: 20px;
}
ul li a {
    text-decoration: none;
    color: #2c3E50;
    font-weight: 500;
    transition: color o.3s ease;
}
ul li a:hover {
    color: #0077cc;
}
.hero {
    text-align: center;
    padding: 60px 20px;
    animation: fadeIn 1.5s ease;
}
.hero img:hover {
    transform: scale(1.05);
}
.hero h2 {
    font-size: 2em;
    margin-top: 20px;
}
.hero p {
    font-size: 1.2em;
    max-width: 600px;
    margin: 10px auto;
}
.hero button {
    background-color: #2c3E50;
    color: white;
    border: none;
    padding: 12px 15px;
    font-size: 1em;
    border-radius: 10px;
    cursor: pointer;
    margin-top: 20px;
    transition: background-color 0.3s ease;
}
.hero button:hover {
    background-color: #1A242F;
}
footer {
    text-align: center;
    padding: 20px;
    background-color: #ffffffcc;
    margin-top: 50px;
}
@keyframes fadeIn {
    0%  {opacity: 0;transform: translateY(20px);}
    100% {opacity: 1;transform: translateY(0);}
}

