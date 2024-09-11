<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inicio - Mi Sitio Web</title>
    <style>
      
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333; 
            color: white; 
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 20px;
        }

        .logo img {
            height: 50px; 
        }

        nav ul {
            list-style-type: none; 
            margin: 0;
            padding: 0;
            display: flex;
        }

        nav ul li {
            margin-left: 20px; 
        }

        nav ul li a {
            color: white;
            text-decoration: none; 
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline; 
        }

     
        section {
            padding: 40px 20px;
            margin: 20px 0;
        }

        #menu {
            background-color: #f4f4f4;
        }

        #productos {
            background-color: #e2e2e2;
        }

        #servicio-al-cliente {
            background-color: #dcdcdc;
        }

        h2 {
            color: #333;
        }
    </style>
</head>
<body>
  
    <header>
      
        <div class="logo">
            <img src="ruta/del/logo.png" alt="Logo de la Empresa">
        </div>

        <nav>
            <ul>
                <li><a href="#menu">Menú</a></li> 
                <li><a href="#productos">Productos</a></li> 
                <li><a href="#servicio-al-cliente">Servicio al Cliente</a></li> 
            </ul>
        </nav>
    </header>

    <section id="menu">
        <h2>Menú</h2>
        <p>Bienvenido a nuestra sección de Menú. Aquí encontrarás nuestras mejores opciones culinarias.</p>
    </section>

    <!-- Sección de Productos -->
    <section id="productos">
        <h2>Productos</h2>
        <p>Explora nuestra variedad de productos de alta calidad. Tenemos algo para todos.</p>
    </section>

    <!-- Sección de Servicio al Cliente -->
    <section id="servicio-al-cliente">
        <h2>Servicio al Cliente</h2>
        <p>¿Tienes alguna pregunta o necesitas ayuda? Nuestro equipo de servicio al cliente está aquí para ayudarte.</p>
    </section>
</body>
</html>
