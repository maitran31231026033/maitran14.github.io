# My Resume
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume - Mainran14</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #1ce6e6;
            color: #f7f2f2;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 30px;
            padding: 30px 0;
            background: linear-gradient(135deg, #2c3e50, #3498db);
            color: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1.8rem;
            margin: 25px 0 15px;
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 5px;
        }

        h3 {
            font-size: 1.3rem;
            margin: 15px 0 10px;
            color: #3498db;
        }

        .tagline {
            font-size: 1.2rem;
            color: #ecf0f1;
            margin-bottom: 15px;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 15px;
        }

        .contact-info a {
            color: white;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .resume-content {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 30px;
        }

        .main-section {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .sidebar {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .section {
            margin-bottom: 25px;
        }

        .job, .education-item {
            margin-bottom: 20px;
        }

        .date {
            color: #7f8c8d;
            font-style: italic;
            margin-bottom: 5px;
        }

        .skills-list {
            list-style-type: none;
        }

        .skills-list li {
            margin-bottom: 10px;
            padding: 8px 12px;
            background: #ecf0f1;
            border-radius: 5px;
            transition: transform 0.3s ease;
        }

        .skills-list li:hover {
            transform: translateX(5px);
            background: #d5dbdb;
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #7f8c8d;
            font-size: 0.9rem;
        }

        .footer a {
            color: #3498db;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            .resume-content {
                grid-template-columns: 1fr;
            }
            
            .contact-info {
                flex-direction: column;
                align-items: center;
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>My Resume</h1>
            <p class="tagline">Created with HTML5 & CSS</p>
            <div class="contact-info">
                <a href="https://mainran14.github.io/" target="_blank">
                    <i class="fas fa-globe"></i> mainran14.github.io
                </a>
                <a href="mailto:mainran14@example.com">
                    <i class="fas fa-envelope"></i> mainran14@example.com
                </a>
                <a href="tel:+84364358690">
                    <i class="fas fa-phone"></i> +84 364 358 690
                </a>
            </div>
        </header>

        <div class="resume-content">
            <div class="main-section">
                <div class="section">
                    <h2>Summary</h2>
                    <p>A graduate with dual majors in Investment Economics and Public Management. Possesses strong analytical and communication skills. Holds an IELTS certificate with a score of 6.5. Proficient in Microsoft Office applications such as Word and Excel, and skilled in Stata, SPSS, and R.</p>
                </div>
                <div class="section">
                    <h2>Education</h2>
                    <div class="education-item">
                        <h3>Bachelor of Investment Economics and Public Management</h3>
                        <p class="date">2023 - 2026</p>
                        <p>University of Economics of Ho Chi Minh City</p>
                    </div>
                </div>
            </div>

            <div class="sidebar">
                <div class="section">
                    <h2>Skills</h2>
                    <ul class="skills-list">
                        <li>Git & GitHub</li>
                        <li>Problem Solving</li>
                        <li>Communication skills
                        <li>Information searching and Researching
                        <li>Analytical skills
                        <li>Team Collaboration</li>
                    </ul>
                </div>

                <div class="section">
                    <h2>Achievements</h2>
                    <div class="academic">
                        <h3>Two scientific research projects, awarded at the university level</h3>
                    <dive class="Extracurricular activities">
                        <h3>Winner of the Faculty-level Student Debate Competition          
                    </div>
                </div>

                <div class="section">
                    <h2>Languages</h2>
                    <ul class="skills-list">
                        <li>Vietnamese (Native)</li>
                        <li>English (Fluent)</li>
                        <li>Chinese (Basic)</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="footer">
            <p>This resume was created using plain HTML5 & CSS. Hosted on <a href="https://mainran14.github.io/" target="_blank">GitHub Pages</a>.</p>
        </div>
    </div>
</body>
</html>
### Summary

My resume I made using plain HTML5 & CSS.
https://maitran14.github.io/

