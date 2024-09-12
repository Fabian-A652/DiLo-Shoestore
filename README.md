<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DiLo Shoestore</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            background-color: #333;
        }
        nav ul li {
            display: inline;
            margin-right: 10px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 10px;
            display: inline-block;
        }
        nav ul li a:hover {
            background-color: #555;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 10px;
            padding: 15px;
            width: calc(33% - 40px);
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            color: #333;
            margin: 10px 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .carousel {
            display: flex;
            overflow: hidden;
        }
        .carousel img {
            width: 100%;
            transition: transform 0.5s ease;
        }
        section {
            margin: 20px 0;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin: 5px 0;
        }
        form input, form textarea {
            margin-bottom: 10px;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        form button {
            background-color: #333;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 4px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>DiLo Shoestore</h1>
            <p>La mejor selección de tenis y zapatos para ti</p>
        </div>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Inicio</a></li>
            <li><a href="#products">Productos</a></li>
            <li><a href="#carousel">Destacados</a></li>
            <li><a href="#contact">Contacto</a></li>
            <li><a href="#subscribe">Suscripción</a></li>
        </ul>
    </nav>

    <div class="container">
        <section id="products" class="products">
            <div class="product">
                <img src="imagen-producto1.jpg" alt="Tenis Modelo 1">
                <h3>Tenis Modelo 1</h3>
                <p>Descripción breve del producto.</p>
                <p>Precio: $XX.XX</p>
            </div>
            <div class="product">
                <img src="imagen-producto2.jpg" alt="Zapato Modelo 2">
                <h3>Zapato Modelo 2</h3>
                <p>Descripción breve del producto.</p>
                <p>Precio: $XX.XX</p>
            </div>
            <!-- Añade más productos aquí -->
        </section>

        <section id="carousel">
            <h2>Productos Destacados</h2>
            <div class="carousel">
                <img src="imagen-destacada1.jpg" alt="Producto Destacado 1">
                <
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DiLo Shoestore</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            background-color: #333;
        }
        nav ul li {
            display: inline;
            margin-right: 10px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 10px;
            display: inline-block;
        }
        nav ul li a:hover {
            background-color: #555;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 10px;
            padding: 15px;
            width: calc(25% - 40px);
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            color: #333;
            margin: 10px 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .carousel {
            display: flex;
            overflow: hidden;
        }
        .carousel img {
            width: 100%;
            transition: transform 0.5s ease;
        }
        section {
            margin: 20px 0;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin: 5px 0;
        }
        form input, form textarea {
            margin-bottom: 10px;
            padding: 8px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        form button {
            background-color: #333;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 4px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>DiLo Shoestore</h1>
            <p>La mejor selección de tenis y zapatos para ti</p>
        </div>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Inicio</a></li>
            <li><a href="#products">Productos</a></li>
            <li><a href="#carousel">Destacados</a></li>
            <li><a href="#contact">Contacto</a></li>
            <li><a href="#subscribe">Suscripción</a></li>
        </ul>
    </nav>

    <div class="container">
        <section id="products">
            <h2>Productos</h2>
            <div class="products">
                <!-- Productos Pirma -->
                <div class="product">
                    <img src="pirma-tenis1.jpg" alt="Tenis Pirma Modelo 1">
                    <h3>Tenis Pirma Modelo 1</h3>
                    <p>Descripción breve del producto Pirma Modelo 1.</p>
                    <p>Precio: $XX.XX</p>
                </div>
                <div class="product">
                    <img src="pirma-tenis2.jpg" alt="Tenis Pirma Modelo 2">
                    <h3>Tenis Pirma Modelo 2</h3>
                    <p>Descripción breve del producto Pirma Modelo 2.</p>
                    <p>Precio: $XX.XX</p>
                </div>
                <!-- Productos Puma -->
                <div class="product">
                    <img src="puma-tenis1.jpg" alt="Tenis Puma Modelo 1">
                    <h3>Tenis Puma Modelo 1</h3>
                    <p>Descripción breve del producto Puma Modelo 1.</p>
                    <p>Precio: $XX.XX</p>
                </div>
                <div class="product">
                    <img src="puma-tenis2.jpg" alt="Tenis Puma Modelo 2">
                    <h3>Tenis Puma Modelo 2</h3>
                    <p>Descripción breve del producto Puma Modelo 2.</p>
                    <p>Precio: $XX.XX</p>
                </div>
            </div>
        </section>

        <section id="carousel">
            <h2>Productos Destacados</h2>
            <div class="carousel">
                <img src="imagen-destacada1.jpg" alt="Producto Destacado 1">
                <img src="imagen-destacada2.jpg" alt="Producto Destacado 2">
                <img src="imagen-destacada3.jpg" alt="Producto Destacado 3">
            </div>
        </section>

        <section id="contact">
            <h2>Contacto</h2>
            <form action="mailto:tu-email@ejemplo.com" method="post" enctype="text/plain">
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Correo Electrónico:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Mensaje:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </section>

        <section id="subscribe">
            <h2>Suscríbete a Nuestro Boletín</h2>
            <form action="mailto:tu-email@ejemplo.com" method="post" enctype="text/plain">
                <label for="subscribe-email">Correo Electrónico:</label>
                <input type="email" id="subscribe-email" name="subscribe-email" required>
                <button type="submit">Suscribirse</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 DiLo Shoestore. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
