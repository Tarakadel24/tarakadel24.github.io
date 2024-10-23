<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="Homepage of Tara Prasad Sharma, a mathematics educator and researcher specializing in Pure Mathematics, Analysis, Algebra, and more.">
    <meta name="keywords" content="Mathematics, Education, Research, Pure Mathematics, Algebra, Analysis">
    <title>Tara Prasad Sharma - Homepage</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Merriweather&display=swap" rel="stylesheet">

    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #2C3E50;
            transition: background-color 0.5s, color 0.5s;
        }

        header {
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            background-color: #2C3E50;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            color: white;
            margin-left: 20px;
            font-size: 24px;
            font-family: 'Merriweather', serif;
        }

        nav {
            margin-right: 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            transition: color 0.3s, text-decoration 0.3s;
        }

        nav a:hover {
            text-decoration: underline;
            color: #1abc9c;
        }

        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: 120px auto 30px;
            background-color: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 12px;
            transition: background-color 0.5s;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #2C3E50;
            color: white;
            position: relative;
            width: 100%;
            bottom: 0;
        }

        .section-title {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #2980B9;
            font-family: 'Merriweather', serif;
        }

        p,
        ul {
            line-height: 1.6;
        }

        .cv-button {
            display: inline-block;
            padding: 12px 24px;
            background-color: #1abc9c;
            color: white;
            font-size: 16px;
            font-weight: 600;
            border-radius: 8px;
            text-decoration: none;
            transition: background-color 0.3s ease, transform 0.2s ease;
            cursor: pointer;
        }

        .cv-button:hover {
            background-color: #16a085;
            transform: scale(1.05);
        }

        .dark-mode-toggle {
            display: inline-block;
            padding: 10px 20px;
            background-color: #2980B9;
            color: white;
            font-size: 14px;
            font-weight: 600;
            border-radius: 8px;
            text-decoration: none;
            cursor: pointer;
            margin-left: 15px;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }

        .dark-mode-toggle:hover {
            background-color: #3498DB;
            transform: scale(1.05);
        }

        /* Dark Mode */
        .dark-mode {
            background-color: #2C3E50;
            color: #ecf0f1;
        }

        .dark-mode section {
            background-color: #34495E;
        }

        .dark-mode nav a {
            color: #ecf0f1;
        }

        .dark-mode nav a:hover {
            color: #1abc9c;
        }

        /* Responsive Image */
        .profile-image {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                align-items: flex-start;
            }

            nav {
                margin: 10px 0;
            }

            section {
                padding: 40px 15px;
            }

            .section-title {
                font-size: 1.5rem;
            }

            .cv-button {
                width: 100%;
                text-align: center;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>Tara Prasad Sharma</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#research">Research</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>
        <div class="toggle-container">
            <button class="dark-mode-toggle" onclick="toggleDarkMode()">Toggle Dark Mode</button>
        </div>
    </header>

    <section id="about">
        <h2 class="section-title">About Me</h2>
        <div style="display: flex; align-items: center;">
            <div style="flex: 1;">
                <p>Welcome! I am Tara Prasad Sharma, a mathematics educator and researcher with a passion for Pure Mathematics. My interests include analysis, algebra, and mathematical biology. I strive to inspire students and contribute to the field of mathematics.</p>
            </div>
            <div style="flex: 1; padding-left: 10px;">
                <img src="tara_prasad_sh.jpeg" alt="Tara Prasad Sharma" class="profile-image">
            </div>
        </div>
    </section>

    <section id="research">
        <h2 class="section-title">Research Interests</h2>
        <ul>
            <li><strong>Mathematical Analysis:</strong> Real and functional analysis.</li>
            <li><strong>Algebra:</strong> Focused on algebraic structures and their applications.</li>
            <li><strong>Topology:</strong> Specialized in Stone-Cech Compactification.</li>
            <li><strong>Mathematical Biology/Biostatistics:</strong> Applying mathematics to healthcare and epidemiology through computational models.</li>
        </ul>
    </section>

    <section id="portfolio">
        <h2 class="section-title">My Work</h2>
        <p>Here are some of my projects and publications:</p>
        <ul>
            <li><a href="link-to-your-publication" target="_blank">Title of Publication 1</a></li>
            <li><a href="link-to-your-project" target="_blank">Title of Project 1</a></li>
        </ul>
        <h3>Curriculum Vitae</h3>
        <a href="Tara_Prasad_Sharma_CV.pdf" class="cv-button" target="_blank">Download CV</a>
    </section>

    <section id="contact">
        <h2 class="section-title">Contact</h2>
        <p>If you have any questions, feel free to contact me at: <a href="mailto:tpsharma2024@outlook.com">tpsharma2024@outlook.com</a> or call <a href="tel:+918906053358">+91 89060 53358</a>.</p>
    </section>

    <footer>
        <p>&copy; 2024 Tara Prasad Sharma. All Rights Reserved.</p>
    </footer>

    <script>
        function toggleDarkMode() {
            document.body.classList.toggle("dark-mode");
        }
    </script>
</body>

</html>
