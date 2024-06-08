<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Afiliados</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Amazon Afiliados</h1>
    </header>
    <div class="product-container">
        <!-- Aquí van los productos -->
    </div>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    margin: 0;
}

header {
    background-color: #007bff;
    padding: 20px;
    text-align: center;
    color: #fff;
}

.product-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.product {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    padding: 20px;
    margin: 10px;
    text-align: center;
    width: 250px;
}

.product img {
    max-width: 100%;
    height: auto;
}

.product a {
    color: #007bff;
    text-decoration: none;
}

.product a:hover {
    text-decoration: underline;
}
