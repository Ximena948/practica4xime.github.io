<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jabones Artesanales Naturales | Aromas del Alma</title>
    <style>
        /* Estilos CSS */
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f9f5f0;
        }
        
        header {
            background-color: #8d6e63;
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        nav {
            background-color: #a1887f;
            padding: 1rem;
        }
        
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            padding: 0;
        }
        
        nav li {
            margin: 0 1rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .hero {
            background-image: url('https://images.unsplash.com/photo-1600166898405-da9535204843');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            margin-bottom: 2rem;
        }
        
        .hero-content {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 2rem;
            border-radius: 10px;
        }
        
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }
        
        .product-card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
        }
        
        .product-img {
            height: 200px;
            background-size: cover;
            background-position: center;
        }
        
        .product-info {
            padding: 1.5rem;
        }
        
        .btn {
            display: inline-block;
            background-color: #8d6e63;
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            text-decoration: none;
            margin-top: 1rem;
        }
        
        footer {
            background-color: #5d4037;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }
        
        .benefits {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin: 2rem 0;
        }
        
        .benefit {
            flex-basis: 30%;
            text-align: center;
            margin-bottom: 2rem;
        }
        
        @media (max-width: 768px) {
            .benefit {
                flex-basis: 100%;
            }
            
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav li {
                margin: 0.5rem 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>¨ESCENCIAS NATURALES EN TU PIEL¨</h1>
            <p>Jabones artesanales creados con amor ,ideales para consentir tu piel con ingredientes naturales y fragancias unicas.</p>
        </div>
    </header>
    
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#productos">Productos</a></li>
            <li><a href="#beneficios">Beneficios</a></li>
            <li><a href="#nosotros">Nosotros</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    
    <section id="inicio" class="hero">
        <div class="hero-content">
            <h2>Descubre el placer de cuidar tu piel</h2>
            <p>Elaborados con ingredientes naturales, sin químicos agresivos</p>
            <a href="#productos" class="btn">Ver productos</a>
        </div>
    </section>
    
    <div class="container">
        <section id="beneficios">
            <h2>Beneficios de nuestros jabones</h2>
            <div class="benefits">
                <div class="benefit">
                    <h3>🌿 100% Naturales</h3>
                    <p>Hechos con ingredientes de origen natural, sin parabenos ni sulfatos.</p>
                </div>
                <div class="benefit">
                    <h3>🧴 Hidratación profunda</h3>
                    <p>Mantienen la humedad natural de tu piel gracias a sus aceites esenciales.</p>
                </div>
                <div class="benefit">
                    <h3>🌎 Eco-friendly</h3>
                    <p>Embalaje biodegradable y procesos de producción sostenibles.</p>
                </div>
            </div>
        </section>
        
        <section id="productos">
            <h2>Nuestra Colección de Jabones</h2>
            <div class="product-grid">
                <div class="product-card">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1594035910387-fea47794261f');"></div>
                    <div class="product-info">
                        <h3>Jabón de Lavanda</h3>
                        <p>Relajante y calmante, perfecto para antes de dormir.</p>
                        <p class="price">$8.99</p>
                        <a href="#" class="btn">Añadir al carrito</a>
                    </div>
                </div>
                
                <div class="product-card">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1600857544200-b2f666a9a2ec');"></div>
                    <div class="product-info">
                        <h3>Jabón de Carbón Activado</h3>
                        <p>Purifica y desintoxica la piel, ideal para pieles mixtas y grasas.</p>
                        <p class="price">$9.99</p>
                        <a href="#" class="btn">Añadir al carrito</a>
                    </div>
                </div>
                
                <div class="product-card">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1600166898405-da9535204843');"></div>
                    <div class="product-info">
                        <h3>Jabón de Miel y Avena</h3>
                        <p>Nutre y suaviza la piel, excelente para pieles sensibles.</p>
                        <p class="price">$8.99</p>
                        <a href="#" class="btn">Añadir al carrito</a>
                    </div>
                </div>
                
                <div class="product-card">
                    <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-15972590324816-1df6aee575d0');"></div>
                    <div class="product-info">
                        <h3>Jabón de Romero y Menta</h3>
                        <p>Energizante y refrescante, ideal para empezar el día.</p>
                        <p class="price">$9.49</p>
                        <a href="#" class="btn">Añadir al carrito</a>
                    </div>
                </div>
            </div>
        </section>
        
        <section id="nosotros">
            <h2>Sobre Nosotros</h2>
            <p>En <strong>Aromas del Alma</strong> comenzamos como un pequeño emprendimiento familiar en 2015, con la misión de crear productos de cuidado personal que respeten tanto la piel como el medio ambiente.</p>
            <p>Cada jabón es elaborado a mano en pequeños lotes, utilizando el método tradicional de saponificación en frío que preserva las propiedades beneficiosas de los aceites esenciales y botánicos que utilizamos.</p>
            <p>Nos enorgullece decir que todos nuestros ingredientes son de origen sostenible y trabajamos directamente con productores locales siempre que es posible.</p>
        </section>
        
        <section id="contacto">
            <h2>Contacto</h2>
            <p>¿Tienes preguntas o quieres hacer un pedido especial? Escríbenos:</p>
            <form>
                <div style="margin-bottom: 1rem;">
                    <label for="nombre">Nombre:</label><br>
                    <input type="text" id="nombre" name="nombre" style="width: 100%; padding: 0.5rem;">
                </div>
                <div style="margin-bottom: 1rem;">
                    <label for="email">Email:</label><br>
                    <input type="email" id="email" name="email" style="width: 100%; padding: 0.5rem;">
                </div>
                <div style="margin-bottom: 1rem;">
                    <label for="mensaje">Mensaje:</label><br>
                    <textarea id="mensaje" name="mensaje" rows="5" style="width: 100%; padding: 0.5rem;"></textarea>
                </div>
                <button type="submit" class="btn">Enviar mensaje</button>
            </form>
        </section>
    </div>
    
    <footer>
        <div class="container">
            <p>&copy; 2023 Aromas del Alma - Jabones Artesanales. Todos los derechos reservados.</p>
            <p>Síguenos en redes sociales: 
                <a href="#" style="color: white;">Instagram</a> | 
                <a href="#" style="color: white;">Facebook</a> | 
                <a href="#" style="color: white;">Pinterest</a>
            </p>
        </div>
    </footer>
</body>
</html>
