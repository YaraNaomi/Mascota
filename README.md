<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Las Mascotas</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        main {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }

        section {
            background-color: white;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #4CAF50;
        }

        section img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 15px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }

        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: sticky;
            bottom: 0;
            width: 100%;
        }

        a {
            color: #4CAF50;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Las Mascotas</h1>
        <nav>
            <ul>
                <li><a href="#perros">Perros</a></li>
                <li><a href="#gatos">Gatos</a></li>
                <li><a href="#aves">Aves</a></li>
                <li><a href="#cuidados">Cuidados</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="perros">
            <h2>Perros</h2>
            <p>Los perros son conocidos por ser los mejores amigos del hombre. Son leales y protectores.</p>
            <img src="Q nombre le pondrias.jfif" alt="Perro">
            <h3>Razas Populares</h3>
            <table>
                <thead>
                    <tr>
                        <th>Raza</th>
                        <th>Tamaño</th>
                        <th>Esperanza de Vida</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Labrador Retriever</td>
                        <td>Grande</td>
                        <td>10-12 años</td>
                    </tr>
                    <tr>
                        <td>Bulldog</td>
                        <td>Mediano</td>
                        <td>8-10 años</td>
                    </tr>
                    <tr>
                        <td>Beagle</td>
                        <td>Mediano</td>
                        <td>12-15 años</td>
                    </tr>
                </tbody>
            </table>
            <p>Para más información sobre perros, visita <a href="https://www.akc.org/dog-breeds/" target="_blank">American Kennel Club</a>.</p>
        </section>
        <section id="gatos">
            <h2>Gatos</h2>
            <p>Los gatos son independientes y curiosos. Son perfectos para apartamentos pequeños.</p>
            <img src="https://example.com/gatos.jpg" alt="Gato">
            <h3>Razas Populares</h3>
            <table>
                <thead>
                    <tr>
                        <th>Raza</th>
                        <th>Tamaño</th>
                        <th>Esperanza de Vida</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Persa</td>
                        <td>Mediano</td>
                        <td>12-17 años</td>
                    </tr>
                    <tr>
                        <td>Siames</td>
                        <td>Mediano</td>
                        <td>15-20 años</td>
                    </tr>
                    <tr>
                        <td>Maine Coon</td>
                        <td>Grande</td>
                        <td>10-13 años</td>
                    </tr>
                </tbody>
            </table>
            <p>Para más información sobre gatos, visita <a href="https://www.catfanciers.org/" target="_blank">Cat Fanciers' Association</a>.</p>
        </section>
        <section id="aves">
            <h2>Aves</h2>
            <p>Las aves son mascotas coloridas y algunas pueden aprender a hablar.</p>
            <img src="https://example.com/aves.jpg" alt="Ave">
            <h3>Tipos Populares</h3>
            <table>
                <thead>
                    <tr>
                        <th>Tipo</th>
                        <th>Tamaño</th>
                        <th>Esperanza de Vida</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Periquito</td>
                        <td>Pequeño</td>
                        <td>5-10 años</td>
                    </tr>
                    <tr>
                        <td>Cacatúa</td>
                        <td>Mediano</td>
                        <td>20-30 años</td>
                    </tr>
                    <tr>
                        <td>Loro Gris</td>
                        <td>Grande</td>
                        <td>40-60 años</td>
                    </tr>
                </tbody>
            </table>
            <p>Para más información sobre aves, visita <a href="https://www.parrots.org/" target="_blank">World Parrot Trust</a>.</p>
        </section>
        <section id="cuidados">
            <h2>Cuidados</h2>
            <p>Cada mascota tiene necesidades específicas. Es importante conocerlas para cuidarlas adecuadamente.</p>
            <h3>Consejos Generales</h3>
            <ul>
                <li>Visita regular al veterinario.</li>
                <li>Proporcionar una dieta adecuada.</li>
                <li>Ejercicio y entretenimiento.</li>
                <li>Mantener un ambiente limpio y seguro.</li>
            </ul>
            <p>Para más información sobre el cuidado de mascotas, visita <a href="https://www.aspca.org/pet-care" target="_blank">ASPCA Pet Care</a>.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Las Mascotas</p>
    </footer>
</body>
</html>
