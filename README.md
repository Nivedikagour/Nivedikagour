<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Colorful Portfolio</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            color: #333;
            scroll-behavior: smooth;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        h1, h2, h3 {
            color: #444;
        }

        /* Header Styles */
        header {
            background: linear-gradient(45deg, #ff8a00, #e52e71);
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline-block;
            margin: 0 20px;
        }

        nav ul li a {
            color: white;
            font-weight: bold;
            text-transform: uppercase;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #ffdd00;
        }

        /* Section Styles <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Colorful Portfolio</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            color: #333;
            scroll-behavior: smooth;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        h1, h2, h3 {
            color: #444;
        }

        /* Header Styles */
        header {
            background: linear-gradient(45deg, #ff8a00, #e52e71);
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline-block;
            margin: 0 20px;
        }

        nav ul li a {
            color: white;
            font-weight: bold;
            text-transform: uppercase;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #ffdd00;
        }

        /* Section Styles */
*/
        section {
            margin: 50px auto;
            max-width: 1200px;
            padding: 20px;
        }

        section h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #333;
        }

        .about, .projects, .skills, .contact {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        .about:hover, .projects:hover, .skills:hover, .contact:hover {
            transform: translateY(-10px);
            background-color: #fffcf2;
        }

        /* Projects */
        .project-item {
            margin-bottom: 20px;
            padding: 15px;
            background-color: #ffefc1;
            border-left: 5px solid #ff8a00;
            transition: background-color 0.3s ease;
        }

        .project-item:hover {
            background-color: #ffdfa1;
        }

        /* Skills */
        .skills ul {
            list-style: none;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .skills ul li {
            margin: 10px;
            padding: 10px 20px;
            background-color: #e52e71;
            color: white;
            border-radius: 30px;
            font-size: 1.1rem;
            transition: background-color 0.3s ease;
        }

        .skills ul li:hover {
            background-color: #ff8a00;
        }

        /* Contact Form */
        form input, form textarea {
            width: 100%;
            padding: 15px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
            background-color: #f4f4f4;
            font-size: 1rem;
        }

        form button {
            width: 100%;
            padding: 15px;
            background-color: #e52e71;
            color: white;
            border: none;
            font-size: 1.2rem;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        form button:hover {
            background-color: #ff8a00;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>

<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about" class="about">
        <h2>About Me</h2>
        <p>Hello! I'm Nivedika Gour, a passionate web developer with a focus on creating vibrant, responsive, and user-friendly websites. I love turning ideas into reality through code!
        and  I would love to convert my creativity to amalgamate with technology for the best outcomes!!
        
        "Thank You"</p>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project-item">
            <h3>Project 1: Personal Website</h3>
            <p>This is a beautiful, dynamic personal website designed with HTML, CSS, and JavaScript. It's responsive and full of vibrant colors!</p>
        </div>
        <div class="project-item">
            <h3>Project 2: E-commerce Platform</h3>
            <p>A fully functional e-commerce platform built using modern web technologies like React, Node.js, and MongoDB.</p>
        </div>
         <div class="project-item">
            <h3>Project 3:hackthon completion</h3>
            <p> I have participated in many hackathos and won them 
            
            Also I'm a good

            <li>programmer</li>
            <li>project head</li>
            <li>creative person</li>
            <li>debugger</li>
            <li>curious learner</li>
            <li>problem solver</li>
            <li>And I have great logical thinking skills</li>
            </p>
        </div>
        <!-- Add more projects -->
    </section>

    <section id="skills" class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>Node.js</li>
            <li>Python</li>
            <li>PHP</li>
        </ul>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio | Designed with passion</p>
    </footer>
</body>

</html>
