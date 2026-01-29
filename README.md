# Articulos-Medico-Dentales-INOVA
Artículos-Medico-Dentales-INOVA
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INOVA - Artículos Medico-Dentales</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --morado-principal: #6a1b9a; /* El morado de tu tarjeta */
            --morado-oscuro: #4a148c;
            --blanco: #ffffff;
            --gris-claro: #f8f9fa;
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--blanco);
        }

        /* Encabezado */
        header {
            background: linear-gradient(135deg, var(--morado-principal), var(--morado-oscuro));
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 5px solid #e1bee7;
        }

        .logo-text { font-size: 3rem; font-weight: 700; margin: 0; letter-spacing: 2px; }
        .subtitle { font-size: 1.2rem; margin-top: 10px; opacity: 0.9; }

        /* Sección Hero */
        .hero {
            padding: 40px 20px;
            text-align: center;
            background-color: var(--gris-claro);
        }

        .servicios-tag {
            background: #e1bee7;
            color: var(--morado-oscuro);
            padding: 8px 15px;
            border-radius: 20px;
            font-weight: bold;
            display: inline-block;
            margin-bottom: 20px;
        }

        /* Productos */
        .contenedor { max-width: 1000px; margin: auto; padding: 20px; }
        .grid-productos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: white;
            border-radius: 15px;
            padding: 25px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-top: 5px solid var(--morado-principal);
            transition: transform 0.3s;
        }

        .card:hover { transform: translateY(-5px); }
        .card h3 { color: var(--morado-principal); }

        /* Botón WhatsApp */
        .btn-ws {
            background-color: #25d366;
            color: white;
            padding: 18px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2rem;
            display: inline-block;
            margin-top: 30px;
            box-shadow: 0 4px 15px rgba(37, 211, 102, 0.4);
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <header>
        <h1 class="logo-text">INOVA</h1>
        <p class="subtitle">Artículos Medico-Dentales</p>
    </header>

    <section class="hero">
        <span class="servicios-tag">🚚 CONTAMOS CON SERVICIO A DOMICILIO</span>
        <h2>Surtido, calidad y el mejor precio</h2>
        <p>Tu aliado confiable en suministros para la salud.</p>
        
        <a href="https://wa.me/521234567890?text=Hola%20INOVA,%20me%20gustaría%20hacer%20un%20pedido" class="btn-ws" target="_blank">
            💬 Hacer pedido por WhatsApp
        </a>
    </section>

    <div class="contenedor">
        <div class="grid-productos">
            <div class="card">
                <h3>🦷 Sector Dental</h3>
                <p>Resinas, brackets, guantes, instrumental quirúrgico, piezas de mano y más.</p>
            </div>
            <div class="card">
                <h3>🩺 Sector Médico</h3>
                <p>Material de curación, equipo de diagnóstico, antisépticos y desechables.</p>
            </div>
            <div class="card">
                <h3>✨ Especialidades</h3>
                <p>Todo lo que necesitas para tu clínica con entrega inmediata.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 INOVA Artículos Medico-Dentales</p>
        <p>Calidad profesional a su alcance</p>
    </footer>

</body>
</html><!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INOVA - Artículos Medico-Dentales</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --morado-principal: #6a1b9a; /* El morado de tu tarjeta */
            --morado-oscuro: #4a148c;
            --blanco: #ffffff;
            --gris-claro: #f8f9fa;
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--blanco);
        }

        /* Encabezado */
        header {
            background: linear-gradient(135deg, var(--morado-principal), var(--morado-oscuro));
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 5px solid #e1bee7;
        }

        .logo-text { font-size: 3rem; font-weight: 700; margin: 0; letter-spacing: 2px; }
        .subtitle { font-size: 1.2rem; margin-top: 10px; opacity: 0.9; }

        /* Sección Hero */
        .hero {
            padding: 40px 20px;
            text-align: center;
            background-color: var(--gris-claro);
        }

        .servicios-tag {
            background: #e1bee7;
            color: var(--morado-oscuro);
            padding: 8px 15px;
            border-radius: 20px;
            font-weight: bold;
            display: inline-block;
            margin-bottom: 20px;
        }

        /* Productos */
        .contenedor { max-width: 1000px; margin: auto; padding: 20px; }
        .grid-productos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: white;
            border-radius: 15px;
            padding: 25px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-top: 5px solid var(--morado-principal);
            transition: transform 0.3s;
        }

        .card:hover { transform: translateY(-5px); }
        .card h3 { color: var(--morado-principal); }

        /* Botón WhatsApp */
        .btn-ws {
            background-color: #25d366;
            color: white;
            padding: 18px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2rem;
            display: inline-block;
            margin-top: 30px;
            box-shadow: 0 4px 15px rgba(37, 211, 102, 0.4);
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <header>
        <h1 class="logo-text">INOVA</h1>
        <p class="subtitle">Artículos Medico-Dentales</p>
    </header>

    <section class="hero">
        <span class="servicios-tag">🚚 CONTAMOS CON SERVICIO A DOMICILIO</span>
        <h2>Surtido, calidad y el mejor precio</h2>
        <p>Tu aliado confiable en suministros para la salud.</p>
        
        <a href="https://wa.me/521234567890?text=Hola%20INOVA,%20me%20gustaría%20hacer%20un%20pedido" class="btn-ws" target="_blank">
            💬 Hacer pedido por WhatsApp
        </a>
    </section>

    <div class="contenedor">
        <div class="grid-productos">
            <div class="card">
                <h3>🦷 Sector Dental</h3>
                <p>Resinas, brackets, guantes, instrumental quirúrgico, piezas de mano y más.</p>
            </div>
            <div class="card">
                <h3>🩺 Sector Médico</h3>
                <p>Material de curación, equipo de diagnóstico, antisépticos y desechables.</p>
            </div>
            <div class="card">
                <h3>✨ Especialidades</h3>
                <p>Todo lo que necesitas para tu clínica con entrega inmediata.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 INOVA Artículos Medico-Dentales</p>
        <p>Calidad profesional a su alcance</p>
    </footer>

</body>
</html><!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INOVA - Artículos Medico-Dentales</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --morado-principal: #6a1b9a; /* El morado de tu tarjeta */
            --morado-oscuro: #4a148c;
            --blanco: #ffffff;
            --gris-claro: #f8f9fa;
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--blanco);
        }

        /* Encabezado */
        header {
            background: linear-gradient(135deg, var(--morado-principal), var(--morado-oscuro));
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 5px solid #e1bee7;
        }

        .logo-text { font-size: 3rem; font-weight: 700; margin: 0; letter-spacing: 2px; }
        .subtitle { font-size: 1.2rem; margin-top: 10px; opacity: 0.9; }

        /* Sección Hero */
        .hero {
            padding: 40px 20px;
            text-align: center;
            background-color: var(--gris-claro);
        }

        .servicios-tag {
            background: #e1bee7;
            color: var(--morado-oscuro);
            padding: 8px 15px;
            border-radius: 20px;
            font-weight: bold;
            display: inline-block;
            margin-bottom: 20px;
        }

        /* Productos */
        .contenedor { max-width: 1000px; margin: auto; padding: 20px; }
        .grid-productos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: white;
            border-radius: 15px;
            padding: 25px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-top: 5px solid var(--morado-principal);
            transition: transform 0.3s;
        }

        .card:hover { transform: translateY(-5px); }
        .card h3 { color: var(--morado-principal); }

        /* Botón WhatsApp */
        .btn-ws {
            background-color: #25d366;
            color: white;
            padding: 18px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2rem;
            display: inline-block;
            margin-top: 30px;
            box-shadow: 0 4px 15px rgba(37, 211, 102, 0.4);
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <header>
        <h1 class="logo-text">INOVA</h1>
        <p class="subtitle">Artículos Medico-Dentales</p>
    </header>

    <section class="hero">
        <span class="servicios-tag">🚚 CONTAMOS CON SERVICIO A DOMICILIO</span>
        <h2>Surtido, calidad y el mejor precio</h2>
        <p>Tu aliado confiable en suministros para la salud.</p>
        
        <a href="https://wa.me/521234567890?text=Hola%20INOVA,%20me%20gustaría%20hacer%20un%20pedido" class="btn-ws" target="_blank">
            💬 Hacer pedido por WhatsApp
        </a>
    </section>

    <div class="contenedor">
        <div class="grid-productos">
            <div class="card">
                <h3>🦷 Sector Dental</h3>
                <p>Resinas, brackets, guantes, instrumental quirúrgico, piezas de mano y más.</p>
            </div>
            <div class="card">
                <h3>🩺 Sector Médico</h3>
                <p>Material de curación, equipo de diagnóstico, antisépticos y desechables.</p>
            </div>
            <div class="card">
                <h3>✨ Especialidades</h3>
                <p>Todo lo que necesitas para tu clínica con entrega inmediata.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 INOVA Artículos Medico-Dentales</p>
        <p>Calidad profesional a su alcance</p>
    </footer>

</body>
</html><!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INOVA - Artículos Medico-Dentales</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --morado-principal: #6a1b9a; /* El morado de tu tarjeta */
            --morado-oscuro: #4a148c;
            --blanco: #ffffff;
            --gris-claro: #f8f9fa;
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--blanco);
        }

        /* Encabezado */
        header {
            background: linear-gradient(135deg, var(--morado-principal), var(--morado-oscuro));
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 5px solid #e1bee7;
        }

        .logo-text { font-size: 3rem; font-weight: 700; margin: 0; letter-spacing: 2px; }
        .subtitle { font-size: 1.2rem; margin-top: 10px; opacity: 0.9; }

        /* Sección Hero */
        .hero {
            padding: 40px 20px;
            text-align: center;
            background-color: var(--gris-claro);
        }

        .servicios-tag {
            background: #e1bee7;
            color: var(--morado-oscuro);
            padding: 8px 15px;
            border-radius: 20px;
            font-weight: bold;
            display: inline-block;
            margin-bottom: 20px;
        }

        /* Productos */
        .contenedor { max-width: 1000px; margin: auto; padding: 20px; }
        .grid-productos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: white;
            border-radius: 15px;
            padding: 25px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-top: 5px solid var(--morado-principal);
            transition: transform 0.3s;
        }

        .card:hover { transform: translateY(-5px); }
        .card h3 { color: var(--morado-principal); }

        /* Botón WhatsApp */
        .btn-ws {
            background-color: #25d366;
            color: white;
            padding: 18px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2rem;
            display: inline-block;
            margin-top: 30px;
            box-shadow: 0 4px 15px rgba(37, 211, 102, 0.4);
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <header>
        <h1 class="logo-text">INOVA</h1>
        <p class="subtitle">Artículos Medico-Dentales</p>
    </header>

    <section class="hero">
        <span class="servicios-tag">🚚 CONTAMOS CON SERVICIO A DOMICILIO</span>
        <h2>Surtido, calidad y el mejor precio</h2>
        <p>Tu aliado confiable en suministros para la salud.</p>
        
        <a href="https://wa.me/521234567890?text=Hola%20INOVA,%20me%20gustaría%20hacer%20un%20pedido" class="btn-ws" target="_blank">
            💬 Hacer pedido por WhatsApp
        </a>
    </section>

    <div class="contenedor">
        <div class="grid-productos">
            <div class="card">
                <h3>🦷 Sector Dental</h3>
                <p>Resinas, brackets, guantes, instrumental quirúrgico, piezas de mano y más.</p>
            </div>
            <div class="card">
                <h3>🩺 Sector Médico</h3>
                <p>Material de curación, equipo de diagnóstico, antisépticos y desechables.</p>
            </div>
            <div class="card">
                <h3>✨ Especialidades</h3>
                <p>Todo lo que necesitas para tu clínica con entrega inmediata.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 INOVA Artículos Medico-Dentales</p>
        <p>Calidad profesional a su alcance</p>
    </footer>

</body>
</html>
