<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COMIDA</title>
    <link rel="stylesheet" href="estilo.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
    <nav>
        <ul class="menu">
            <li><a href="">Inicio</a></li>
            <li><a href="#info">Información</a></li>
            <li><a href="#Conoce más">Conoce más</a></li>
            <li><a href="#galeria">Galería</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    <header class="hero">
        <div class="hero-texto">
            <h1>Comida Italiana</h1>
            <h2>Te mostramos la mejor comida italiana</h2>
        </div>
    </header>
    <section class="info" id="info">
        <div class="contenedor">
            <h3 class="titulo">Historia de la comida Italiana</h3>
            <p>La cocina italiana es parte integral de las gastronomías mediterráneas, 
                cuya dieta fue declarada Patrimonio Cultural Inmaterial de la Humanidad en 2010 por la Unesco, 
                y es imitada y practicada en todo el mundo. Algunas preparaciones más reconocidas son la pizza, 
                el risotto, muchas formas de pasta, la parmigiana, la frittata, el gelato o el tiramisú. 
                Italia también posee una larga tradición de vinos, café, chocolate, licores, quesos o aceite entre otros productos.</p>
        </div>
    </section>
    <section class="contenedor" id="Conoce más">
        <h2 class="titulo">Conoce más</h2>
        <div class="contenedor-card">
            <article class="card">
                <div class="espacio">
                    <i class="bi bi-flower2"></i>
                </div>
                <h3>Postres</h3>
                <p>Pide el mejor postre que probaras en tu vida</p>
                <a href="" class="boton">Pedir</a>
            </article>
            <article class="card">
                <div class="espacio">
                    <i class="bi bi-person-arms-up"></i>                </div>
                <h3>Pizzas</h3>
                <p>Elegir Ingredientes para tu pizza</p>
                <a href="" class="boton">Pedir</a>
            </article>
            <article class="card">
                <div class="espacio">
                    <i class="bi bi-house-door-fill"></i>
                </div>
                <h3>lasagna</h3>
                <p>Elige el tipo de lasagna que te gusta</p>
                <a href="" class="boton">Pedir</a>
            </article>
        </div>
    </section>
    <section class="galeria" id="galeria">
        <div class="contenedor">
            <h2 class="titulo">Imagenes de nuestra comida</h2>
            <div class="contenedor-galeria">
                <img src="IMAGEN/img1.jpg" alt="">
                <img src="IMAGEN/img2.jpg" alt="">
                <img src="IMAGEN/img3.jpg" alt="">
                <img src="IMAGEN/img4.jpg" alt="">
                <img src="IMAGEN/img5.jpg" alt="">
                <img src="IMAGEN/img6.jpg" alt="">
                <img src="IMAGEN/img7.jpg" alt="">
                <img src="IMAGEN/img8.jpg" alt="">
                <img src="IMAGEN/img9.webp" alt="">
                <img src="IMAGEN/img10.jpg" alt="">
                <img src="IMAGEN/img11.jpg" alt="">
                <img src="IMAGEN/img12.jpg" alt="">
            </div>
        </div>
    </section>
    <section class="contacto" id="contacto">
        <div class="contenedor">
            <h2 class="titulo">¡Ingresa tu nombre y direccion para tu pedido</h2>
            <form class="formulario">
                <input type="text" id="nombre" name="nom" class="input input-ancho" placeholder="Ingresa nombre">
                <input type="text" id="email" name="mail" class="input input-ancho" placeholder="Ingresa direccion">
                <textarea name="msj" id="msj" class="input textarea-ancho" placeholder="Ingrese algun pedido extra" cols="30"
                    rows="10"></textarea>
                <input type="reset" value="Limpiar" class="boton">
                <input type="submit" value="Enviar" class="boton">
                <input type="submit" value="Cancelar" class="boton">

            </form>
        </div>
    </section>
    <footer>
        <p> Empresa el pastita. Todos los derechos reservados.
            Contacto 
            -Numero: +56912345678-
            -Correo: lineasblancas@gmail.com-
            -Horario de antencion: 03:00AM - 04:00AM-
            -Direccion: calle mala muerte #1313
        </p>
    </footer>
</body>
</html>
