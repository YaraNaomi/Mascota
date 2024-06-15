<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicias sin límites</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
        }
        header {
            background-color: #fcd2f3;
            color: #f5a2cf;
            text-align: center;
            padding: 15px;
            margin-bottom: 20px;
            position: relative;
        }
        .logo {
            width: 150px;
            height: auto;
            position: absolute;
            top: 20px;
            right: 20px;
            z-index: 999;
        }
        .main-title {
            font-family: 'Bubble Bobble';
            font-size: 2em;
            text-shadow: 2px 2px 2px #b68a51;
        }
        .sub-title {
            font-family: 'Bubble Bobble', Times, serif;
            font-size: 2em;
            text-shadow: 2px 2px 2px #b68a51;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            overflow: hidden;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            padding-top: 80px;
        }
        .product {
            width: 30%;
            margin-bottom: 20px;
            background-color: #fff;
            border: 1px solid #ddd;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
            box-sizing: border-box;
            overflow: hidden;
            cursor: pointer;
        }
        .product:hover {
            transform: translateY(-5px);
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product-details {
            padding: 20px;
            text-align: center;
        }
        .product-details h2 {
            margin-top: 0;
        }
        .hidden {
            display: none;
        }
        .details-container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ddd;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .form-container {
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .form-container h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
        }
        .form-group textarea {
            resize: vertical;
            height: 100px;
        }
        .form-group button {
            width: 100%;
            padding: 10px;
            background-color: #f5a2cf;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            color: #fff;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #e081af;
        }
    </style>
</head>
<body>
    <header>
        <img class="logo" src="Logo de Delicias sin límites.png" alt="Logo de Delicias sin límites">
        <h1><span class="main-title">Delicias sin</span> <span class="sub-title">límites</span></h1>
    </header>

    <div class="container">
        <div class="product" onclick="showDetails('cacahuate-platano')">
            <img src="galletacacahuateyplatano.jpeg" alt="Galleta de Cacahuate con Plátano">
            <div class="product-details">
                <h2>Galleta de Cacahuate con Plátano</h2>
                <p>Precio: $20</p>
                <p>Ingredientes: Cacahuate, plátano, amaranto, arándano, ajonjolí negro y blanco.</p>
            </div>
        </div>
        <div class="product" onclick="showDetails('coco-canela')">
            <img src="galletacoco.jpeg" alt="Galleta de Coco">
            <div class="product-details">
                <h2>Galleta de Coco</h2>
                <p>Precio: $20</p>
                <p>Ingredientes: Coco, canela, amaranto, nuez, ajonjolí blanco y negro.</p>
            </div>
        </div>
        <div class="product" onclick="showDetails('manzana')">
            <img src="galletasemillas.jpeg" alt="Galleta de Manzana">
            <div class="product-details">
                <h2>Galleta de Manzana</h2>
                <p>Precio: $20</p>
                <p>Ingredientes: Manzana, pepita de calabaza, amaranto, cacahuate, ajonjolí negro y blanco.</p>
            </div>
        </div>
        <div class="product" onclick="showDetails('platano')">
            <img src="galletaplatano.jpeg" alt="Galleta de Plátano">
            <div class="product-details">
                <h2>Galleta de Plátano</h2>
                <p>Precio: $20</p>
                <p>Ingredientes: Plátano, amaranto, ajonjolí negro y blanco, arándano</p>
            </div>
        </div>
    </div>

    <div id="details-cacahuate-platano" class="hidden details-container">
        <h2>Galleta de Cacahuate con Plátano</h2>
        <p>Deliciosa galleta de Plátano con Cacahuate</p>
        <p>Precio: $20</p>
        <p>Contenido: 5 piezas por paquete</p>
        <p>Ingredientes: Cacahuate, plátano, amaranto, arándano, ajonjolí negro y blanco</p>
        <p class="availability available">Disponibilidad: Disponible</p>
        <p>Opciones de envío: Envío estándar, Envío exprés</p>
    </div>

    <div id="details-coco-canela" class="hidden details-container">
        <h2>Galleta de Coco</h2>
        <p>Deliciosa galleta de Coco.</p>
        <p>Precio: $20</p>
        <p>Contenido: 5 piezas por paquete</p>
        <p>Ingredientes: coco, canela, amaranto, nuez, ajonjolí blanco, ajonjolí negro</p>
        <p class="availability available">Disponibilidad: Disponible</p>
        <p>Opciones de envío: Envío estándar, Envío exprés</p>
    </div>

    <div id="details-manzana" class="hidden details-container">
        <h2>Galleta de Manzana</h2>
        <p>Deliciosa galleta de manzana con pepita de calabaza.</p>
        <p>Precio: $20</p>
        <p>Contenido: 5 piezas por paquete</p>
        <p>Ingredientes: Manzana, pepita de calabaza, ajonjolí negro, ajonjolí blanco, amaranto</p>
        <p class="availability available">Disponibilidad: Disponible</p>
        <p>Opciones de envío: Envío estándar, Envío exprés</p>
    </div>

    <div id="details-platano" class="hidden details-container">
        <h2>Galleta de Plátano</h2>
        <p>Deliciosa galleta de Plátano.</p>
        <p>Precio: $20</p>
        <p>Contenido: 5 piezas por paquete</p>
        <p>Ingredientes: Plátano, amaranto, ajonjolí negro y blanco, arándano</p>
        <p class="availability available">Disponibilidad: Disponible</p>
        <p>Opciones de envío: Envío estándar, Envío exprés</p>
    </div>

    <div class="form-container" id="order-form">
        <h2>Formulario de Pedido</h2>
        <form action="#" method="post" onsubmit="return validateForm()">
            <div class="form-group">
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Correo Electrónico:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="phone">Teléfono:</label>
                <input type="tel" id="phone" name="phone" required>
            </div>
            <div class="form-group">
                <label for="product">Producto:</label>
                <select id="product" name="product" onchange="updateProductDetails()">
                    <option value="cacahuate-platano">Galleta de Cacahuate con Plátano</option>
                    <option value="coco-canela">Galleta de Coco</option>
                    <option value="manzana">Galleta de Manzana</option>
                    <option value="platano">Galleta de Plátano</option>
                </select>
            </div>
            <div class="form-group">
                <label for="quantity">Cantidad:</label>
                <input type="number" id="quantity" name="quantity" min="1" value="1" required>
            </div>
            <div class="form-group">
                <label for="shipping">Envío:</label>
                <select id="shipping" name="shipping">
                    <option value="standard">Envío estándar</option>
                    <option value="express">Envío exprés</option>
                </select>
            </div>
            <div class="form-group">
                <label for="message">Mensaje adicional:</label>
                <textarea id="message" name="message"></textarea>
            </div>
            <div class="form-group">
                <button type="submit">Enviar Pedido</button>
            </div>
        </form>
    </div>

    <script>
        function showDetails(productId) {
            // Ocultar todos los detalles primero
            var detailsContainers = document.querySelectorAll('.details-container');
            detailsContainers.forEach(function(container) {
                container.classList.add('hidden');
            });

            // Mostrar los detalles del producto seleccionado
            var selectedDetails = document.getElementById('details-' + productId);
            if (selectedDetails) {
                selectedDetails.classList.remove('hidden');
            }
        }

        function updateProductDetails() {
            var productId = document.getElementById('product').value;
            // Ocultar todos los detalles primero
            var detailsContainers = document.querySelectorAll('.details-container');
            detailsContainers.forEach(function(container) {
                container.classList.add('hidden');
            });

            // Mostrar los detalles del producto seleccionado en el formulario
            var selectedDetails = document.getElementById('details-' + productId);
            if (selectedDetails) {
                selectedDetails.classList.remove('hidden');
            }
        }

        function validateForm() {
            var name = document.getElementById('name').value;
            var email = document.getElementById('email').value;
            var phone = document.getElementById('phone').value;

            if (name.trim() === '' || email.trim() === '' || phone.trim() === '') {
                alert('Por favor completa todos los campos.');
                return false;
            }

            return true;
        }
    </script>
</body>
</html>
