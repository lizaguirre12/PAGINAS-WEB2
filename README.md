
HTML

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Ana Torres Luna</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="cv-container">
        <aside class="sidebar">
            <div class="profile-img-container">
                <img src="CV/foto.jpg" alt="Ana Torres Luna" class="profile-img">
            </div>

            <div class="sidebar-content">
                <section class="contact">
                    <h3>CONTACT</h3>
                    <div class="contact-item">
                        <img src="CV/pin.png" class="icon"> 
                        <p>Calle Obregón 10780000 Culiacán</p>
                    </div>
                    <div class="contact-item">
                        <img src="CV/phone.png" class="icon"> 
                        <p>667.713-1126</p>
                    </div>
                    <div class="contact-item">
                        <img src="CV/mail.png" class="icon"> 
                        <p>ana.tl@example.com</p>
                    </div>
                </section>

                <hr>

                <section class="skills">
                    <h3>HABILIDADES</h3>
                    <ul>
                        <li>Entrenamiento personal</li>
                        <li>Animación deportiva</li>
                        <li>Coordinación de actividades</li>
                        <li>Programas de ejercicio</li>
                        <li>Habilidades interpersonales</li>
                        <li>Simpatía y amabilidad</li>
                    </ul>
                </section>

                <hr>

                <section class="courses">
                    <h3>CURSOS</h3>
                    <p><strong>Entrenamiento Personal</strong> - Editorial Médica Panamericana, 2020</p>
                    <p><strong>Pilates</strong> - Instituto Superior de Artes Escena 3, 2019</p>
                </section>

                <hr>

                <section class="certifications">
                    <h3>CERTIFICACION</h3>
                    <ul>
                        <li>Certificación Internacional en Indoor Cycling - Bike Live, 2017</li>
                        <li>Certificación en "Instructor Especializado en Gimnasio y Musculación" - CEDPRO, 2015</li>
                    </ul>
                </section>
            </div>
        </aside>

        <main class="main-content">
            <header class="header-blue">
                <h1>Ana Torres Luna</h1>
                <p class="summary">
                    Instructora de gimnasio con experiencia en acondicionamiento físico. 
                    Soy una persona enérgica con habilidad para ayudar a los demás a alcanzar 
                    sus objetivos de entrenamiento mediante sesiones personalizadas. 
                    Busco unirme a un equipo dinámico y motivado.
                </p>
            </header>

            <section class="experience">
                <h2>EXPERIENCIA LABORAL</h2>

                <div class="job">
                    <p><strong>FIT ZONE - Instructora de gimnasio</strong></p>
                    <p class="date">Culiacán | 11/2020 - Actual</p>
                    <ul>
                        <li>Asesoramiento e información al usuario sobre la práctica deportiva y la adopción de hábitos de vida saludables.</li>
                        <li>Mantenimiento y limpieza de máquinas, materiales y espacio de trabajo.</li>
                        <li>Organización y dirección de diferentes tipos de actividades deportivas (aerobic, zumba, spinning, etc.).</li>
                    </ul>
                </div>

                <div class="job">
                    <p><strong>Champions Gym - Instructora de gimnasio</strong></p>
                    <p class="date">Culiacán | 01/2016 - 03/2020</p>
                    <ul>
                        <li>Prevención y tratamiento básico de lesiones deportivas.</li>
                        <li>Información y orientación al usuario sobre cómo utilizar el material deportivo, las máquinas, etc.</li>
                        <li>Planificación y elaboración de calendarios y horarios de sesiones.</li>
                    </ul>
                </div>

                <div class="job">
                    <p><strong>Dalia Fitness - Monitora de zumba</strong></p>
                    <p class="date">Culiacán | 03/2011 - 10/2015</p>
                    <ul>
                        <li>Planificación y diseño de clases de zumba adaptadas a diferentes niveles y edades.</li>
                        <li>Adaptación de las clases a las necesidades específicas de alumnos con discapacidades o lesiones.</li>
                        <li>Mantenimiento y actualización de conocimientos sobre zumba y otras disciplinas.</li>
                    </ul>
                </div>
            </section>

            <hr class="full-hr">

            <section class="education">
                <h2>ESTUDIOS</h2>
                <p><strong>Universidad Autónoma de Sinaloa</strong>, Culiacán | 06/2010</p>
                <p><em>Licenciatura en Educación Deportiva</em></p>
            </section>
        </main>
    </div>

</body>
</html>
Código CSS (style.css)
CSS

/* Configuración General */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    background-color: #f0f0f0;
    color: #333;
    line-height: 1.5;
}

.cv-container {
    width: 210mm; /* Tamaño A4 aproximado */
    min-height: 297mm;
    margin: 20px auto;
    background: white;
    display: flex;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Sidebar Izquierdo */
.sidebar {
    width: 35%;
    background-color: #dee8ef; /* Azul grisáceo claro de la imagen */
}

.profile-img-container {
    width: 100%;
    height: 250px;
}

.profile-img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ajusta la imagen sin deformarla */
}

.sidebar-content {
    padding: 30px 20px;
}

h3 {
    font-size: 1.1rem;
    margin-bottom: 15px;
    letter-spacing: 1px;
}

.contact-item {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
    font-size: 0.9rem;
}

.icon {
    width: 18px;
    height: 18px;
    margin-right: 10px;
}

hr {
    border: 0;
    border-top: 1px solid #99a;
    margin: 20px 0;
}

ul {
    list-style: none;
    padding-left: 0;
}

.skills li, .certifications li {
    margin-bottom: 8px;
    font-size: 0.9rem;
}

.skills li::before {
    content: "• ";
    color: #333;
}

/* Columna Derecha */
.main-content {
    width: 65%;
}

.header-blue {
    background-color: #5b8ba1; /* Azul petróleo de la cabecera */
    color: white;
    padding: 40px;
}

.header-blue h1 {
    font-size: 3rem;
    margin-bottom: 20px;
    font-weight: 700;
}

.summary {
    font-size: 0.95rem;
    font-weight: 300;
}

.experience, .education {
    padding: 30px 40px;
}

h2 {
    font-size: 1.2rem;
    margin-bottom: 20px;
    color: #222;
}

.job {
    margin-bottom: 25px;
}

.date {
    font-size: 0.85rem;
    color: #666;
    margin: 5px 0 10px 0;
}

.experience ul {
    list-style: disc;
    padding-left: 20px;
    font-size: 0.9rem;
}

.full-hr {
    margin: 0 40px;
    border-top: 1px solid #ccc;
}

