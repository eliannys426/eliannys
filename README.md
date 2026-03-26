# eliannys
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venezuela: Tierra de Gracia</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; color: #333; background-color: #f4f4f4; }
        header { background: #003893; color: white; padding: 40px 20px; text-align: center; border-bottom: 8px solid #f4d03f; }
        .container { max-width: 1000px; margin: 20px auto; padding: 20px; background: white; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; margin-top: 20px; }
        .card { border: 1px solid #ddd; border-radius: 10px; overflow: hidden; transition: transform 0.3s; }
        .card:hover { transform: scale(1.03); }
        .card img { width: 100%; height: 200px; object-fit: cover; background-color: #eee; }
        .card-content { padding: 15px; }
        h2 { color: #ce1126; border-left: 5px solid #003893; padding-left: 10px; margin-top: 40px; }
    </style>
</head>
<body>

<header>
    <h1>Venezuela</h1>
    <p>Un paraíso por descubrir: paisajes, sabor y cultura</p>
</header>

<div class="container">
    <h2>🏔️ Paisajes Naturales</h2>
    <div class="grid">
        <div class="card">
            <!-- La ruta "img/archivo.jpg" busca dentro de tu carpeta img -->
            <img src="img/salto-angel.jpg" alt="Salto Ángel en Canaima">
            <div class="card-content">
                <h3>Salto Ángel</h3>
                <p>La caída de agua más alta del mundo, ubicada en el Parque Nacional Canaima.</p>
            </div>
        </div>
        <div class="card">
            <img src="img/los-roques.jpg" alt="Archipiélago Los Roques">
            <div class="card-content">
                <h3>Los Roques</h3>
                <p>Aguas turquesas y arenas blancas en uno de los arrecifes más bellos del Caribe.</p>
            </div>
        </div>
    </div>

    <h2>🫓 Sabores Típicos</h2>
    <div class="grid">
        <div class="card">
            <img src="img/arepa.jpg" alt="Arepas venezolanas">
            <div class="card-content">
                <h3>La Arepa</h3>
                <p>Nuestra comida más icónica. Hecha de maíz y rellena de lo que prefieras.</p>
            </div>
        </div>
        <div class="card">
            <div class="card-content">
                <h3>Pabellón Criollo</h3>
                <p>El plato nacional compuesto por arroz, caraotas, carne mechada y tajadas.</p>
            </div>
        </div>
    </div>
</div>

</body>
</html>
