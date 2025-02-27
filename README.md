<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>🖥️ Programadora con mamá | YouTube</title>
    <style>
        :root {
            --primary-color: #6a1b9a;
            --secondary-color: #9c27b0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f3e5f5 0%, #e1bee7 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
        }

        .header {
            text-align: center;
            padding: 2rem;
            background: white;
            border-radius: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 2rem;
        }

        .profile {
            position: relative;
            width: 150px;
            height: 150px;
            margin: 0 auto 1rem;
            border-radius: 50%;
            overflow: hidden;
            border: 4px solid var(--primary-color);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .profile img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .title {
            color: var(--primary-color);
            font-size: 2.5rem;
            margin: 1rem 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }

        .badges {
            display: flex;
            gap: 1rem;
            justify-content: center;
            margin: 2rem 0;
        }

        .badge {
            padding: 0.8rem 1.5rem;
            border-radius: 25px;
            background: var(--secondary-color);
            color: white;
            text-decoration: none;
            transition: transform 0.3s ease;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .badge:hover {
            transform: translateY(-3px);
            background: var(--primary-color);
        }

        .content {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .feature-card {
            background: #f8f9fa;
            padding: 1.5rem;
            border-radius: 10px;
            margin: 1rem 0;
            border-left: 5px solid var(--secondary-color);
            transition: transform 0.3s ease;
        }

        .feature-card:hover {
            transform: translateX(10px);
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #666;
        }

        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        .profile {
            animation: float 3s ease-in-out infinite;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="profile">
                <!-- Reemplaza con tu imagen -->
                <div style="background: #ddd; width:100%; height:100%; display: grid; place-items: center;">
                    <i class="fas fa-camera" style="font-size: 2rem; color: #666;"></i>
                </div>
            </div>
            <h1 class="title">👩💻 Programadora con mamá</h1>
            
            <div class="badges">
                <a href="TU_ENLACE_DE_YOUTUBE" class="badge" target="_blank">
                    <i class="fab fa-youtube"></i> YouTube
                </a>
                <a href="TU_ENLACE_DE_GITHUB" class="badge" target="_blank">
                    <i class="fab fa-github"></i> GitHub
                </a>
            </div>
        </div>

        <div class="content">
            <div class="feature-card">
                <h2>📌 Sobre mí</h2>
                <p>¡Hola! Soy una programadora apasionada que comparte su experiencia combinando la vida de madre con el desarrollo de software. ¡Acompáñame en este viaje de código y crianza!</p>
            </div>

            <div class="feature-card">
                <h2>🎥 Contenido del canal</h2>
                <ul>
                    <li>💡 Tutoriales de programación</li>
                    <li>👩👧 Experiencias tech-maternidad</li>
                    <li>⚡ Tips de productividad</li>
                    <li>🚀 Proyectos prácticos</li>
                </ul>
            </div>

            <div class="feature-card">
                <h2>🛠️ Tecnologías favoritas</h2>
                <div style="display: flex; gap: 1rem; flex-wrap: wrap;">
                    <span style="background: #6a1b9a22; color: var(--primary-color); padding: 0.5rem 1rem; border-radius: 20px;">JavaScript</span>
                    <span style="background: #6a1b9a22; color: var(--primary-color); padding: 0.5rem 1rem; border-radius: 20px;">Python</span>
                    <span style="background: #6a1b9a22; color: var(--primary-color); padding: 0.5rem 1rem; border-radius: 20px;">React</span>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>© 2024 Programadora con mamá - Todos los derechos reservados</p>
    </footer>
</body>
</html>
