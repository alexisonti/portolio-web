<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Personal</title>
    <style>
        /* Estilos del cuerpo */
        body {
            margin: 0; /* Elimina márgenes por defecto */
            height: 100vh; /* Asegura que el cuerpo ocupe toda la ventana */
            display: flex; /* Usa flexbox para centrar contenido */
            justify-content: center; /* Centra horizontalmente */
            align-items: flex-start; /* Alinea todo hacia la parte superior */
            flex-direction: column; /* Ordena los elementos en columna */
            background-image: url("fondo de pagina.jpg"); /* Imagen de fondo */
            background-size: cover; /* Escala la imagen para cubrir toda la pantalla */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que se repita */
            background-attachment: fixed; /* Fija la imagen de fondo */
            font-family: Arial, sans-serif;
            color: #fff; /* Texto en blanco para destacar */
            text-align: center; /* Centra el texto */
            padding-top: 60px; /* Agrega un espacio desde la parte superior */
        }

        /* Contenedor común para imagen, título y descripción */
        .contenido {
            background-color: rgba(0, 0, 0, 0.6); /* Fondo oscuro semi-transparente */
            border-radius: 15px; /* Esquinas redondeadas */
            padding: 20px;
            margin: 10px auto; /* Centra el contenedor */
            max-width: 80%; /* Limita el ancho máximo */
        }

        /* Estilos de la imagen */
        img {
            width: 300px; /* Ajusta el tamaño de la imagen */
            height: auto;
            border-radius: 10px; /* Bordes redondeados */
            margin-bottom: 10px; /* Espacio entre la imagen y el título */
        }

        /* Estilos de los títulos */
        h1, h2 {
            margin: 0;
        }

        /* Estilos del párrafo */
        p {
            font-size: 18px;
        }

        /* Estilos para el contenedor de Skills */
        .skills, .contact {
            background-color: rgba(0, 0, 0, 0.6); /* Fondo oscuro semi-transparente */
            border-radius: 15px; /* Esquinas redondeadas */
            padding: 20px;
            margin-top: 20px; /* Espacio entre los contenedores */
            max-width: 80%; /* Limita el ancho máximo */
            display: flex;
            flex-direction: column;
            align-items: center; /* Centra los elementos de forma vertical */
        }

        /* Contenedor de las imágenes dentro de Skills y Contact */
        .skills-images, .contact-images {
            display: flex;
            justify-content: center; /* Centra las imágenes */
            gap: 20px; /* Añade un espacio entre las imágenes */
            margin-top: 20px; /* Añade espacio entre el título y las imágenes */
        }

        /* Estilos de las imágenes dentro de Skills y Contact */
        .skills-images img, .contact-images img {
            width: 50px; /* Tamaño de las imágenes */
            height: 50px;
            border-radius: 8px; /* Bordes redondeados */
            cursor: pointer; /* Indica que las imágenes son clickeables */
        }

        /* Contenedor de las secciones (Skills y Contact) lado a lado */
        .sections-container {
            display: flex;
            justify-content: center; /* Centra las secciones */
            gap: 20px; /* Añade espacio entre los recuadros */
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="contenido">
        <img src="foto para web.jpeg" alt="Mi Imagen Central">
        <h1>Alexis Ontiveros</h1>
        <h2>About Me</h2>
    </div>

    <div class="contenido">
        <p>
            Soy de Argentina, estoy estudiando Ingeniería en Sistemas en la UTN Córdoba y actualmente trabajo como SA Operator.
        </p>
    </div>

    <!-- Sección de Skills y Contact -->
    <div class="sections-container">
        <!-- Sección de Skills -->
        <div class="skills">
            <h2>Skills</h2>
            <div class="skills-images">
                <img src="pyhton.png" alt="Skill 1">
                <img s
