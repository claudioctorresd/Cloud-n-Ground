<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cloud n Ground — Claridad que conecta</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif;
            line-height: 1.6;
            color: #3e3e3e;
            background: #ffffff;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 24px;
        }

        /* Hero Section */
        .hero {
            min-height: 85vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 80px 0 60px;
        }

        .logo {
            width: 280px;
            height: auto;
            margin-bottom: 40px;
        }

        .hero-content h1 {
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 16px;
            letter-spacing: -0.02em;
        }

        .hero-content h1 .cloud {
            color: #0099cc;
        }

        .hero-content h1 .ground {
            color: #3e3e3e;
        }

        .hero-content .tagline {
            font-size: 1.5rem;
            color: #8bc34a;
            font-weight: 500;
            margin-bottom: 32px;
            text-transform: uppercase;
            letter-spacing: 0.05em;
        }

        .hero-content .description {
            font-size: 1.125rem;
            color: #666;
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.7;
        }

        /* Services Section */
        .services {
            padding: 80px 0;
            background: #f8f9fa;
        }

        .services h2 {
            font-size: 2rem;
            margin-bottom: 48px;
            text-align: center;
            font-weight: 600;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 40px;
            max-width: 900px;
            margin: 0 auto;
        }

        .service-item {
            text-align: left;
        }

        .service-item h3 {
            font-size: 1.25rem;
            margin-bottom: 12px;
            font-weight: 600;
            color: #1a1a1a;
        }

        .service-item p {
            color: #666;
            line-height: 1.6;
        }

        /* CTA Section */
        .cta {
            padding: 80px 0;
            text-align: center;
        }

        .cta h2 {
            font-size: 2rem;
            margin-bottom: 24px;
            font-weight: 600;
        }

        .cta p {
            font-size: 1.125rem;
            color: #666;
            margin-bottom: 32px;
        }

        .cta-button {
            display: inline-block;
            padding: 16px 40px;
            background: #0066ff;
            color: #ffffff;
            text-decoration: none;
            border-radius: 8px;
            font-weight: 500;
            font-size: 1.125rem;
            transition: background 0.2s ease;
        }

        .cta-button:hover {
            background: #0052cc;
        }

        /* Footer */
        footer {
            padding: 40px 0;
            text-align: center;
            color: #666;
            font-size: 0.9rem;
            border-top: 1px solid #e5e5e5;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .hero-content h1 {
                font-size: 2.5rem;
            }

            .hero-content .tagline {
                font-size: 1.25rem;
            }

            .hero-content .description {
                font-size: 1rem;
            }

            .services h2,
            .cta h2 {
                font-size: 1.75rem;
            }

            .services {
                padding: 60px 0;
            }

            .cta {
                padding: 60px 0;
            }

            .services-grid {
                gap: 32px;
            }
        }

        @media (max-width: 480px) {
            .hero-content h1 {
                font-size: 2rem;
            }

            .hero {
                min-height: 70vh;
                padding: 60px 0 40px;
            }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <h1>Cloud n Ground</h1>
                <p class="tagline">Datos claros, decisiones reales</p>
                <p class="description">
                    Conectamos tus sistemas en la nube con la operación diaria de tu negocio. Integración, BI y automatización que funcionan.
                </p>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services">
        <div class="container">
            <h2>Qué hacemos</h2>
            <div class="services-grid">
                <div class="service-item">
                    <h3>Integración de sistemas</h3>
                    <p>Hacemos que tus herramientas hablen entre sí. CRM, ERP, bases de datos y servicios cloud trabajando como uno solo.</p>
                </div>
                <div class="service-item">
                    <h3>Business Intelligence</h3>
                    <p>Transformamos datos dispersos en reportes claros. Dashboards que muestran lo que necesitas saber para decidir.</p>
                </div>
                <div class="service-item">
                    <h3>Automatización</h3>
                    <p>Eliminamos trabajo manual repetitivo. Procesos que se ejecutan solos, liberando tiempo para lo que realmente importa.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="cta">
        <div class="container">
            <h2>Trabajemos juntos</h2>
            <p>¿Tienes un proyecto en mente? Conversemos.</p>
            <a href="mailto:contacto@cloudnground.com" class="cta-button">contacto@cloudnground.com</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>Cloud n Ground · Chile · 2025</p>
        </div>
    </footer>
</body>
</html>
