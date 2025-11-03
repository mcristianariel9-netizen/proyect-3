# proyect-3
curriculum vitae
((curriculum vitae)(<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Cristian Martin</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            max-width: 900px;
            width: 100%;
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 50px 40px;
            text-align: center;
            position: relative;
        }

        .header::after {
            content: '';
            position: absolute;
            bottom: -30px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 100px;
            background: white;
            border-radius: 50%;
            border: 5px solid #667eea;
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
        }

        .name {
            font-size: 2.5em;
            font-weight: 700;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .title {
            font-size: 1.3em;
            font-weight: 300;
            opacity: 0.95;
        }

        .content {
            padding: 60px 40px 40px;
        }

        .section {
            margin-bottom: 35px;
        }

        .section-title {
            color: #667eea;
            font-size: 1.5em;
            font-weight: 600;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 3px solid #667eea;
            display: inline-block;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .info-item {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            padding: 20px;
            border-radius: 12px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .info-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(102, 126, 234, 0.3);
        }

        .info-label {
            color: #764ba2;
            font-weight: 600;
            font-size: 0.9em;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 5px;
        }

        .info-value {
            color: #333;
            font-size: 1.1em;
        }

        .education-item, .skills-item {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 15px;
            border-left: 4px solid #667eea;
            transition: all 0.3s ease;
        }

        .education-item:hover, .skills-item:hover {
            background: #e8ecf1;
            border-left-width: 8px;
        }

        .education-title, .skills-title {
            color: #333;
            font-weight: 600;
            font-size: 1.1em;
            margin-bottom: 8px;
        }

        .education-desc, .skills-desc {
            color: #666;
            line-height: 1.6;
        }

        .download-btn {
            display: inline-block;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 15px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
            margin-top: 30px;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
            cursor: pointer;
            border: none;
        }

        .download-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(102, 126, 234, 0.6);
        }

        .btn-container {
            text-align: center;
            padding: 20px 0;
        }

        @media (max-width: 768px) {
            .name {
                font-size: 1.8em;
            }
            
            .title {
                font-size: 1.1em;
            }
            
            .content {
                padding: 40px 20px;
            }
            
            .info-grid {
                grid-template-columns: 1fr;
            }
        }

        @media print {
            body {
                background: white;
                padding: 0;
            }
            
            .container {
                box-shadow: none;
                max-width: 100%;
            }
            
            .download-btn {
                display: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1 class="name">Cristian Martin</h1>
            <p class="title">Diseñador de Imagen | Marketing Digital</p>
        </div>

        <div class="content">
            <div class="section">
                <h2 class="section-title">Información Personal</h2>
                <div class="info-grid">
                    <div class="info-item">
                        <div class="info-label">Edad</div>
                        <div class="info-value">44 años</div>
                    </div>
                    <div class="info-item">
                        <div class="info-label">Nacionalidad</div>
                        <div class="info-value">Argentino</div>
                    </div>
                    <div class="info-item">
                        <div class="info-label">Domicilio</div>
                        <div class="info-value">Posadas, Misiones</div>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">Perfil Profesional</h2>
                <div class="education-item">
                    <p class="education-desc">
                        Diseñador de imagen con formación en recursos digitales y marketing. Profesional creativo con habilidades en diseño visual y estrategias de comunicación digital. Orientado al desarrollo de soluciones creativas e innovadoras.
                    </p>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">Educación</h2>
                <div class="education-item">
                    <div class="education-title">📚 Secundario Completo</div>
                    <div class="education-desc">Educación secundaria finalizada</div>
                </div>
                <div class="education-item">
                    <div class="education-title">🎓 Recursos Digitales y Marketing</div>
                    <div class="education-desc">Actualmente cursando la carrera</div>
                </div>
            </div>

            <div class="section">
                <h2 class="section-title">Habilidades y Competencias</h2>
                <div class="skills-item">
                    <div class="skills-title">💼 Diseño de Imagen</div>
                    <div class="skills-desc">Creación y desarrollo de identidad visual para marcas y proyectos</div>
                </div>
                <div class="skills-item">
                    <div class="skills-title">🌐 Marketing Digital</div>
                    <div class="skills-desc">Conocimientos en estrategias digitales y gestión de recursos online</div>
                </div>
                <div class="skills-item">
                    <div class="skills-title">🌍 Idiomas</div>
                    <div class="skills-desc">Portugués - Nivel Básico</div>
                </div>
            </div>

            <div class="btn-container">
                <button class="download-btn" onclick="descargarPDF()">📥 Descargar CV en PDF</button>
            </div>
        </div>
    </div>

    <script>
        function descargarPDF() {
            window.print();
        }
    </script>
</body>
</html>
