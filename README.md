# helmhand<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Helmano | Solución de Lado a Lado</title>
    <style>
        :root {
            --bg-deep: #0f0b1a;
            --bg-card: #171228;
            --border-glow: rgba(168, 85, 247, 0.3);
            --neon-purple: #c084fc;
            --neon-blue: #38bdf8;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
        }
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }
        body {
            background-color: var(--bg-deep);
            color: var(--text-main);
            line-height: 1.6;
            overflow-x: hidden;
        }
        header {
            background: rgba(15, 11, 26, 0.9);
            backdrop-filter: blur(10px);
            padding: 1.5rem 6%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(255, 255, 255, 0.06);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .logo-area h1 {
            font-size: 1.7rem;
            letter-spacing: 0.5px;
            background: linear-gradient(135deg, #ffffff 30%, var(--neon-purple) 70%, var(--neon-blue) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: lowercase;
            font-weight: 700;
        }
        .logo-area span {
            font-size: 0.7rem;
            display: block;
            color: var(--text-muted);
            letter-spacing: 2px;
            text-transform: uppercase;
        }
        nav a {
            color: var(--text-muted);
            text-decoration: none;
            margin-left: 25px;
            font-size: 0.9rem;
            font-weight: 500;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: var(--neon-purple);
        }
        .hero {
            padding: 7rem 6% 5rem 6%;
            text-align: center;
            background: radial-gradient(circle at 50% 20%, rgba(168, 85, 247, 0.08) 0%, rgba(56, 189, 248, 0.03) 40%, transparent 70%);
        }
        .hero h2 {
            font-size: 3.2rem;
            margin-bottom: 1.2rem;
            font-weight: 700;
            letter-spacing: -0.5px;
        }
        .hero h2 span {
            background: linear-gradient(135deg, var(--neon-purple), var(--neon-blue));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .hero p {
            font-size: 1.15rem;
            color: var(--text-muted);
            max-width: 650px;
            margin: 0 auto 2.5rem auto;
        }
        .btn {
            display: inline-block;
            background: linear-gradient(135deg, #7c3aed, #2563eb);
            color: white;
            padding: 0.85rem 2.2rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
            box-shadow: 0 4px 20px rgba(124, 58, 237, 0.3);
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 25px rgba(168, 85, 247, 0.4);
            filter: brightness(1.1);
        }
        .section {
            padding: 5rem 6%;
            max-width: 1200px;
            margin: 0 auto;
        }
        .section-title {
            text-align: center;
            font-size: 2.2rem;
            margin-bottom: 3.5rem;
            font-weight: 600;
        }
        .section-title span {
            color: var(--neon-purple);
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2rem;
        }
        .card {
            background-color: var(--bg-card);
            padding: 2.5rem;
            border-radius: 12px;
            border: 1px solid rgba(255, 255, 255, 0.04);
            position: relative;
            transition: all 0.3s ease;
        }
        .card:hover {
            transform: translateY(-4px);
            border-color: var(--border-glow);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
        }
        .card h3 {
            margin-bottom: 1rem;
            font-size: 1.25rem;
            font-weight: 600;
            color: var(--text-main);
        }
        .card p {
            color: var(--text-muted);
            font-size: 0.95rem;
        }
        footer {
            text-align: center;
            padding: 2.5rem;
            background-color: #090610;
            color: var(--text-muted);
            font-size: 0.85rem;
            border-top: 1px solid rgba(255, 255, 255, 0.04);
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-area">
            <h1>helmano</h1>
            <span>Solución de lado a lado</span>
        </div>
        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#nosotros">Esencia</a>
            <a href="#servicios">Servicios</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <section class="hero" id="inicio">
        <h2>Solución de lado a lado, <span>crecemos juntos.</span></h2>
        <p>Analizamos problemas de lado a lado. Acompañamos a tu empresa con respaldo absoluto, estrategia y soluciones impecables.</p>
        <a href="#contacto" class="btn">Comienza tu proyecto</a>
    </section>

    <section class="section" id="nosotros">
        <h2 class="section-title">Nuestra <span>Esencia</span></h2>
        <div class="grid">
            <div class="card">
                <h3>Análisis Integral</h3>
                <p>Examinamos cada situación desde todos los flancos para dar con la raíz exacta y resolverla de forma definitiva.</p>
            </div>
            <div class="card">
                <h3>Lado a Lado</h3>
                <p>Trabajamos hombro con hombro contigo, asegurando un respaldo incondicional en cada decisión importante de tu negocio.</p>
            </div>
            <div class="card">
                <h3>Eficacia y Solución</h3>
                <p>Transformamos los desafíos complejos en resultados claros, eficientes y medibles para tu tranquilidad.</p>
            </div>
        </div>
    </section>

    <section class="section" id="servicios">
        <h2 class="section-title">Nuestros <span>Servicios</span></h2>
        <div class="grid">
            <div class="card">
                <h3>Dirección y Estrategia</h3>
                <p>Te guiamos paso a paso para estructurar las metas de tu negocio y asegurar un crecimiento sostenido.</p>
            </div>
            <div class="card">
                <h3>Soluciones a la Medida</h3>
                <p>Desarrollamos respuestas adaptadas a tus necesidades operativas para simplificar y potenciar tu día a día.</p>
            </div>
            <div class="card">
                <h3>Acompañamiento Experto</h3>
                <p>Soporte continuo de principio a fin, garantizando que nunca enfrentes los retos corporativos en solitario.</p>
            </div>
        </div>
    </section>

    <section class="section" id="contacto" style="text-align: center;">
        <h2 class="section-title">Hablemos de tu <span>Solución</span></h2>
        <p style="color: var(--text-muted); margin-bottom: 2rem; max-width: 550px; margin-left: auto; margin-right: auto;">¿Tienes un reto empresarial que resolver? Contáctanos y empecemos a trabajar de lado a lado hoy mismo.</p>
        <a href="mailto:contacto@helmano.com" class="btn">Escríbenos directamente</a>
    </section>

    <footer>
        <p>&copy; 2026 Helmano. Todos los derechos reservados. Solución de lado a lado.</p>
    </footer>

</body>
</html>
