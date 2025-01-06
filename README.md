<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Global Styles */
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            color: #f5f5f5;
            background-color: #121212; /* Dark background color */
        }
        h1, h2 {
            font-weight: 700;
        }
        a {
            color: #00bcd4; /* Link color to teal */
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }

        /* Header */
        header {
            background: linear-gradient(90deg, #00bcd4, #0047ab); /* Gradient for header */
            color: white;
            padding: 2rem 1rem;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        header p {
            font-size: 1.2rem;
            margin: 0.5rem 0 1.5rem;
        }
        .social-icons {
            display: flex;
            justify-content: center;
            margin-top: 1rem;
        }
        .social-icons a {
            margin: 0 0.5rem;
            font-size: 1.5rem;
            color: white;
            transition: color 0.3s ease;
        }
        .social-icons a:hover {
            color: #ffcc00;
        }

        /* Navigation */
        nav {
            background: #1a1a1a;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            display: flex;
            justify-content: center;
        }
        nav a {
            margin: 0 1rem;
            font-weight: bold;
            font-size: 1rem;
            color: #f5f5f5;
        }

        /* Sections */
        section {
            background-color: #121212; /* Dark background for sections */
            padding: 2rem 1rem;
            max-width: 1200px;
            margin: 2rem auto;
        }
        section h2 {
            color: #00bcd4; /* Section heading color to teal */
            font-size: 2rem;
            margin-bottom: 1rem;
            text-transform: uppercase;
        }

        /* About Section */
        #about p {
            font-size: 1.2rem;
            line-height: 1.6;
        }

        /* Expertise Section */
        #expertise ul {
            list-style: none;
            padding: 0;
        }
        #expertise ul li {
            margin-bottom: 0.8rem;
            font-size: 1.1rem;
        }
        #expertise ul li::before {
            content: "✔";
            color: #00bcd4; /* Teal for check icon */
            margin-right: 0.5rem;
        }

        /* Experience Section */
        .experience-card {
            background: #1a1a1a;
            border-radius: 10px;
            margin-bottom: 2rem;
            padding: 1.5rem;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .experience-card:hover {
            transform: scale(1.02);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.5);
        }
        .experience-card h3 {
            margin-top: 0;
            font-size: 1.5rem;
            color: #00bcd4; /* Teal for job title */
        }
        .experience-card p {
            margin: 0.5rem 0 1rem;
            font-size: 1.1rem;
            color: #cccccc;
        }
        .experience-card ul {
            margin: 0;
            padding-left: 1.2rem;
            color: #b3b3b3;
        }
        .experience-card ul li {
            margin-bottom: 0.5rem;
        }

        /* Contact Section */
        #contact p {
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
        }

        /* New Sections */
        #passion-projects, #knowledge-sharing {
            background-color: #1a1a1a; /* Darker background for new sections */
            padding: 2rem 1rem;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            margin-bottom: 2rem;
        }

        #passion-projects p, #knowledge-sharing p {
            font-size: 1.2rem;
            line-height: 1.6;
            color: #cccccc;
        }

        /* Footer */
        footer {
            text-align: center;
            background-color: #121212; /* Dark footer */
            padding: 1.5rem 0;
            color: #cccccc;
        }
        footer a {
            color: #00bcd4;
        }
    </style>
</head>
<body>
<header>
    <div style="display: flex; align-items: center; justify-content: center;">
        <!-- Image on the left side -->
        <img src="slkr.png" alt="Profile Picture" style="border-radius: 50%; width: 80px; height: 80px; margin-right: 20px;">
        <!-- Text content on the right -->
        <div>
            <h2>LaxmiKumar Sammeta</h2>
            <p>Technology Executive | AI & Digital Transformation Leader</p>
            <div class="social-icons">
                <a href="https://www.youtube.com" target="_blank"><i class="fab fa-youtube"></i></a>
                <a href="https://x.com/slkreddy" target="_blank"><i class="fab fa-twitter"></i></a>
                <a href="https://github.com" target="_blank"><i class="fab fa-github"></i></a>
                <a href="https://www.linkedin.com/in/laxmikumarreddy/" target="_blank"><i class="fab fa-linkedin"></i></a>
            </div>
        </div>
    </div>
