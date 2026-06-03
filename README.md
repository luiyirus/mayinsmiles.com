<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Buchaca Sana | Consultorio Dental</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<style>
:root{
    --azul:#0ea5e9;
    --azul-oscuro:#0369a1;
    --blanco:#ffffff;
    --gris:#f4f7fa;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Segoe UI, sans-serif;
}

body{
    background:var(--gris);
}

header{
    background:linear-gradient(135deg,var(--azul),var(--azul-oscuro));
    color:white;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:28px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

.hero{
    min-height:80vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
    background:url('https://images.unsplash.com/photo-1629909615184-74f495363b67?w=1200')
    center/cover;
}

.hero-content{
    background:rgba(0,0,0,.5);
    padding:40px;
    border-radius:15px;
}

.hero h1{
    font-size:3rem;
    margin-bottom:15px;
}

.btn{
    display:inline-block;
    margin-top:20px;
    padding:12px 25px;
    background:var(--azul);
    color:white;
    text-decoration:none;
    border-radius:8px;
}

section{
    padding:70px 8%;
}

h2{
    text-align:center;
    margin-bottom:30px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 3px 10px rgba(0,0,0,.1);
    text-align:center;
}

.galeria{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:15px;
}

.galeria img{
    width:100%;
    border-radius:10px;
}

.video{
    text-align:center;
}

.video iframe{
    width:100%;
    max-width:900px;
    height:500px;
    border:none;
    border-radius:15px;
}

.productos{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.producto{
    background:white;
    padding:15px;
    border-radius:15px;
    text-align:center;
}

.producto img{
    width:100%;
    height:200px;
    object-fit:cover;
    border-radius:10px;
}

button{
    background:var(--azul);
    color:white;
    border:none;
    padding:10px 15px;
    border-radius:8px;
    cursor:pointer;
    margin-top:10px;
}

#carrito{
    background:white;
    margin-top:30px;
    padding:20px;
    border-radius:15px;
}

.formulario{
    max-width:600px;
    margin:auto;
}

input, textarea{
    width:100%;
    padding:12px;
    margin:10px 0;
    border:1px solid #ccc;
    border-radius:8px;
}

footer{
    background:#111827;
    color:white;
    text-align:center;
    padding:25px;
}

.whatsapp{
    position:fixed;
    right:20px;
    bottom:20px;
    width:60px;
    height:60px;
    border-radius:50%;
    background:#25D366;
    color:white;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:30px;
    text-decoration:none;
}

@media(max-width:768px){
    header{
        flex-direction:column;
        gap:15px;
    }

    .hero h1{
        font-size:2rem;
    }

    .video iframe{
        height:250px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">
        🦷 Buchaca Sana
    </div>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#servicios">Servicios</a>
        <a href="#galeria">Galería</a>
        <a href="#tienda">Tienda</a>
        <a href="#contacto">Contacto</a>
    </nav>
</header>

<section class="hero" id="inicio">
    <div class="hero-content">
        <h1>Tu Sonrisa es Nuestra Prioridad</h1>
        <p>Consultorio dental moderno con atención profesional.</p>
        <a href="#contacto" class="btn">Agendar Cita</a>
    </div>
</section>

<section id="servicios">
    <h2>Servicios Dentales</h2>

    <div class="cards">
        <div class="card">
            <h3>🦷 Limpieza Dental</h3>
            <p>Prevención y salud bucal.</p>
        </div>

        <div class="card">
            <h3>😁 Blanqueamiento</h3>
            <p>Sonrisa más brillante.</p>
        </div>

        <div class="card">
            <h3>📐 Ortodoncia</h3>
            <p>Brackets y alineadores.</p>
        </div>

        <div class="card">
            <h3>👶 Odontopediatría</h3>
            <p>Atención especializada para niños.</p>
        </div>
    </div>
</section>

<section id="galeria">
    <h2>Galería</h2>

    <div class="galeria">
        <img src="https://images.unsplash.com/photo-1588776814546-1ffcf47267a5" alt="">
        <img src="https://images.unsplash.com/photo-1629909613654-28e377c37b09" alt="">
        <img src="https://images.unsplash.com/photo-1606811841689-23dfddce3e95" alt="">
    </div>
</section>

<section>
    <h2>Video Informativo</h2>

    <div class="video">
        <iframe
            src="https://www.youtube.com/embed/n6XJ3M5r6GQ"
            allowfullscreen>
        </iframe>
    </div>
</section>

<section id="tienda">
    <h2>Tienda Dental</h2>

    <div class="productos">

        <div class="producto">
            <img src="https://images.unsplash.com/photo-1559591937-abc6b6f5d44f">
            <h3>Cepillo Dental</h3>
            <p>$50</p>
            <button onclick="agregarProducto('Cepillo Dental',50)">
                Agregar
            </button>
        </div>

        <div class="producto">
            <img src="https://images.unsplash.com/photo-1607619056574-7b8d3ee536b2">
            <h3>Pasta Dental</h3>
            <p>$80</p>
            <button onclick="agregarProducto('Pasta Dental',80)">
                Agregar
            </button>
        </div>

        <div class="producto">
            <img src="https://images.unsplash.com/photo-1583947582886-f40ec95dd752">
            <h3>Enjuague Bucal</h3>
            <p>$120</p>
            <button onclick="agregarProducto('Enjuague Bucal',120)">
                Agregar
            </button>
        </div>

    </div>

    <div id="carrito">
        <h3>🛒 Carrito de Compras</h3>
        <ul id="lista-carrito"></ul>
        <h4>Total: $<span id="total">0</span></h4>
    </div>
</section>

<section id="contacto">
    <h2>Agenda tu Cita</h2>

    <div class="formulario">
        <input type="text" placeholder="Nombre completo">

        <input type="email" placeholder="Correo electrónico">

        <input type="date">

        <textarea rows="5" placeholder="Mensaje"></textarea>

        <button>Solicitar Cita</button>
    </div>
</section>

<footer>
    <h3>Buchaca Sana © 2026</h3>
    <p>Consultorio Dental Profesional</p>
</footer>

<a class="whatsapp"
href="https://wa.me/5215512345678"
target="_blank">
<i class="fab fa-whatsapp"></i>
</a>

<script>
let total = 0;

function agregarProducto(nombre, precio){

    const lista =
    document.getElementById("lista-carrito");

    const item =
    document.createElement("li");

    item.textContent =
    `${nombre} - $${precio}`;

    lista.appendChild(item);

    total += precio;

    document.getElementById("total")
    .textContent = total;
}
</script>

</body>
</html>
