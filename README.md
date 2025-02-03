<!DOCTYPE html>
<html lang="fr" data-theme="light">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2I Solutions - Expert en Solutions IT Sécurisées</title>
    <meta name="description" content="2I Solutions déploie des solutions sécurisées en systèmes, réseaux, cloud, sauvegarde, vidéosurveillance et téléphonie IP en Tunisie">
    
    <!-- Stylesheets -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css">
    
    <style>
        :root {
            --primary-blue: #0A192F;
            --cyber-green: #64FFDA;
            --accent-orange: #FF6B6B;
            --dark-bg: #020C1B;
            --light-bg: #F8F9FA;
            --text-dark: #2D3748;
            --text-light: #E2E8F0;
            --gradient-tech: linear-gradient(135deg, #0A192F 0%, #1E3A8A 100%);
            --transition: 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }

        /* Reset et Base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            scroll-padding-top: 100px;
        }

        body {
            background: var(--light-bg);
            color: var(--text-dark);
            font-family: 'Inter', sans-serif;
            line-height: 1.7;
        }

        h1, h2, h3 {
            font-family: 'Space Grotesk', sans-serif;
            margin-bottom: 1.5rem;
        }

        /* Header */
        .main-header {
            background: rgba(10, 25, 47, 0.95);
            padding: 1rem 5%;
            position: fixed;
            width: 100%;
            z-index: 1000;
            backdrop-filter: blur(10px);
        }

        .nav-container {
            max-width: 1400px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            color: white;
            font-size: 1.8rem;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        /* Section Hero */
        .hero-section {
            padding: 180px 5% 100px;
            background: var(--gradient-tech);
            color: white;
            text-align: center;
        }

        .hero-content {
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Section Services */
        .services-section {
            padding: 5rem 5%;
            background: var(--light-bg);
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            max-width: 1400px;
            margin: 0 auto;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            transition: var(--transition);
        }

        .service-icon {
            font-size: 2.5rem;
            color: var(--cyber-green);
            margin-bottom: 1rem;
        }

        /* Section Contact */
        .contact-section {
            padding: 5rem 5%;
            background: var(--primary-blue);
            color: white;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            max-width: 1400px;
            margin: 0 auto;
        }

        /* Footer */
        .main-footer {
            background: var(--dark-bg);
            color: white;
            padding: 3rem 5%;
            text-align: center;
        }

        @media (max-width: 768px) {
            .contact-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="main-header">
        <nav class="nav-container">
            <a href="#" class="logo">
                <i class="fas fa-network-wired"></i>
                2I Solutions
            </a>
            <div class="nav-links">
                <a href="#accueil">Accueil</a>
                <a href="#services">Services</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <!-- Section Accueil -->
    <section id="accueil" class="hero-section">
        <div class="hero-content">
            <h1>Solutions IT Sécurisées pour Votre Entreprise</h1>
            <p class="hero-subtitle">Experts en déploiement de systèmes, réseaux et solutions cloud en Tunisie</p>
            <div class="cta-container">
                <a href="#contact" class="cta-button">Demander un Devis</a>
            </div>
        </div>
    </section>

    <!-- Section Services -->
    <section id="services" class="services-section">
        <h2>Nos Solutions Expertes</h2>
        <div class="services-grid">
            <div class="service-card">
                <i class="service-icon fas fa-cloud"></i>
                <h3>Infrastructure Cloud</h3>
                <p>Solutions cloud hybrides sécurisées et scalables</p>
            </div>
            <div class="service-card">
                <i class="service-icon fas fa-shield-alt"></i>
                <h3>Sécurité Réseau</h3>
                <p>Protection avancée contre les cybermenaces</p>
            </div>
            <div class="service-card">
                <i class="service-icon fas fa-database"></i>
                <h3>Sauvegarde de Données</h3>
                <p>Solutions de sauvegarde et récupération de données</p>
            </div>
            <div class="service-card">
                <i class="service-icon fas fa-video"></i>
                <h3>Vidéosurveillance IP</h3>
                <p>Systèmes de surveillance haute résolution</p>
            </div>
            <div class="service-card">
                <i class="service-icon fas fa-phone-alt"></i>
                <h3>Téléphonie IP</h3>
                <p>Solutions de communication unifiées</p>
            </div>
            <div class="service-card">
                <i class="service-icon fas fa-chalkboard-teacher"></i>
                <h3>Formations</h3>
                <p>Certifications et formations techniques</p>
            </div>
        </div>
    </section>

    <!-- Section Contact -->
    <section id="contact" class="contact-section">
        <div class="contact-grid">
            <div class="contact-info">
                <h2>Notre Siège Social</h2>
                <p><i class="fas fa-map-marker-alt"></i> Ezzahra, Tunisie</p>
                <p><i class="fas fa-phone"></i> +216 25 231 236</p>
                <p><i class="fas fa-envelope"></i> contact@2i-solutions.tn</p>
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d12776.13428621523!2d10.304105!3d36.743684!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12fd48a5fc6e05d5%3A0x4d6d3e9a1a60dcd0!2sEzzahra!5e0!3m2!1sfr!2stn!4v1623930406784!5m2!1sfr!2stn" 
                        width="100%" 
                        height="300" 
                        style="border:0;" 
                        allowfullscreen="" 
                        loading="lazy">
                </iframe>
            </div>
            <div class="contact-form">
                <h2>Contact Rapide</h2>
                <form>
                    <input type="text" placeholder="Nom complet" required>
                    <input type="email" placeholder="Email" required>
                    <input type="tel" placeholder="Téléphone">
                    <textarea rows="5" placeholder="Message" required></textarea>
                    <button type="submit">Envoyer</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="main-footer">
        <p>© 2024 2I Solutions - Tous droits réservés</p>
        <div class="social-links">
            <a href="#"><i class="fab fa-linkedin"></i></a>
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
        </div>
    </footer>

    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 1000,
            once: true
        });
    </script>
</body>
</html>
