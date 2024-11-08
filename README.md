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
            background-color: #f5f5dc; /* Beige */
            color: #4b3832; /* Café oscuro */
        }
        
        /* Encabezado */
        header {
            background-image: url('https://via.placeholder.com/1200x600'); /* Reemplaza con una imagen de tus productos */
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
        header h1 {
            font-size: 3.5em;
            color: #4b3832; /* Café oscuro */
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.5em;
            color: #fff;
            margin-bottom: 20px;
        }
        .instagram-link {
            display: inline-block;
            padding: 12px 24px;
            background-color: #4b3832; /* Café oscuro */
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 10px;
            transition: background-color 0.3s;
        }
        .instagram-link:hover {
            background-color: #2f1e17; /* Café más oscuro */
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
            background-color: #fff; /* Blanco */
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
        .product-card h2 {
            font-size: 1.8em;
            color: #4b3832; /* Café oscuro */
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
            background-color: #f0e4d7; /* Beige más claro */
            padding: 40px 20px;
            text-align: center;
        }
        .contact-section h2 {
            font-size: 2em;
            color: #4b3832; /* Café oscuro */
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
            background-color: #4b3832; /* Café oscuro */
            color: #fff; /* Blanco */
            font-size: 0.9em;
        }
    </style>
</head>
<body>

    <header>
        <h1>Lilla Bageriet</h1>
        <p>Handcrafted Baked Goods with a Touch of Tradition</p>
        <a href="https://www.instagram.com/LillabagerietM/" class="instagram-link" target="_blank">
            Visit Our Instagram
        </a>
    </header>

    <section class="product-section">
        <div class="product-card">
            <img src="https://via.placeholder.com/300x200" alt="Pan de Muerto">
            <h2>Pan de Muerto</h2>
            <p>This traditional Mexican bread is a seasonal favorite, ideal for celebrating Día de Muertos or any occasion.</p>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300x200" alt="Alfajores">
            <h2>Alfajores</h2>
            <p>Delicate cookies filled with dulce de leche, perfect for indulging yourself or as a gift for loved ones.</p>
        </div>
    </section>

    <section class="contact-section">
        <h2>Contact Us</h2>
        <p>Have a question or want to place an order? Email us at <a href="mailto:lillabageriet@example.com">lillabageriet@example.com</a></p>
    </section>

    <footer>
        &copy; 2024 Lilla Bageriet. All rights reserved.
    </footer>

</body>
</html>
