<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HazaGlow - Luminosidad Natural para tu Piel</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header -->
    <header>
        <div class="container">
            <h1>HazaGlow</h1>
            <p>Luminosidad Natural para tu Piel</p>
            <a href="#productos" class="btn">Compra Ahora</a>
            <a href="#sobre-nosotros" class="btn">Conoce más</a>
        </div>
    </header>

    <!-- Sobre Nosotros -->
    <section id="sobre-nosotros">
        <div class="container">
            <h2>Nuestra Historia: Belleza Natural para Todos</h2>
            <p>En HazaGlow, creemos que el cuidado de la piel no tiene que comprometer ni la salud ni el medio ambiente. Nuestra misión es ofrecer productos que nutran la piel de manera natural, con ingredientes sostenibles y de alta calidad.</p>
            <h3>Misión</h3>
            <p>Ofrecer productos que nutran la piel de manera natural y responsable.</p>
            <h3>Visión</h3>
            <p>Ser una marca reconocida por su compromiso con el bienestar y la belleza natural.</p>
            <h3>Valores</h3>
            <ul>
                <li>Sostenibilidad</li>
                <li>Cuidado personal</li>
                <li>Innovación</li>
            </ul>
            <img src="about-image.jpg" alt="Nuestra Historia" class="responsive">
        </div>
    </section>

    <!-- Productos -->
    <section id="productos">
        <div class="container">
            <h2>Descubre la Crema HazaGlow</h2>
            <div class="product">
                <img src="hazaglow.jpg" alt="HazaGlow Crema">
                <p>Nuestra crema HazaGlow ha sido diseñada para todas las personas que buscan un producto natural y eficaz. Con propiedades hidratantes, antioxidantes y protectoras, es perfecta para el cuidado diario de la piel.</p>
                <ul>
                    <li>Hipoalergénica</li>
                    <li>Sin parabenos ni productos químicos agresivos</li>
                    <li>Con filtro solar natural</li>
                    <li>Envase sostenible y reciclable</li>
                </ul>
                <a href="#" class="btn">Añadir al Carrito</a>
            </div>
        </div>
    </section>

    <!-- Sostenibilidad -->
    <section id="sostenibilidad">
        <div class="container">
            <h2>Compromiso con el Planeta</h2>
            <p>En HazaGlow, no solo cuidamos de tu piel, sino también del planeta. Cada uno de nuestros productos está diseñado con ingredientes naturales y empaques ecológicos, fomentando un ciclo de vida responsable y sostenible.</p>
            <h3>Packaging Ecológico</h3>
            <p>Utilizamos envases reciclables y biodegradables.</p>
            <h3>Producción Responsable</h3>
            <p>Obtenemos nuestros ingredientes de manera sostenible, minimizando nuestra huella de carbono.</p>
            <img src="sustainability.jpg" alt="Sostenibilidad" class="responsive">
        </div>
    </section>

    <!-- Blog -->
    <section id="blog">
        <div class="container">
            <h2>Consejos de Cuidado de la Piel y Belleza Natural</h2>
            <article>
                <h3>Los beneficios del ácido hialurónico en la hidratación de la piel</h3>
                <p>El ácido hialurónico es un compuesto clave que ayuda a mantener la piel hidratada y firme.</p>
            </article>
            <article>
                <h3>Cómo proteger tu piel de los radicales libres</h3>
                <p>Los radicales libres son moléculas dañinas que pueden afectar la salud de la piel; aquí te mostramos cómo combatirlos.</p>
            </article>
        </div>
    </section>
/* Estilos generales */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}

/* Header */
header {
    background-color: #a8dadc;
    color: white;
    text-align: center;
    padding: 50px 0;
}

header h1 {
    font-size: 48px;
}

header p {
    font-size: 24px;
    margin: 20px 0;
}

header .btn {
    background-color: #1d3557;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin: 5px;
}

header .btn:hover {
    background-color: #457b9d;
}

/* Sección de Sobre Nosotros */
section {
    background-color: white;
    padding: 50px 0;
    margin: 20px 0;
}

section h2 {
    text-align: center;
    color: #1d3557;
    margin-bottom: 20px;
}

section p, section ul {
    font-size: 18px;
    color: #333;
}

ul {
    list-style-type: square;
    padding-left: 20px;
}

h3 {
    color: #457b9d;
}

/* Productos */
.product {
    display: flex;
    align-items: center;
    flex-direction: column;
    text-align: center;
}

.product img {
    max-width: 300px;
    border-radius: 10px;
    margin-bottom: 20px;
}

/* Sostenibilidad */
.responsive {
    max-width: 100%;
    height: auto;
}

/* Blog */
article {
    margin-bottom: 20px;
}

article h3 {
    color: #457b9d;
}

/* Footer */
footer {
    background-color: #1d3557;
    color: white;
    text-align: center;
    padding: 20px 0;
}

footer p {
    margin: 0;
}

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 HazaGlow. Todos los derechos reservados.</p>
        </div>
    </footer>

</body>
</html>
