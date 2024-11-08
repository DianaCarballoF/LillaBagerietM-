<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lilla Bageriet</title>
    <style>
        /* Reset de estilos básicos */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            color: #4d4d4d;
            background-color: #fffaf1;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            line-height: 1.6;
        }
        /* Encabezado */
        header {
            text-align: center;
            margin-bottom: 30px;
        }
        header h1 {
            font-size: 3em;
            color: #c95b72;
        }
        header p {
            font-size: 1.2em;
            color: #666;
        }
        /* Botón de Instagram */
        .instagram-link {
            display: inline-block;
            padding: 12px 24px;
            background-color: #c95b72;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 10px;
            transition: background-color 0.3s;
        }
        .instagram-link:hover {
            background-color: #a9455c;
        }
        /* Sección de productos */
        .product-section {
            width: 100%;
            max-width: 800px;
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            margin-top: 20px;
        }
        .product-card {
            width: 100%;
            max-width: 300px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
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
        .product-card h2 {
            font-size: 1.5em;
            color: #c95b72;
            margin: 15px 0;
        }
        .product-card p {
            padding: 0 15px;
            color: #666;
            font-size: 1em;
            margin-bottom: 15px;
        }
        /* Pie de página */
        footer {
            margin-top: 30px;
            font-size: 0.9em;
            color: #999;
        }
    </style>
</head>
<body>

    <header>
        <h1>Lilla Bageriet</h1>
        <p>Artisan Pastries Crafted with Love</p>
        <a href="https://www.instagram.com/LillabagerietM/" class="instagram-link" target="_blank">
            Follow us on Instagram
        </a>
    </header>

    <section class="product-section">
        <div class="product-card">
            <img src="https://via.placeholder.com/300x200" alt="Pan de Muerto">
            <h2>Pan de Muerto</h2>
            <p>A traditional Mexican bread, perfect for Día de Muertos or any occasion. Soft, flavorful, and made with care.</p>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300x200" alt="Alfajores">
            <h2>Alfajores</h2>
            <p>Delicious dulce de leche-filled cookies, a sweet treat that melts in your mouth with each bite.</p>
        </div>
    </section>

    <footer>
        &copy; 2024 Lilla Bageriet. All rights reserved.
    </footer>

</body>
</html>