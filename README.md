
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ishika Bhatt | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0b1020;
            color: white;
            line-height: 1.6;
        }

        header {
            background: #121a2e;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h2 {
            color: #8b9cff;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        nav a:hover {
            color: #8b9cff;
        }

        .home {
            min-height: 85vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px 20px;
        }

        .home h1 {
            font-size: 45px;
            margin-bottom: 15px;
        }

        .home span {
            color: #8b9cff;
        }

        .home p {
            color: #aab5ce;
            font-size: 18px;
            margin-bottom: 25px;
        }

        .btn {
            display: inline-block;
            background: #8b9cff;
            color: #10172d;
            padding: 12px 25px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 60px 10%;
        }

        h2 {
            color: #8b9cff;
            margin-bottom: 20px;
            text-align: center;
        }

        .about, .skill, .project, .contact {
            background: #121a2e;
            padding: 25px;
            margin: 15px 0;
            border-radius: 12px;
            border: 1px solid #273451;
        }

        .about p, .project p, .contact p {
            color: #aab5ce;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }

        .skill {
            text-align: center;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
        }

        .project a {
            display: inline-block;
            margin-top: 12px;
            color: #8b9cff;
            text-decoration: none;
        }

        .contact {
            text-align: center;
        }

        footer {
            background: #121a2e;
            text-align: center;
            padding: 20px;
            color: #aab5ce;
        }

        @media (max-width: 650px) {
            header {
                flex-direction: column;
                gap: 12px;
            }

            nav a {
                margin: 5px;
                font-size: 14px;
            }

            .home h1 {
                font-size: 32px;
            }

            .skills, .projects {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>

<body>

    <!-- Navigation -->
    <header>
        <h2>IB Portfolio</h2>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Home Section -->
    <section class="home" id="home">
        <div>
            <h1>Hi, I'm <span>Ishika Bhatt</span></h1>

            <p>
                BCA Student | Aspiring Web Developer
                <br>
                Learning, Creating and Growing.
            </p>

            <a href="#projects" class="btn">
                View My Projects
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>

        <div class="about">
            <p>
                Hello! I am Ishika Bhatt, a BCA student
                interested in web development and programming.

                I enjoy learning new technologies and creating
                simple and creative websites. I am improving
                my technical skills through practical projects.
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>

        <div class="skills">

            <div class="skill">
                <h3>HTML</h3>
                <p>Webpage Structure</p>
            </div>

            <div class="skill">
                <h3>CSS</h3>
                <p>Webpage Designing</p>
            </div>

            <div class="skill">
                <h3>GitHub</h3>
                <p>Project Management</p>
            </div>

        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>

        <div class="projects">

            <div class="project">
                <h3>My First Webpage</h3>

                <p>
                    My beginner HTML webpage project.
                </p>

                <a href="https://github.com/bhattishika2307-stack/My--first--webpage"
                   target="_blank">
                    View Project
                </a>
            </div>

            <div class="project">
                <h3>My First Website</h3>

                <p>
                    A simple website created using HTML.
                </p>

                <a href="https://github.com/bhattishika2307-stack/My---first---Webpage"
                   target="_blank">
                    View Project
                </a>
            </div>

        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>

        <div class="contact">
            <p>
                Thank you for visiting my portfolio!
            </p>

            <br>

            <a href="https://github.com/bhattishika2307-stack"
               target="_blank" class="btn">
                Visit My GitHub
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>
            © 2026 Ishika Bhatt | Personal Portfolio
        </p>
    </footer>

</body>
</html>
