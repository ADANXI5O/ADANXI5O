<header>
    <h1>Mi Página Web</h1>
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#acerca-de">Acerca de</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
</header>
<main>
    <section id="inicio">
        <h1>Bienvenido a Mi Página Web</h1>
        <p>Esta es una página de ejemplo creada para mostrar la estructura básica de un documento HTML.</p>
    </section>
</main>
<footer>
    <p>Tu Nombre  2024</p>
</footer>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acerca de - Mi Página Web</title>
</head>
<body>
    <header>
        <h1>Mi Página Web</h1>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="about.html">Acerca de</a></li>
                <li><a href="contact.html">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="acerca-de">
            <h1>Acerca de Nosotros</h1>
            <p>Bienvenido a nuestra página web. Este sitio está dedicado a proporcionar información sobre [tu tema o propósito].</p>
            <p>Somos una organización ficticia comprometida con [tu misión o visión]. Nuestro objetivo es [describir el objetivo principal].</p>
        </section>
    </main>
    <footer>
        <p>Tu Nombre  2024</p>
    </footer>
</body>
</html>
<link rel="stylesheet" href="styles.css">
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Contenido de la página -->
</body>
</html>
// Función para mostrar un mensaje de bienvenida en un cuadro de alerta
function mostrarMensajeBienvenida() {
    alert("¡Bienvenido a Mi Página Web!");
}

// Función para validar el formulario de contacto
function validarFormulario() {
    const nombre = document.getElementById('nombre').value;
    const email = document.getElementById('email').value;
    const mensaje = document.getElementById('mensaje').value;

    if (nombre === '' || email === '' || mensaje === '') {
        alert("Por favor, completa todos los campos.");
        return false;
    }
    return true;
}
