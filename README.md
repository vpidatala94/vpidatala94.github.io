<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        header {
            background: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 24px;
        }
        .section {
            margin-bottom: 30px;
            padding: 20px;
            border-bottom: 1px solid #ddd;
        }
        h1, h2 {
            color: #444;
        }
        .profile-pic {
            width: 150px;
            height: 150px;
            background: url('https://via.placeholder.com/150');
            background-size: cover;
            display: block;
            margin: 20px auto;
            border-radius: 50%;
        }
        .skills-list, .projects-list {
            list-style: none;
            padding: 0;
        }
        .skills-list li, .projects-list li {
            padding: 10px;
            background: #eee;
            margin: 5px 0;
            border-radius: 5px;
        }
        .footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Professional Portfolio</h1>
    </header>
    <div class="container">
        <div class="section" id="introduction">
            <h2>Introduction</h2>
            <p>Welcome to my professional website. Here you will find information about my skills, experience, and projects.</p>
        </div>
        <div class="section" id="core-skills">
            <h2>Core Skills</h2>
            <ul class="skills-list">
                <li>Web Development</li>
                <li>Software Engineering</li>
                <li>Project Management</li>
            </ul>
        </div>
        <div class="section" id="experience">
            <h2>Professional Experience</h2>
            <p><strong>Company Name - Position</strong> (Year-Present)</p>
            <p>Description of your role and achievements.</p>
        </div>
        <div class="section" id="projects">
            <h2>Projects</h2>
            <ul class="projects-list">
                <li><strong>Project Name</strong>: Brief description of what the project is about.</li>
                <li><strong>Project Name</strong>: Brief description of what the project is about.</li>
            </ul>
        </div>
        <div class="section" id="photo">
            <h2>Photo</h2>
            <div class="profile-pic"></div>
        </div>
    </div>
    <div class="footer">
        <p>&copy; 2024 My Portfolio | Contact: email@example.com</p>
    </div>
</body>
</html>