</header>

    <nav>
        <a href="#about">About</a>
        <a href="#expertise">Expertise</a>
        <a href="#experience">Experience</a>
        <a href="#passion-projects">Passion Projects</a>
        <a href="#knowledge-sharing">Knowledge Sharing</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a Technology Executive with a proven track record of delivering mission-critical applications and driving innovation through servant leadership. 
            From designing scalable systems to leading high-performing teams, I specialize in bridging technical expertise with strategic vision to drive transformative outcomes.
        </p>
    </section>
    <section id="expertise">
        <h2>Expertise</h2>
        <ul>
            <li><strong>AI/ML Solutions</strong>: Led the integration of Large Language Models (LLMs) into full-stack applications, leveraging capabilities such as text-to-SQL open-source models (e.g., HuggingFace) and fine-tuning models for a wide range of domain-specific tasks.</li>
            <li><strong>Enterprise Application Development</strong>: Led the design and delivery of scalable applications using Java/Springboot, Python, and ORMs. Expert in Scrum practices and managing global stakeholders to drive robust, efficient systems.</li>
            <li><strong>Data Engineering & Feature Engineering</strong>: Expertise in building streaming and batch data pipelines for seamless integration and scalability, with extensive experience in preprocessing and transforming data to enhance AI/ML model performance and accuracy.</li>
            <li><strong>Cloud and Infrastructure Optimization</strong>: Expertise in AWS services, designing cross-account data streams in AWS Cloud. Developed an infrastructure recommender system focused on optimizing cloud costs and rightsizing for improved efficiency.</li>
            <li><strong>People Leadership</strong>: Proven ability to mentor and grow high-performing cross-functional teams, drive talent acquisition, and foster innovation. Skilled in team development, hiring, and aligning teams with strategic goals to deliver impactful results.</li>
        </ul>
    </section>
    <section id="experience">
        <h2>Experience</h2>
        <div class="experience-card">
            <h3>Executive Director – AI & ML Platform</h3>
            <p>JPMorgan Chase | 2016 – Present</p>
            <ul>
                <li>AI/ML Solutions: Generative AI and LLM-powered applications using Java, Python, AWS, and ML frameworks.</li>
                <li>Cloud Integration: Migrated systems to cloud environments for enhanced scalability.</li>
                <li>Platform Observability: Unifying enterprise-scale monitoring tools for platform owners at JPMC.</li>
            </ul>
        </div>
        <div class="experience-card">
            <h3>Lead System Designer</h3>
            <p>GE Healthcare | 2011 – 2016</p>
            <ul>
                <li>Designed and implemented healthcare data management systems.</li>
                <li>Enhanced reporting and operational efficiency for medical systems.</li>
            </ul>
        </div>
        <div class="experience-card">
            <h3>Senior Software Engineer</h3>
            <p>Various Roles | 2005 – 2011</p>
            <ul>
                <li>Developed enterprise-level software with a focus on performance optimization.</li>
                <li>Implemented scalable cloud-based solutions for global operations.</li>
            </ul>
        </div>
    </section>
    <section id="passion-projects">
        <h2>Passion Projects</h2>
        <p>
            Keenly interested in Generative AI and Large Language Models, reshaping industries and unlocking new AI-powered application possibilities. 
            These technologies are rapidly transforming the way businesses function, leading to groundbreaking innovations.
        </p>
    </section>
    <section id="knowledge-sharing">
        <h2>Knowledge Sharing and Mentorship</h2>
        <p>
            Keynote speaker at industry forums and academic institutions, passionate about contributing to student growth and inspiring the next generation of technologists. Organized TECHMEETUP 2024, reinforcing thought leadership in mentorship and knowledge sharing.
            Open Source contributor.
        </p>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:slkreddysite@gmail.com">slkreddysite@gmail.com</a></p>
    </section>
    <footer>
        <p>&copy; 2025 LaxmiKumar Sammeta | <a href="#top">Back to Top</a></p>
    </footer>
</body>
</html>
