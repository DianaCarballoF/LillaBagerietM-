<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lilla Bageriet</title>
    <style>
        /* Estilos generales */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background-color: #faf3e0;
            color: #333;
        }

        /* Encabezado y menú de navegación */
        header {
            background-color: #c95b72;
            color: white;
            padding: 20px;
            text-align: center;
            position: relative;
        }
        header h1 {
            font-size: 2.5em;
            margin-bottom: 5px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #a9455c;
            padding: 10px 0;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        nav ul li {
            position: relative;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 8px;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #faf3e0;
        }

        /* Sección Hero */
        .hero {
            background-image: url('https://via.placeholder.com/1200x500'); /* Reemplaza con una imagen de fondo */
            background-size: cover;
            background-position: center;
            padding: 80px 20px;
            text-align: center;
            color: white;
        }
        .hero h2 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        /* Sección de productos */
        .product-section {
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px;
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product-card {
            background-color: #fff;
            width: 300px;
            border-radius: 10px;
            box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s;
        }
        .product-card:hover {
            transform: scale(1.05);
        }
        .product-card img {
            width: 100%;
            height: auto;
            object-fit: cover;
        }
        .product-card h3 {
            font-size: 1.8em;
            color: #c95b72;
            margin: 15px 0;
        }
        .product-card p {
            padding: 0 15px;
            color: #666;
            font-size: 1em;
            margin-bottom: 15px;
        }

        /* Sección de contacto */
        .contact-section {
            background-color: #f1e4d3;
            padding: 40px 20px;
            text-align: center;
        }
        .contact-section h2 {
            font-size: 2em;
            color: #c95b72;
            margin-bottom: 20px;
        }
        .contact-section p {
            font-size: 1.2em;
            color: #555;
        }
        
        /* Pie de página */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <!-- Encabezado y menú de navegación -->
    <header>
        <h1>Lilla Bageriet</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Sección Hero -->
    <section class="hero" id="home">
        <h2>Welcome to Lilla Bageriet</h2>
        <p>Handcrafted Baked Goods with Love and Tradition</p>
    </section>

    <!-- Sección de productos -->
    <section class="product-section" id="products">
        <div class="product-card">
            <img src="https://via.placeholder.com/300x200" alt="Pan de Muerto">
            <h3>Pan de Muerto</h3>
            <p>Traditional Mexican bread for Día de Muertos, filled with rich flavors and memories.</p>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300x200" alt="Alfajores">
            <h3>Alfajores</h3>
            <p>Delicious cookies filled with dulce de leche, perfect for indulging or sharing.</p>
        </div>
    </section>

    <!-- Sección de contacto -->
    <section class="contact-section" id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:lillabageriet@example.com">lillabageriet@example.com</a></p>
    </section>

    <footer>
        &copy; 2024 Lilla Bageriet. All rights reserved.
    </footer>

</body>
</html>