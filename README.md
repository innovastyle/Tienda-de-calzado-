<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Calzado Clásico</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f6f1;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #d3c4e3;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #b2a1c7;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .productos {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .producto {
            background-color: #e3d9f1;
            border: 1px solid #ccc;
            border-radius: 10px;
            padding: 15px;
            margin: 10px;
            width: 30%;
            text-align: center;
        }
        .producto img {
            max-width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #d3c4e3;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tienda de Calzado Clásico</h1>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#productos">Productos</a>
        <a href="#nosotros">Nosotros</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <div class="container" id="inicio">
        <h2>Bienvenidos a nuestra tienda de calzado</h2>
        <p>Encuentra los mejores zapatos clásicos y elegantes para cada ocasión.</p>
        <img src="https://via.placeholder.com/800x300" alt="Imagen destacada">
    </div>
    <div class="container" id="productos">
        <h2>Nuestros Productos</h2>
        <div class="productos">
            <div class="producto">
                <img src="https://via.placeholder.com/150" alt="Zapato 1">
                <h3>Zapato Clásico 1</h3>
                <p>$50.00</p>
            </div>
            <div class="producto">
                <img src="https://via.placeholder.com/150" alt="Zapato 2">
                <h3>Zapato Clásico 2</h3>
                <p>$60.00</p>
            </div>
            <div class="producto">
                <img src="https://via.placeholder.com/150" alt="Zapato 3">
                <h3>Zapato Clásico 3</h3>
                <p>$55.00</p>
            </div>
        </div>
    </div>
    <div class="container" id="nosotros">
        <h2>Sobre Nosotros</h2>
        <p>Somos una tienda dedicada a ofrecer calzado clásico y elegante, con un enfoque en la calidad y el estilo atemporal. Nuestro objetivo es proporcionar a nuestros clientes productos que combinen comodidad y elegancia.</p>
    </div>
    <div class="container" id="contacto">
        <h2>Contacto</h2>
        <p>Para más información, puedes contactarnos a través de:</p>
        <ul>
            <li>Email: info@tiendadecalzado.com</li>
            <li>Teléfono: +123 456 7890</li>
            <li>Dirección: Calle Falsa 123, Ciudad, País</li>
        </ul>
    </div>
    <footer>
        <p>&copy; 2024 Tienda de Calzado Clásico. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
