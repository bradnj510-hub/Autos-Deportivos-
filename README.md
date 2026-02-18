<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Autos Deportivos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bienvenidos a Autos Deportivos</h1>
        <nav>
            <a href="#autos">Autos</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

 <section id="autos">
        <h2>Autos Disponibles</h2>
        <div class="autos-grid">
            <div class="auto">
                <img src="images/ferrari.jpg" alt="Ferrari">
                <h3>Ferrari F8</h3>
                <p>Precio: $280,000</p>
                <button>Comprar</button>
            </div>
            <div class="auto">
                <img src="images/lamborghini.jpg" alt="Lamborghini">
                <h3>Lamborghini Huracán</h3>
                <p>Precio: $300,000</p>
                <button>Comprar</button>
            </div>
    <!-- Puedes agregar más autos aquí -->
        </div>
    </section>

<section id="contacto">
        <h2>Contacto</h2>
        <p>Correo: ventas@autosdeportivos.com</p>
    </section>

<footer>
        <p>&copy; 2026 Autos Deportivos</p>
    </footer>

<script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #111;
    color: white;
    padding: 20px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

.autos-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
}

.auto {
    border: 1px solid #ccc;
    padding: 10px;
    width: 200px;
    text-align: center;
}

.auto img {
    width: 100%;
    height: auto;
}

button {
    background-color: red;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}

button:hover {
    background-color: darkred;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #111;
    color: white;
}
document.querySelectorAll('button').forEach(btn => {
    btn.addEventListener('click', () => {
        alert('Gracias por su interés. Nos pondremos en contacto.');
    });
});


