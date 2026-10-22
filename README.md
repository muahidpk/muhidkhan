
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muhid Khan | My Website</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f4f7fc;
            color: #243447;
        }

        header {
            background: #102b4e;
            color: white;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        header h2 {
            color: #60c7ff;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 18px;
        }

        nav a:hover {
            color: #60c7ff;
        }

        .hero {
            min-height: 390px;
            padding: 90px 8%;
            text-align: center;
            color: white;
            background: linear-gradient(135deg, #102b4e, #1676b8);
        }

        .hero h1 {
            font-size: 44px;
            margin-bottom: 15px;
        }

        .hero span {
            color: #75dcff;
        }

        .hero p {
            font-size: 18px;
            line-height: 1.8;
            margin-bottom: 25px;
        }

        .button {
            display: inline-block;
            background: #60c7ff;
            color: #102b4e;
            padding: 12px 25px;
            border-radius: 7px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 55px 8%;
            text-align: center;
        }

        section h2 {
            color: #102b4e;
            font-size: 30px;
            margin-bottom: 20px;
        }

        .about p {
            max-width: 700px;
            margin: auto;
            line-height: 1.9;
        }

        .cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 25px;
        }

        .card {
            background: white;
            padding: 25px;
            width: 250px;
            border-radius: 12px;
            box-shadow: 0 5px 18px #00000012;
            border-bottom: 4px solid #1682c4;
        }

        .card h3 {
            color: #1676b8;
            margin-bottom: 12px;
        }

        .contact {
            background: #e5eef8;
        }

        .contact p {
            margin: 12px;
        }

        footer {
            background: #102b4e;
            color: white;
            text-align: center;
            padding: 20px;
        }

        @media (max-width: 600px) {
            header {
                justify-content: center;
                text-align: center;
            }

            nav a {
                display: inline-block;
                margin: 8px;
            }

            .hero h1 {
                font-size: 32px;
            }

            .hero {
                padding: 65px 6%;
            }
        }
    </style>
</head>

<body>

    <header>
        <h2>Muhid Khan</h2>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero" id="home">
        <h1>Hello, I'm <span>Muhid Khan</span></h1>
        <p>
            Welcome to my personal website!<br>
            Student | Computer Course Learner | Future IT Professional
        </p>
        <a class="button" href="#about">Explore My Website</a>
    </div>

    <section class="about" id="about">
        <h2>About Me</h2>
        <p>
            My name is Muhid Khan. I am 13 years old and studying
            in Class 6 in Pakistan. I am taking a computer course
            to improve my computer skills. I enjoy learning about
            technology and developing new abilities for my future.
        </p>
    </section>

    <section id="skills">
        <h2>My Learning & Skills</h2>

        <div class="cards">
            <div class="card">
                <h3>💻 Computer Skills</h3>
                <p>I am learning computer basics and how to use technology.</p>
            </div>

            <div class="card">
                <h3>🌐 Web Development</h3>
                <p>I want to learn HTML, CSS and how to build websites.</p>
            </div>

            <div class="card">
                <h3>📚 Education</h3>
                <p>I study in Class 6 and continue to learn new things.</p>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Contact Me</h2>
        <p><strong>Name:</strong> Muhid Khan</p>
        <p><strong>Country:</strong> Pakistan</p>
        <p>Thank you for visiting my website!</p>
        <a class="button" href="#home">Back to Top</a>
    </section>

    <footer>
        <p>&copy; 2026 Muhid Khan | My Personal Website</p>
    </footer>

</body>
</html>
