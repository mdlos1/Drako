<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <title>Drako - Inicio</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            background-color: #fff8f0;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #4b2c20;
            color: white;
            padding: 60px 20px;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }
        p.slogan {
            font-style: italic;
            font-size: 1.5em;
            margin-top: 0;
        }
        .btn {
            display: inline-block;
            margin-top: 40px;
            padding: 15px 30px;
            font-size: 1.2em;
            background-color: #e0c9a6;
            color: #4b2c20;
            text-decoration: none;
            border-radius: 8px;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #d4b792;
        }
    </style>
</head>
<body>
    <header>
        <h1>Drako</h1>
        <p class="slogan">LUZ QUE DA FUERZA INTERIOR</p>
        <a href="productos.html" class="btn">Ver Productos</a>
    </header>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <title>Productos - Drako</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fff8f0;
            color: #333;
        }
        header {
            background-color: #4b2c20;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header .slogan {
            font-style: italic;
            font-size: 1.2em;
            margin-top: 5px;
        }
        nav {
            background-color: #e0c9a6;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4b2c20;
            font-weight: bold;
        }
        .section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            width: 250px;
            background-color: white;
            text-align: center;
            transition: transform 0.2s;
        }
        .product:hover {
            transform: scale(1.03);
        }
        .product img {
            max-width: 100%;
            border-radius: 8px;
            height: auto;
        }
        footer {
            background-color: #4b2c20;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Productos Drako</h1>
        <p class="slogan">LUZ QUE DA FUERZA INTERIOR</p>
    </header>
    <nav>
        <a href="index.html">Inicio</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section class="section">
        <h2>Nuestras Velas</h2>
        <div class="products">
            <div class="product">
                <img src="https://ambientegourmet.vtexassets.com/arquivos/ids/238576-800-auto?v=638815289699930000&width=800&height=auto&aspect=true" alt="Vela Decorativa Blanca" />
                <h3>Vela Decorativa Blanca</h3>
                <p>Elegancia minimalista para ambientes cálidos y sofisticados. Ideal para regalar o ambientar tu espacio.</p>
            </div>
            <div class="product">
                <img src="https://yaabil.com/wp-content/uploads/2024/06/8-1024x683.jpg" alt="Set de Velas Florales" />
                <h3>Set de Velas Florales</h3>
                <p>Aromas florales y presentación delicada. Una combinación perfecta de aroma y decoración artesanal.</p>
            </div>
            <div class="product">
                <img src="https://cdn.shopify.com/s/files/1/0848/2770/1572/files/velas_de_soja_3_480x480.png?v=1734281730" alt="Velas Naturales" />
                <h3>Velas Naturales</h3>
                <p>Aromas suaves, sin químicos agresivos. Perfectas para crear un ambiente relajante y armonioso.</p>
            </div>
        </div>
    </section>
    <section id="contacto" class="section">
        <h2>Contacto</h2>
        <p>¿Quieres hacer un pedido o tienes alguna consulta?</p>
        <p><strong>Email:</strong> drakovelas@gmail.com</p>
        <p><strong>Instagram:</strong> <a href="https://instagram.com/drakovelas" target="_blank">@drakovelas</a></p>
    </section>
    <footer>
        <p>&copy; 2025 Drako - Todos los derechos reservados.</p>
    </footer>
</body>
</html>
