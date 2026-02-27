<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <a href="#home" class="logo">Portfolio</a>
            <ul class="nav-menu">
                <li><a href="#home">Accueil</a></li>
                <li><a href="#about">À propos</a></li>
                <li><a href="#skills">Compétences</a></li>
                <li><a href="#projects">Projets</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span class="bar"></span>
                <span class="bar"></span>
                <span class="bar"></span>
            </div>
        </div>
    </nav>

    <!-- Section Accueil -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Bonjour, je suis <span class="highlight">Votre Nom</span></h1>
            <p>Développeur Full Stack & Designer UI/UX</p>
            <div class="hero-buttons">
                <a href="#contact" class="btn primary">Me Contacter</a>
                <a href="#projects" class="btn secondary">Voir mes projets</a>
            </div>
        </div>
    </section>

    <!-- Section À propos -->
    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">À propos de moi</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>Je suis un développeur passionné avec 5 ans d'expérience dans la création d'applications web innovantes. J'aime transformer des idées complexes en solutions simples et élégantes.</p>
                    <p>Diplômé en Informatique de l'Université de Paris, j'ai travaillé avec des startups et des grandes entreprises pour créer des expériences utilisateur exceptionnelles.</p>
                    <div class="about-info">
                        <div class="info-item">
                            <i class="fas fa-map-marker-alt"></i>
                            <span>Paris, France</span>
                        </div>
                        <div class="info-item">
                            <i class="fas fa-envelope"></i>
                            <span>email@exemple.com</span>
                        </div>
                        <div class="info-item">
                            <i class="fas fa-phone"></i>
                            <span>+261 38 31 465 89</span>
                        </div>
                    </div>
                </div>
                <div class="about-image">
                    <img src="https://via.placeholder.com/400" alt="Photo de profil">
                </div>
            </div>
        </div>
    </section>

    <!-- Section Compétences -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">Mes Compétences</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <i class="fab fa-html5"></i>
                    <h3>HTML5</h3>
                    <div class="progress-bar">
                        <div class="progress" style="width: 90%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-css3-alt"></i>
                    <h3>CSS3</h3>
                    <div class="progress-bar">
                        <div class="progress" style="width: 85%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-js"></i>
                    <h3>JavaScript</h3>
                    <div class="progress-bar">
                        <div class="progress" style="width: 80%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-react"></i>
                    <h3>React</h3>
                    <div class="progress-bar">
                        <div class="progress" style="width: 75%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-node"></i>
                    <h3>Node.js</h3>
                    <div class="progress-bar">
                        <div class="progress" style="width: 70%"></div>
                    </div>
                </div>
                <div class="skill-card">
                    <i class="fab fa-python"></i>
                    <h3>Python</h3>
                    <div class="progress-bar">
                        <div class="progress" style="width: 65%"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Projets -->
    <section id="projects" class="projects">
        <div class="container">
            <h2 class="section-title">Mes Projets</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <img src="https://via.placeholder.com/300x200" alt="Projet 1">
                    <div class="project-info">
                        <h3>Application E-commerce</h3>
                        <p>Une plateforme e-commerce complète avec React et Node.js</p>
                        <div class="project-tags">
                            <span>React</span>
                            <span>Node.js</span>
                            <span>MongoDB</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn small">Voir le projet</a>
                            <a href="#" class="btn small github"><i class="fab fa-github"></i> Code</a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <img src="https://via.placeholder.com/300x200" alt="Projet 2">
                    <div class="project-info">
                        <h3>Dashboard Analytics</h3>
                        <p>Tableau de bord interactif avec visualisation de données</p>
                        <div class="project-tags">
                            <span>Vue.js</span>
                            <span>D3.js</span>
                            <span>Firebase</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn small">Voir le projet</a>
                            <a href="#" class="btn small github"><i class="fab fa-github"></i> Code</a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <img src="https://via.placeholder.com/300x200" alt="Projet 3">
                    <div class="project-info">
                        <h3>Application Mobile</h3>
                        <p>Application de fitness avec React Native</p>
                        <div class="project-tags">
                            <span>React Native</span>
                            <span>Redux</span>
                            <span>Firebase</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="btn small">Voir le projet</a>
                            <a href="#" class="btn small github"><i class="fab fa-github"></i> Code</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Section Contact -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Contactez-moi</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Parlons de votre projet</h3>
                    <p>N'hésitez pas à me contacter pour discuter de vos idées ou opportunités de collaboration.</p>
                    <div class="contact-details">
                        <div class="contact-item">
                            <i class="fas fa-envelope"></i>
                            <span>email@exemple.com</span>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-phone"></i>
                            <span>+33 6 12 34 56 78</span>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-map-marker-alt"></i>
                            <span>Paris, France</span>
                        </div>
                    </div>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-github"></i></a>
                        <a href="#"><i class="fab fa-linkedin"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <form class="contact-form">
                    <div class="form-group">
                        <input type="text" placeholder="Votre nom" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Votre email" required>
                    </div>
                    <div class="form-group">
                        <input type="text" placeholder="Sujet">
                    </div>
                    <div class="form-group">
                        <textarea placeholder="Votre message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="btn primary">Envoyer le message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Mon Portfolio. Tous droits réservés.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
