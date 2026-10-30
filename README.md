
<!DOCTYPE html>
<html>
<head>
    <title>Ishika Bhatt - Portfolio</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #10172d;
            color: white;
        }

        header {
            background-color: #1c2745;
            padding: 20px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #a5b4fc;
        }

        .home {
            text-align: center;
            padding: 80px 20px;
        }

        .home h1 {
            font-size: 40px;
        }

        .home span {
            color: #a5b4fc;
        }

        .home p {
            font-size: 18px;
        }

        .btn {
            display: inline-block;
            background-color: #818cf8;
            color: black;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 8px;
            margin-top: 15px;
        }

        section {
            padding: 40px 10%;
        }

        h2 {
            color: #a5b4fc;
            text-align: center;
        }

        .box {
            background-color: #1c2745;
            padding: 25px;
            margin: 15px 0;
            border-radius: 10px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }

        .skills div {
            background-color: #1c2745;
            padding: 20px;
            border-radius: 8px;
            min-width: 100px;
            text-align: center;
        }

        footer {
            background-color: #1c2745;
            text-align: center;
            padding: 20px;
        }

        @media(max-width: 600px) {
            nav a {
                display: inline-block;
                margin: 7px;
            }
        }
    </style>
</head>

<body>

<!-- HEADER -->
<header>
    <h1>Ishika Bhatt</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HOME -->
<section class="home" id="home">
    <h1>Hello, I'm <span>Ishika Bhatt</span></h1>
    <h3>BCA Student | Aspiring Web Developer</h3>

    <p>
        Welcome to my personal portfolio website.
        I love learning technology and creating websites.
    </p>

    <a href="#about" class="btn">Know More</a>
</section>

<!-- ABOUT -->
<section id="about">
    <h2>About Me</h2>

    <div class="box">
        <p>
            I am a BCA student interested in web development,
            programming and technology. I enjoy learning new
            skills and creating creative projects.
            My goal is to become a successful IT professional.
        </p>
    </div>
</section>

<!-- EDUCATION -->
<section id="education">
    <h2>My Education</h2>

    <div class="box">
        <h3>Bachelor of Computer Applications (BCA)</h3>
        <p>Currently Pursuing - Semester 3</p>
    </div>
</section>

<!-- SKILLS -->
<section id="skills">
    <h2>My Skills</h2>

    <div class="skills">
        <div>HTML</div>
        <div>CSS</div>
        <div>JavaScript</div>
        <div>C</div>
        <div>C++</div>
        <div>GitHub</div>
    </div>
</section>

<!-- PROJECTS -->
<section id="projects">
    <h2>My Projects</h2>

    <div class="box">
        <h3>My First Website</h3>
        <p>A beginner website created using HTML.</p>
        <a href="https://github.com/bhattishika2307-stack/My---first---Webpage"
           target="_blank">View Project</a>
    </div>

    <div class="box">
        <h3>My First Webpage</h3>
        <p>A creative webpage development project.</p>
        <a href="https://github.com/bhattishika2307-stack/My--first--webpage"
           target="_blank">View Project</a>
    </div>
</section>

<!-- CONTACT -->
<section id="contact">
    <h2>Contact Me</h2>

    <div class="box">
        <p><b>Name:</b> Ishika Bhatt</p>
        <p><b>GitHub:</b>
            <a href="https://github.com/bhattishika2307-stack"
               target="_blank">Visit GitHub</a>
        </p>
        <p><b>LinkedIn:</b>
            <a href="https://www.linkedin.com/"
               target="_blank">Visit LinkedIn</a>
        </p>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Ishika Bhatt | My Personal Portfolio</p>
    <p>Designed using HTML and CSS</p>
</footer>

</body>
</html>

