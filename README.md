<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rajat Sharma - Developer Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            background: #161b22;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 8px 24px rgba(0,0,0,0.5);
            border: 1px solid #30363d;
        }
        header {
            text-align: center;
            margin-bottom: 30px;
        }
        header h1 {
            color: #58a6ff;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        header p {
            color: #8b949e;
            font-size: 1.1rem;
        }
        .section {
            margin-bottom: 25px;
        }
        .section h2 {
            color: #58a6ff;
            border-bottom: 1px solid #30363d;
            padding-bottom: 8px;
            margin-bottom: 15px;
            font-size: 1.4rem;
        }
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .skill-tag {
            background: #21262d;
            color: #58a6ff;
            padding: 8px 14px;
            border-radius: 6px;
            font-size: 0.9rem;
            border: 1px solid #30363d;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            color: #8b949e;
            font-size: 0.85rem;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Rajat Sharma</h1>
            <p>Frontend Explorer & UI/UX Design Enthusiast</p>
        </header>

        <div class="section">
            <h2>About Me</h2>
            <p>Hello! I am a student and passionate developer focused on building clean interfaces, exploring web technologies, and learning backend development fundamentals.</p>
        </div>

        <div class="section">
            <h2>Tech Stack & Tools</h2>
            <div class="skills-list">
                <span class="skill-tag">HTML5</span>
                <span class="skill-tag">CSS3</span>
                <span class="skill-tag">JavaScript</span>
                <span class="skill-tag">Git</span>
                <span class="skill-tag">VS Code</span>
                <span class="skill-tag">Figma</span>
                <span class="skill-tag">Canva</span>
            </div>
        </div>

        <footer>
            <p>Built with HTML & Internal CSS • Hosted on GitHub Pages</p>
        </footer>
    </div>

</body>
</html>
