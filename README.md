# Personal-portfolio
Personal portfolio website showcasing my software development journey, technical skills, and featured projects. Built with HTML/CSS and hosted via GitHub Pages.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        :root {
            --bg-color: #faf7f8;
            --card-bg: #ffffff;
            --text-main: #332d30;
            --text-muted: #706569;
            --accent-pink: #f3cbd3;
            --accent-soft: #fae1e6;
            --border-color: #eee5e7;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            padding: 40px 20px;
        }

        .container {
            max-width: 700px;
            margin: 0 auto;
        }

        header {
            margin-bottom: 40px;
            text-align: center;
        }

        header h1 {
            font-size: 2.2rem;
            font-weight: 600;
            margin-bottom: 8px;
            letter-spacing: -0.5px;
        }

        header p {
            color: var(--text-muted);
            font-size: 1.1rem;
        }

        .accent-bar {
            width: 50px;
            height: 4px;
            background-color: var(--accent-pink);
            margin: 15px auto 0 auto;
            border-radius: 2px;
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            font-size: 1.3rem;
            font-weight: 600;
            margin-bottom: 16px;
            border-bottom: 2px solid var(--accent-soft);
            padding-bottom: 4px;
            display: inline-block;
        }

        .about-text {
            color: var(--text-main);
            font-size: 1rem;
        }

        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 16px;
        }

        @media (max-width: 500px) {
            .grid {
                grid-template-columns: 1fr;
            }
        }

        .card {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            padding: 20px;
            border-radius: 8px;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        .card:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(243, 203, 211, 0.3);
        }

        .card h3 {
            font-size: 1.1rem;
            margin-bottom: 8px;
        }

        .card p {
            color: var(--text-muted);
            font-size: 0.9rem;
            margin-bottom: 12px;
        }

        .tag-container {
            display: flex;
            flex-wrap: wrap;
            gap: 6px;
        }

        .tag {
            background-color: var(--bg-color);
            border: 1px solid var(--border-color);
            padding: 2px 8px;
            border-radius: 4px;
            font-size: 0.75rem;
            color: var(--text-muted);
        }

        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .skill-item {
            background-color: var(--accent-soft);
            color: var(--text-main);
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
        }

        footer {
            text-align: center;
            margin-top: 60px;
            font-size: 0.85rem;
            color: var(--text-muted);
            border-top: 1px solid var(--border-color);
            padding-top: 20px;
        }

        footer a {
            color: var(--text-main);
            text-decoration: none;
            margin: 0 10px;
            font-weight: 500;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="container">
        
        <header>
            <h1>Hi, I'm Kanupriya</h1>
            <p>Btech student and aspiring software engineer.</p>
            <div class="accent-bar"></div>
        </header>

        <section id="about">
            <h2>About Me</h2>
            <p class="about-text">
                I am a Computer Science Engineering student passionate about exploring backend architecture, interactive system design, and security fundamentals. Currently, I am focused on strengthening my independent programming logic and building robust, efficient applications. I love taking ideas from concept to code and am always eager to learn new technologies.
            </p>
        </section>

        <section id="skills">
            <h2>Skills & Technologies</h2>
            <div class="skills-list">
                <span class="skill-item">Java</span>
                <span class="skill-item">C</span>
                <span class="skill-item">C++</span>
                <span class="skill-item">HTML & CSS</span>
		<span class="skill-item">Python</span>
                <span class="skill-item">Git & GitHub</span>
                <span class="skill-item">Cybersecurity Basics</span>
            </div>
        </section>

        <section id="projects">
            <h2>Featured Projects</h2>
            <div class="grid">
                
                <div class="card">
                    <h3>TripSync</h3>
                    <p>A smart carpooling application concept designed for student commuting, featuring optimized ride-matching logic and budget splits.</p>
                    <div class="tag-container">
                        <span class="tag">Java</span>
                        <span class="tag">UI Design</span>
                    </div>
                </div>

                <div class="card">
                    <h3>Secure Login System</h3>
                    <p>A backend authentication project demonstrating secure password storage, user authorization, and basic encryption fundamentals.</p>
                    <div class="tag-container">
                        <span class="tag">Spring Boot</span>
                        <span class="tag">Security</span>
                    </div>
                </div>

            </div>
        </section>

        <footer>
            <p>© 2026 • Built with 💖</p>
            <div style="margin-top: 10px;">
    	<a href="https://github.com/kanupriya-1401" target="_blank">GitHub</a>
    	<a href="https://www.linkedin.com/in/kanu-priya-1802273b2" target="_blank">LinkedIn</a>
    	<a href="mailto:kanupriya1401@gmail.com">Email</a>
	</div>
        </footer>

    </div>

</body>
</html>
