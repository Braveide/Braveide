## Hi soy  bravonasso felipinchis👋

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cruz Felipe Cruz Bravo - Especialista en Sistemas</title>
    <style>
        :root {
            --primary: #000000;
            --secondary: #e91e63;
            --accent: #ad1457;
            --light: #fce4ec;
            --dark: #212121;
            --gray: #757575;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #fafafa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 60px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .header-content {
            position: relative;
            z-index: 2;
        }
        
        .photo-container {
            width: 200px;
            height: 200px;
            margin: 0 auto 25px;
            border-radius: 50%;
            border: 5px solid white;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
            background-color: #f0f0f0;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .profile-img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .header-content h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
        }
        
        .header-content .title {
            font-size: 1.3rem;
            opacity: 0.9;
            margin-bottom: 20px;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 8px;
            background: rgba(255, 255, 255, 0.2);
            padding: 8px 15px;
            border-radius: 20px;
            backdrop-filter: blur(5px);
        }
        
        /* Section Styles */
        section {
            padding: 60px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            color: var(--primary);
            position: relative;
        }
        
        .section-title:after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: var(--secondary);
            margin: 10px auto;
        }
        
        .card {
            background: white;
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            margin-bottom: 30px;
            border-left: 4px solid var(--secondary);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(233, 30, 99, 0.15);
        }
        
        /* Synthesis Section */
        .synthesis {
            text-align: center;
            font-size: 1.1rem;
            line-height: 1.8;
        }
        
        /* Experience Section */
        .experience-item {
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }
        
        .experience-item:last-child {
            border-bottom: none;
        }
        
        .job-title {
            font-weight: bold;
            color: var(--primary);
            font-size: 1.2rem;
        }
        
        .company {
            color: var(--secondary);
            font-weight: 600;
            margin: 5px 0;
        }
        
        .date {
            color: var(--gray);
            font-style: italic;
            background: var(--light);
            display: inline-block;
            padding: 3px 10px;
            border-radius: 15px;
            font-size: 0.9rem;
        }
        
        .responsibilities {
            margin-top: 15px;
        }
        
        .responsibilities li {
            margin-bottom: 8px;
            position: relative;
            padding-left: 20px;
        }
        
        .responsibilities li:before {
            content: '▸';
            position: absolute;
            left: 0;
            color: var(--secondary);
            font-weight: bold;
        }
        
        /* Skills Section */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .skill-category {
            background: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .skill-category:hover {
            transform: translateY(-5px);
        }
        
        .skill-category h3 {
            color: var(--primary);
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--light);
        }
        
        .skill-list {
            list-style-type: none;
        }
        
        .skill-list li {
            padding: 8px 0;
            border-bottom: 1px dashed #eee;
            position: relative;
            padding-left: 25px;
        }
        
        .skill-list li:before {
            content: '★';
            position: absolute;
            left: 0;
            color: var(--secondary);
        }
        
        .skill-list li:last-child {
            border-bottom: none;
        }
        
        /* Education Section */
        .education-item {
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 1px dashed #eee;
        }
        
        .education-item:last-child {
            border-bottom: none;
        }
        
        .education-title {
            font-weight: bold;
            color: var(--primary);
        }
        
        .education-institution {
            color: var(--secondary);
            margin: 5px 0;
            font-weight: 600;
        }
        
        /* Footer */
        footer {
            background: var(--primary);
            color: white;
            text-align: center;
            padding: 30px 0;
        }
        
        .footer-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 15px;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
        }
        
        .social-link {
            color: white;
            background: var(--secondary);
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            transition: background 0.3s ease;
        }
        
        .social-link:hover {
            background: var(--accent);
            transform: scale(1.1);
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .header-content h1 {
                font-size: 2rem;
            }
            
            .photo-container {
                width: 180px;
                height: 180px;
            }
            
            .contact-info {
                flex-direction: column;
                align-items: center;
                gap: 10px;
            }
            
            .skills-container {
                grid-template-columns: 1fr;
            }
            
            .contact-item {
                padding: 6px 12px;
            }
        }
        
        @media (max-width: 480px) {
            .photo-container {
                width: 150px;
                height: 150px;
            }
            
            .header-content h1 {
                font-size: 1.8rem;
            }
            
            section {
                padding: 40px 0;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="photo-container">
                    <img src="IMG/YO.jpg" alt="Cruz Felipe Cruz Bravo" class="profile-img">
                </div>
                <h1>CRUZ FELIPE CRUZ BRAVO</h1>
                <p class="title">Técnico en Sistemas y Soporte Informático</p>
                <div class="contact-info">
                    <div class="contact-item">
                        <span>📧 Email: (agregar tu email)</span>
                    </div>
                    <div class="contact-item">
                        <span>📱 Teléfono: (agregar tu teléfono)</span>
                    </div>
                    <div class="contact-item">
                        <span>📍 CDMX, México</span>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- Synthesis Section -->
    <section id="synthesis">
        <div class="container">
            <h2 class="section-title">SÍNTESIS PROFESIONAL</h2>
            <div class="card synthesis">
                <p>Soy un profesional de 21 años que tiene como propósito superarse cada día tanto personal como académicamente. Busco mejores oportunidades en la vida mientras desarrollo mi carrera en Ingeniería en Sistemas Computacionales, con el objetivo de aplicar mis conocimientos para un futuro prometedor.</p>
                <p>A lo largo del tiempo he desarrollado la capacidad de manejar y comprender el funcionamiento de diversos sistemas técnicos. Soy un profesional del trabajo técnico con gran dominio de equipos especializados. Me desempeño con rigor en la investigación y resolución de problemas técnicos complejos. Busco un empleo que me permita desarrollar mis cualidades y seguir creciendo profesionalmente.</p>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience">
        <div class="container">
            <h2 class="section-title">EXPERIENCIA LABORAL</h2>
            <div class="card">
                <div class="experience-item">
                    <div class="job-title">TÉCNICO EN SISTEMAS</div>
                    <div class="company">CODAE - BOSQUE DE TLAHUAC CIL FAUSTO, CDMX</div>
                    <div class="date">Mayo 2021 - Presente</div>
                    <ul class="responsibilities">
                        <li>Encargado del área de videovigilancia para las tiendas Elektra</li>
                        <li>Función principal: revisión de cámaras de seguridad y manipulación del servidor</li>
                        <li>Verificación del correcto funcionamiento de cámaras, audio, grabaciones y enfoques</li>
                        <li>Detección y reparación de fallas en el sistema de seguridad</li>
                        <li>Soporte técnico a equipos de computo, resolviendo problemas de hardware y software</li>
                    </ul>
                </div>
                
                <div class="experience-item">
                    <div class="job-title">TÉCNICO ELECTRÓNICO</div>
                    <ul class="responsibilities">
                        <li>Servicio y reparación de equipos electrónicos de consumo doméstico</li>
                        <li>Cambio de piezas y componentes electrónicos dañados</li>
                        <li>Desempeño de labores de mantenimiento preventivo y correctivo en instalaciones</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2 class="section-title">COMPETENCIAS Y HABILIDADES</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Habilidades Técnicas</h3>
                    <ul class="skill-list">
                        <li>Soporte técnico a equipos de computo</li>
                        <li>Mantenimiento de hardware y software</li>
                        <li>Administración de sistemas de videovigilancia</li>
                        <li>Configuración y mantenimiento de servidores</li>
                        <li>Reparación de equipos electrónicos</li>
                        <li>Mantenimiento preventivo y correctivo</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>Habilidades Personales</h3>
                    <ul class="skill-list">
                        <li>Gran capacidad de trabajo</li>
                        <li>Manualidad y responsabilidad</li>
                        <li>Trabajo en equipo</li>
                        <li>Competencias digitales</li>
                        <li>Resolución de problemas técnicos complejos</li>
                        <li>Investigación y análisis</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>Especialidades</h3>
                    <ul class="skill-list">
                        <li>Sistemas de videovigilancia</li>
                        <li>Soporte técnico informático</li>
                        <li>Reparación electrónica</li>
                        <li>Administración de servidores</li>
                        <li>Mantenimiento de equipos de computo</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education">
        <div class="container">
            <h2 class="section-title">ESTUDIOS</h2>
            <div class="card">
                <div class="education-item">
                    <div class="education-title">Ingeniería en Sistemas Computacionales</div>
                    <div class="education-institution">(En curso) - Universidad</div>
                    <p>Actualmente cursando mi carrera universitaria. Aspiro a aprender conocimientos y poder aplicarlos para un buen puesto a futuro.</p>
                </div>
                
                <div class="education-item">
                    <div class="education-title">Certificado en Soporte Técnico a Equipos de Computo</div>
                    <div class="education-institution">CETIS 50 - CDMX</div>
                    <div class="date">Enero 2015 - Julio 2018</div>
                    <p>Completé la preparatoria técnica con especialización en soporte técnico.</p>
                </div>
                
                <div class="education-item">
                    <div class="education-title">Estudios de Secundaria</div>
                    <p>Finalizados con éxito.</p>
                </div>
                
                <div class="education-item">
                    <div class="education-title">Estudios Primarios</div>
                    <p>Finalizados con éxito.</p>
                    <p>Promedio general de calificaciones: 8.5</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <p>&copy; 2023 Cruz Felipe Cruz Bravo - Todos los derechos reservados</p>
                <p>Portafolio Profesional - Técnico en Sistemas</p>
                <div class="social-links">
                    <a href="#" class="social-link">in</a>
                    <a href="#" class="social-link">Git</a>
                    <a href="#" class="social-link">@</a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Efectos de scroll suave
        document.addEventListener('DOMContentLoaded', function() {
            // Animación para las secciones al hacer scroll
            const sections = document.querySelectorAll('section');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, { threshold: 0.1 });
            
            sections.forEach(section => {
                section.style.opacity = '0';
                section.style.transform = 'translateY(20px)';
                section.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
                observer.observe(section);
            });

            // Efecto hover para las tarjetas de habilidades
            const skillCategories = document.querySelectorAll('.skill-category');
            skillCategories.forEach(category => {
                category.addEventListener('mouseenter', function() {
                    this.style.transform = 'translateY(-10px) scale(1.02)';
                });
                
                category.addEventListener('mouseleave', function() {
                    this.style.transform = 'translateY(0) scale(1)';
                });
            });

            // Efecto para los enlaces sociales
            const socialLinks = document.querySelectorAll('.social-link');
            socialLinks.forEach(link => {
                link.addEventListener('mouseenter', function() {
                    this.style.transform = 'scale(1.2) rotate(5deg)';
                });
                
                link.addEventListener('mouseleave', function() {
                    this.style.transform = 'scale(1) rotate(0)';
                });
            });
        });
    </script>
</body>
</html>
