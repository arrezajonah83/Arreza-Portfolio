

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Jonah Alea Arreza | Web Portfolio</title>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- CSS -->
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Navigation -->
    <header class="navbar">
        <div class="logo"><span>J</span>onah.</div>

        <nav class="nav-links">
            <a href="#home">Home</a>
            <a href="#about">About Me</a>
            <a href="#activities">Course Activities</a>
            <a href="#contact">Contact</a>
        </nav>

        <a href="#contact" class="btn-cta">Let's Talk</a>
    </header>

    <!-- Home Section -->
    <section id="home" class="hero-section">
        <div class="hero-container">

            <div class="hero-content">
                <span class="greeting">WELCOME TO MY PORTFOLIO</span>

                <h1>
                    Hi, I'm <span>Jonah Alea Arreza</span>
                </h1>

                <h3>Frontend Developer & Tech Enthusiast</h3>

                <p>
                    Passionate about crafting intuitive, responsive web
                    experiences and translating creative concepts into
                    functional digital solutions.
                </p>

                <div class="cta-group">
                    <a href="#contact" class="btn btn-primary">Hire Me</a>
                    <a href="#activities" class="btn btn-secondary">View Work</a>
                </div>

                <!-- Social Links -->
                <div class="social-links">
                    <a href="https://github.com/arrezajonah83"
                       target="_blank"
                       rel="noopener noreferrer"
                       aria-label="GitHub">
                        <i class="fa-brands fa-github"></i>
                    </a>

                    <a href="mailto:arrezajonah83@gmail.com"
                       aria-label="Email">
                        <i class="fa-solid fa-envelope"></i>
                    </a>

                    <a href="https://www.facebook.com/exclamation.point.165"
                       target="_blank"
                       rel="noopener noreferrer"
                       aria-label="Facebook">
                        <i class="fa-brands fa-facebook-f"></i>
                    </a>
                </div>
            </div>

            <!-- Profile Picture -->
            <div class="hero-image-container">
                <div class="hero-image-wrapper">
                    <img
                        src="jonah.jpeg"
                        alt="Jonah Alea Arreza"
                        class="hero-profile-img"
                    >
                </div>
            </div>

        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="about-section">
        <div class="about-container">

            <h2 class="section-title-left">About Me</h2>

            <div class="about-content">

                <p class="about-text">
                    Hello! I am <strong>Jonah Alea Arreza</strong>,
                    a dedicated individual and aspiring web developer.
                    I enjoy building clean, functional, and visually
                    appealing web interfaces. I'm constantly learning
                    new web technologies and improving my skills to
                    turn creative ideas into engaging digital experiences.
                </p>

                <div class="about-details-row">

                    <div class="info-group">
                        <p><span>Full Name:</span> Jonah Alea Arreza</p>
                        <p><span>Age:</span> 43</p>
                        <p><span>Birthday:</span> August 28, 1983</p>
                        <p><span>Role:</span> Student / Web Developer</p>
                    </div>

                    <div class="info-group">
                        <p><span>Email:</span> arrezajonah83@gmail.com</p>
                        <p><span>Phone:</span> 09266591188</p>
                        <p><span>Location:</span> Philippines</p>
                    </div>

                </div>

                <div class="about-skills">
                    <h4>Technologies & Skills</h4>

                    <p class="skills-inline">
                        HTML5 • CSS3 • JavaScript • Responsive Design •
                        UI/UX Basics • Git / GitHub
                    </p>
                </div>

            </div>
        </div>
    </section>

    <!-- Course Activities Section -->
    <section id="activities" class="activities-section">

        <h2 class="main-activities-title">Course Activities</h2>

        <!-- Activity Cards -->
        <div class="activity-grid">

            <button class="activity-card" type="button"
                    onclick="showProject('fashion', this)">
                <h4>HTML Practice 1.1</h4>
                <p>Fashion Blog</p>
            </button>

            <button class="activity-card" type="button"
                    onclick="showProject('wine', this)">
                <h4>HTML Practice 1.2</h4>
                <p>Wine Festival Schedule</p>
            </button>

            <button class="activity-card" type="button"
                    onclick="showProject('burger', this)">
                <h4>CSS Practice 1.1</h4>
                <p>Davies Burger</p>
            </button>

        </div>

        <!-- Project Display Area -->
        <div id="project-display-container">

            <!-- Fashion Blog -->
            <div id="project-fashion" class="project-content">
                <div class="activity-preview-wrapper">

                    <a href="https://christene13.github.io/FashionBlog/fashionblog.html"
                       target="_blank"
                       rel="noopener noreferrer"
                       class="external-link-btn">
                        Open Original Page
                        <i class="fa-solid fa-arrow-up-right-from-square"></i>
                    </a>

                    <iframe
                        src="https://christene13.github.io/FashionBlog/fashionblog.html"
                        class="project-iframe"
                        title="Fashion Blog Activity">
                    </iframe>

                </div>
            </div>

            <!-- Wine Festival -->
            <div id="project-wine" class="project-content">
                <div class="activity-preview-wrapper">

                    <a href="https://christene13.github.io/WineFestivalSchedule/index.html"
                       target="_blank"
                       rel="noopener noreferrer"
                       class="external-link-btn">
                        Open Original Page
                        <i class="fa-solid fa-arrow-up-right-from-square"></i>
                    </a>

                    <iframe
                        src="https://christene13.github.io/WineFestivalSchedule/index.html"
                        class="project-iframe"
                        title="Wine Festival Activity">
                    </iframe>

                </div>
            </div>

            <!-- Davies Burger -->
            <div id="project-burger" class="project-content">
                <div class="activity-preview-wrapper">

                    <a href="https://christene13.github.io/DaviesBurger/index.html"
                       target="_blank"
                       rel="noopener noreferrer"
                       class="external-link-btn">
                        Open Original Page
                        <i class="fa-solid fa-arrow-up-right-from-square"></i>
                    </a>

                    <iframe
                        src="https://christene13.github.io/DaviesBurger/index.html"
                        class="project-iframe"
                        title="Davies Burger Activity">
                    </iframe>

                </div>
            </div>

        </div>
    </section>

    <!-- Contact Section -->
    <footer id="contact" class="footer-section">
        <div class="footer-content">

            <h3>Get In Touch</h3>

            <p>
                <strong>Email:</strong>
                <a href="mailto:arrezajonah83@gmail.com">
                    arrezajonah83@gmail.com
                </a>
                |
                <strong>Phone:</strong> 09266591188
            </p>

            <div class="footer-socials">
                <a href="https://github.com/arrezajonah83"
                   target="_blank"
                   rel="noopener noreferrer"
                   aria-label="GitHub">
                    <i class="fa-brands fa-github"></i>
                </a>

                <a href="https://www.facebook.com/exclamation.point.165"
                   target="_blank"
                   rel="noopener noreferrer"
                   aria-label="Facebook">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
            </div>

            <p class="copyright">
                &copy; 2026 Jonah Alea Arreza. All Rights Reserved.
            </p>

        </div>
    </footer>

    <!-- JavaScript -->
    <script>
        function showProject(projectId, cardElement) {

            const selectedProject =
                document.getElementById(`project-${projectId}`);

            const isAlreadyActive =
                selectedProject.classList.contains('active');

            // Hide all projects
            document.querySelectorAll('.project-content')
                .forEach(project => {
                    project.classList.remove('active');
                });

            // Remove active state from all cards
            document.querySelectorAll('.activity-card')
                .forEach(card => {
                    card.classList.remove('active');
                });

            // Toggle selected project
            if (!isAlreadyActive) {
                selectedProject.classList.add('active');
                cardElement.classList.add('active');
            }
        }
    </script>

</body>
</html>
