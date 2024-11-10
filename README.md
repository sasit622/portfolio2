<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Reset some default browser styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Basic body styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f4f6;
            color: #333;
        }

        /* Header styling */
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-top: 15px;
        }

        /* Main container */
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Section titles */
        .section-title {
            font-size: 1.5em;
            margin-bottom: 10px;
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
            margin-top: 20px;
        }

        /* About, Projects, Contact sections */
        .about, .projects, .contact {
            margin-bottom: 30px;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }

        /* Individual project styling */
        .project-item {
            margin-bottom: 15px;
        }

        /* Footer styling */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: #fff;
            font-size: 0.9em;
        }

        /* Link styling */
        a {
            color: #007bff;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>My Portfolio</h1>
    <img src="profile.jpg" alt="Profile Picture" class="profile-img">
</header>

<div class="container">
    <!-- About Section -->
    <section class="about">
        <h2 class="section-title">About Me</h2>
        <p>Hi! I'm SASITHARAN S, a passionate software developer specializing in C++ and web development. I enjoy creating efficient solutions and continuously learning new technologies.</p>
    </section>

    <!-- Projects Section -->
    <section class="projects">
        <h2 class="section-title">Projects</h2>
        <div class="project-item">
            <h3>Project 1: [NORMAL AND TRACE MATRIX]</h3>
            <p>Normal Matrix: A square matrix A is called normal if it commutes with its conjugate transpose,AA∗=A∗A.
            Trace of a Matrix: The trace of a matrix is the sum of its diagonal elements. </p>
        </div>
        <div class="project-item">
            <h3>Project 2: [TREE]</h3>
            <p> This problem teaches how to find the closest shared boss of two employees in a company hierarchy. It applies concepts of tree structures and common ancestors useful in organizational charts, file systems, and genealogy..</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <!-- Contact Section -->
    <section class="contact">
        <h2 class="section-title">Contact</h2>
        <p>Email: sasit@gmail.com</p>
        <p>LinkedIn: <a href=https://www.linkedin.com/in/sasitharan-s-b6b1b9329?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app target="_blank">LinkedIn Profile</a></p>
        <p>GitHub: <a href="https://github.com/sasit622/SASI" target="_blank">GitHub Profile</a></p>
    </section>
</div>

<footer>
    <p>&copy; 2024 SASITHARAN S. All rights reserved.</p>
</footer>

</body>
</html>
