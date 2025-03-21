<!DOCTYPE html>

<html>

<head>

    <title>Portfolio</title>

    <style>

        body {

            font-family: Arial, sans-serif;

            margin: 0;

            padding: 0;

            background-color: #f0f0f0;;

        }



        header {

            background-color: #3498db;

            color: #fff;

            text-align: center;

            padding: 2rem 0;

            position: relative; /* Add this */

        }



        .header-content h1 {

            font-size: 2.5rem;

        }



        /* Add styles for the round profile picture */

        .profile-picture {

            width: 100px; /* Adjust the size as needed */

            height: 100px;

            border-radius: 75%; /* Create a circular shape */

            object-fit: cover; /* To ensure the image fills the circular area */

            position: absolute; /* Add this */

            top: 75px; /* Adjust top position as needed */

            left: 75px; /* Adjust left position as needed */

        }



        nav {

            background-color: #333;

            color: #fff;

            text-align: center;

        }



        nav ul {

            list-style-type: none;

            padding: 0;

        }



        nav ul li {

            display: inline;

            margin: 0 20px;

        }



        nav ul li a {

            text-decoration: none;

            color: #fff;

        }



        .section-content {

            background-color: #fff;

            padding: 2rem;

            margin: 1rem;

            border-radius: 20px;

            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

            text-align: justify;

        }



        .download-button {

            background-color: #333;

            color: #fff;

            padding: 0.5rem 1rem;

            text-decoration: none;

            border-radius: 20px;

            display: inline-block;

            margin-top: 10px;

            align-self: center;

        }



        .download-button:hover {

            background-color: #555;

        }



        footer {

            text-align: center;

            padding: 1rem 0;

            background-color: #333;

            color: #fff;

        }



        ul {

            list-style-type: disc;

            padding-left: 20px;

        }

    </style>

</head>

<body>

    <header>

        <div class="header-content">

            <!-- Add your profile picture here -->

            <img src="IMG_20250321_094053.jpg"alt="your profile picture" class="profile-picture">

            <h1>Thangaraj M</h1>

            <p>BSC Computer science</p>

        </div>

    </header>



    <nav>

        <ul>

            <li><a href="#about">About</a></li>

            <li><a href="#education">Education</a></li>

            <li><a href="#skills">Skills</a></li>

            <li><a href="#projects">Projects</a></li>

            <li><a href="#resume">Resume</a></li>

           

        </ul>

    </nav>



    <section id="about">

        <div class="section-content">

            <h2>About Me</h2>

            <p>Hello! I'm Thangaraj M, a second-year student pursuing a Bachelor of Science in Computer Science (BSC CS).
                
               As a budding web developer, I'm passionate about creating innovative and user-friendly digital experiences.
                
               With a strong foundation in computer science, I'm well-versed in programming languages like HTML, CSS, Java, C++, and Python.
                
               I'm also familiar with web development frameworks and technologies.
                
               As a student, I'm constantly seeking opportunities to learn and grow.
                
               I'm excited to apply my skills and knowledge to real-world projects and collaborate with like-minded individuals.
                
               Feel free to explore my portfolio and get in touch with me if you'd like to discuss potential projects or opportunities.</p>



        </div>

    </section>



    <section id="education">

        <div class="section-content">

            <h2>Education</h2>

            <p>Medras University  - BSC CS</p>

            

            

        </div>

    </section>



    <section id="skills">

        <div class="section-content">

            <h2>Skills</h2>

            <ul>

                <li>HTML</li>
                <li>CSS</li>
                <li>Computer Architecture</li>
                <li>React</li>


                <li>Python</li>

              <li>Data structure</li>
                <li>java</li>

                <li>c++</li>

            </ul>

        </div>

    </section>



    <section id="projects">

        <div class="section-content">

            <h2>Projects</h2>

            <ul>

                <li><a href="#">Personal Portfolio</a></li>


                <!-- Add more project links here -->

            </ul>

        </div>

    </section>



    <section id="resume">

    

        <div class="section-content">

            <center>

            <h2>Resume</h2>

            <a href="Thangaraj M.pdf"target="_blank" class="download-button">Download CV</a>

        </center>

        </div>

        

    </section>



    <footer>

        <p>&copy; 2025 Thangaraj M</p>

    </footer>



    <script>

        // Smooth scrolling to section when clicking on navigation links

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {

            anchor.addEventListener('click', function(e) {

                e.preventDefault();



                const targetId = this.getAttribute('href').substring(1);

                const targetElement = document.getElementById(targetId);



                if (targetElement) {

                    window.scrollTo({

                        top: targetElement.offsetTop,

                        behavior: 'smooth'

                    });

                }

            });

        });

    </script>

</body>

</html>
