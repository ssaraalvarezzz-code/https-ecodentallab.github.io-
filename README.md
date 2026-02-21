# https-ecodentallab.github.io-
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #f4f7f4;
    color: #333;
    scroll-behavior: smooth;
}

nav {
    background: #1e3f29;
    padding: 15px 10%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-weight: 500;
}

nav a:hover {
    color: #9bd3a7;
}

.hero {
    background: linear-gradient(rgba(30,70,40,0.8), rgba(30,70,40,0.8)),
    url('https://images.unsplash.com/photo-1588776814546-ec7e4f5f7c1d');
    background-size: cover;
    color: white;
    text-align: center;
    padding: 120px 20px;
}

.hero h1 {
    font-size: 3em;
    animation: fadeIn 1.5s ease-in-out;
}

.hero p {
    font-style: italic;
    font-size: 1.3em;
    animation: fadeIn 2s ease-in-out;
}

section {
    padding: 60px 10%;
}

h2 {
    text-align: center;
    color: #2f5d3a;
}

.button {
    background: #2f5d3a;
    color: white;
    padding: 12px 25px;
    border-radius: 5px;
    text-decoration: none;
    display: inline-block;
    margin-top: 20px;
}

.button:hover {
    background: #1e3f29;
}

.card-container {
    display: flex;
    gap: 30px;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    background: white;
    width: 300px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    overflow: hidden;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-8px);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card div {
    padding: 20px;
}

footer {
    background: #1e3f29;
    color: white;
    text-align: center;
    padding: 20px;
}

form {
    max-width: 600px;
    margin: auto;
}

input, textarea {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

@keyframes fadeIn {
    from {opacity: 0; transform: translateY(20px);}
    to {opacity: 1; transform: translateY(0);}
}

<!DOCTYPE html>
<html lang="gl">
<head>
<meta charset="UTF-8">
<title>EcoDental Lab</title>
<link rel="stylesheet" href="style.css">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>

<body>

<nav>
    <div style="color:white;font-weight:600;">EcoDental Lab</div>
    <div>
        <a href="index.html">Inicio</a>
        <a href="servizos.html">Servizos</a>
        <a href="modelo.html">Modelo</a>
        <a href="contacto.html">Contacto</a>
    </div>
</nav>

<div class="hero">
    <h1>EcoDental Lab</h1>
    <p>Colaboramos hoxe para sorrir mañán.</p>
    <a href="contacto.html" class="button">Solicitar Orzamento</a>
</div>

<section>
    <h2>Laboratorio Colaborativo Sostible en Vigo</h2>
    <p style="text-align:center;max-width:800px;margin:auto;">
        Modelo innovador que combina colaboración profesional,
        tecnoloxía compartida e precisión artesanal.
    </p>
</section>

<footer>
© 2026 EcoDental Lab | Vigo
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="gl">
<head>
<meta charset="UTF-8">
<title>EcoDental Lab</title>
<link rel="stylesheet" href="style.css">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>

<body>

<nav>
    <div style="color:white;font-weight:600;">EcoDental Lab</div>
    <div>
        <a href="index.html">Inicio</a>
        <a href="servizos.html">Servizos</a>
        <a href="modelo.html">Modelo</a>
        <a href="contacto.html">Contacto</a>
    </div>
</nav>

<div class="hero">
    <h1>EcoDental Lab</h1>
    <p>Colaboramos hoxe para sorrir mañán.</p>
    <a href="contacto.html" class="button">Solicitar Orzamento</a>
</div>

<section>
    <h2>Laboratorio Colaborativo Sostible en Vigo</h2>
    <p style="text-align:center;max-width:800px;margin:auto;">
        Modelo innovador que combina colaboración profesional,
        tecnoloxía compartida e precisión artesanal.
    </p>
</section>

<footer>
© 2026 EcoDental Lab | Vigo
</footer>

</body>
</html>
