

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rachel Ladouceur - Personal Webpage</title>
    <style>
        /* General page styles */
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5; /* Light gray background */
        }

        /* --- Top Navigation Bar Menu --- */
        header {
            background-color: #ededed; /* Light gray navigation background */
            padding: 15px 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 1000; /* Keeps the menu on top when scrolling */
            width: 100%;
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 40px;
            box-sizing: border-box;
        }

        .site-title {
            font-weight: bold;
            font-size: 1.3em;
            color: #111;
            text-decoration: none;
            margin: 0;
        }

        .nav-links {
            display: flex;
            gap: 25px;
            list-style: none;
            margin: 0;
            padding: 0;
        }

        .nav-links a {
            text-decoration: none;
            color: #444;
            font-size: 1em;
            font-weight: 500;
            transition: color 0.2s;
        }

        .nav-links a:hover {
            color: #0066cc;
        }

        /* --- Main Content Container --- */
        .content-container {
            max-width: 1000px;
            margin: 30px auto 50px auto; /* Centered layout */
            padding: 40px;
            display: flex;
            gap: 50px;
            flex-wrap: wrap;
            background-color: #fff; /* Clean white card layout */
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.08);
            box-sizing: border-box;
        }

        /* Left column (Profile & Links) */
        .sidebar {
            flex: 1;
            min-width: 220px;
            max-width: 250px;
        }

        .profile-photo {
            width: 90%;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin-bottom: 25px;
        }

        .sidebar h3 {
            margin-top: 0;
            color: #222;
            font-size: 1.2em;
        }

        .sidebar hr {
            margin-bottom: 15px;
            border: 0;
            border-top: 1px solid #eee;
        }

        .contact-links {
            list-style: none;
            padding-left: 0;
            line-height: 2.2;
        }

        .contact-links a {
            text-decoration: none;
            color: #0066cc;
            transition: text-decoration 0.2s;
        }

        .contact-links a:hover {
            text-decoration: underline;
        }

        /* Right column (Main content) */
        .main-content {
            flex: 2;
            min-width: 300px;
        }

        .main-content h1 {
            margin-top: 0;
            margin-bottom: 5px;
            color: #111;
            font-size: 2.2em;
        }

        .subtitle {
            font-size: 1.2em;
            color: #666;
            margin-bottom: 25px;
        }

        /* Target offsets for smooth scrolling down to sections */
        .main-content h2 {
            margin-top: 40px;
            color: #222;
            font-size: 1.4em;
            scroll-margin-top: 70px; /* Prevents the sticky menu from covering headers */
        }

        .main-content h3 {
            margin-top: 25px;
            color: #444;
            font-size: 1.15em;
        }

        .main-content hr {
            border: 0;
            border-top: 1px solid #eee;
            margin-bottom: 15px;
        }

        .main-content p {
            line-height: 1.6;
            font-size: 1.1em;
            margin-bottom: 1.2em;
        }

        .custom-list, .teaching-list {
            line-height: 1.8;
            font-size: 1.05em;
            padding-left: 20px;
            margin-bottom: 20px;
        }

        .publication-list {
            line-height: 1.7;
            font-size: 1.05em;
            padding-left: 20px;
            margin-bottom: 20px;
            list-style-type: square;
        }

        .publication-list li, .teaching-list li {
            margin-bottom: 15px;
        }

        .publication-list a {
            color: #0066cc;
            text-decoration: none;
            font-size: 0.95em;
            margin-left: 5px;
        }

        .publication-list a:hover {
            text-decoration: underline;
        }

        /* CV Download Button Style */
        .cv-button {
            background-color: #0066cc; 
            color: white; 
            padding: 12px 25px; 
            text-decoration: none; 
            font-weight: bold; 
            border-radius: 5px; 
            box-shadow: 0 2px 5px rgba(0,0,0,0.15);
            display: inline-block;
            transition: background-color 0.2s;
            margin-top: 10px;
        }

        .cv-button:hover {
            background-color: #004ea3;
        }

        /* Enable smooth scrolling effects */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>

<!-- --- HORIZONTAL NAVIGATION MENU --- -->
<header>
    <div class="nav-container">
        <a href="#" class="site-title">Rachel Ladouceur</a>
        
        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#publications">Publications</a></li>
            <li><a href="#teaching">Teaching</a></li>
            <li><a href="#cv">CV</a></li>
        </ul>
    </div>
</header>

<!-- --- MAIN PAGE CONTENT --- -->
<div class="content-container">

    <!-- Left Sidebar: Photo & Links -->
    <div class="sidebar">
        <img src="photo.png" alt="Rachel Ladouceur" class="profile-photo">
        
        <h3>Contact & Links</h3>
        <hr>
        
        <ul class="contact-links">
            <li>💼 <a href="https://www.linkedin.com/in/rachel-ladouceur-a2a86b26" target="_blank">My LinkedIn Profile</a></li>
            <li>🎓 <a href="https://scholar.google.com/citations?user=ladouceurrachel" target="_blank">My Google Scholar Profile</a></li>
            <li>🆔 <a href="https://orcid.org/0009-0009-9201-0268" target="_blank">My ORCID Profile</a></li>
            <li>💻 <a href="https://github.com/ladouceurrachel" target="_blank">My GitHub Profile</a></li>
        </ul>
    </div>

    <!-- Right Main Content Column -->
    <div class="main-content">
        
        <h1>Rachel Ladouceur</h1>
        <div class="subtitle">PhD Candidate | Academic Lecturer | CPA, CISA</div>
        
        <!-- About Me Section -->
        <h2 id="about" style="margin-top: 0;">About Me</h2>
        <hr>
        <p>
            Rachel Ladouceur, CPA, CISA, is a PhD candidate in Computer Science at the Université du Québec à Chicoutimi (UQAC), Canada since 2022. Her doctoral work examines the effectiveness of large language models (LLMs) in identifying and explaining disinformation. She works part-time as a student PhD with the National Defence Research Centre.
        </p>

        <!-- Research Interests Section -->
        <h2>Research Interests</h2>
        <hr>
        <ul class="custom-list">
            <li>Disinformation and influence campaigns Detection: Detect and explain disinformation by clustering similar messages into thematic groups. Prioritize those with the greatest negative impact on society. </li>
            <li>Analyze narrative patterns: Identify and validate dominant narratives in platform networks. Narrative analysis reveals the implicit meanings, interpretive frames, and discursive strategies that are never visible in a single message.(</li>
            <li>Large Language Models (LLMs): Use LLMs to analyze narratives and assess their effectiveness in detecting and explaining disinformation through comparative multi-model approaches. </li>
        </ul>

        <!-- Publications Section -->
        <h2 id="publications">Publications</h2>
        <hr>

        <h3>Articles Submitted</h3>
        <ul class="publication-list">
            <li>
                <strong>Ladouceur, R.</strong>, Ben Abdessalem, H., & Jaafar, F. (2026). Elements of Credibility or Credulity About Fake News Exposure: An Empirical Study. Submitted to <em>ACM Transactions on Social Computing (TSC)</em>, April 15th.
            </li>
        </ul>

        <h3>International Conferences</h3>
        <ul class="publication-list">
            <li>
                <strong>Ladouceur, R.</strong>, Njeh, C., Nakouri, H., and Jaafar, F. (2025). Comparisons Between Open-LLMs For Fake News Detection. In <em>Proceedings of the 2025 9th Cyber Security in Networking Conference (CSNet)</em> (pp. 1–5). IEEE. 
                <a href="https://doi.org/10.1109/CSNet67572.2025.11288261" target="_blank">[View on IEEE Xplore]</a>
            </li>
            <li>
                <strong>Ladouceur, R.</strong>, Hassan, A., Mejri, M., & Jaafar, F. (2024). Can Deep Learning Detect Fake News Better when Adding Context Features? In <em>2024 IEEE International Conference on Cyber Security and Resilience (CSR)</em> (pp. 56–61). 
                <a href="https://doi.org/10.1109/CSR61664.2024.10679393" target="_blank">[View on IEEE Xplore]</a>
            </li>
        </ul>

        <h3>Book Chapters</h3>
        <ul class="publication-list">
            <li>
                <strong>Ladouceur, R.</strong> (2023). Cyber Influence Stakes. In F. Jaafar & S. Pierre (Eds.), <em>Blockchain and Artificial Intelligence-Based Solution to Enhance the Privacy in Digital Identity and IoT</em> (pp. 155–174). CRC Press.
            </li>
            <li>
                <strong>Ladouceur, R.</strong>, Pierre, S., & Jaafar, F. (2022). Cyberguerre : géopolitique des infrastructures technologiques et des réseaux sociaux. In D. Uzunidis & L. Adatto (Eds.), <em>Catastrophes majeures au XXIe siècle : Santé, environnement, alimentation, guerre</em> (Magna Carta Collection). Éditions Le Manuscrit.
            </li>
        </ul>

        <h3>Conference Presentation</h3>
        <ul class="publication-list">
            <li>
                ACFAS, Intelligence artificielle et cyberinfluence, Congrès de l’Association francophone professionnelle pour le savoir (ACFAS), May 2022.
            </li>
        </ul>

        <!-- Teaching Section -->
        <h2 id="teaching">Teaching</h2>
        <hr>
        <p>
            Alongside my doctoral studies, I serve as an academic lecturer to bridge theoretical computer science frameworks with operational IT realities. 
        </p>

        <ul class="teaching-list">
            <li>
                <strong>GCGR2010 — Security Governance and Risk Management</strong> <br>
                <em>Université de technologie d’Haïti</em> | Spring 2026 (Current) <br>
                Lecturer for 1 class of 19 students. Graduate Diploma (DESS) in Information Technology and Computer Science (TII). Total of 36 hours (3 hours/week).
            </li>
            <li>
                <strong>GIS4020 — Security Incident Management (Detection & Response Tools)</strong> <br>
                <em>Université de technologie d’Haïti</em> | Winter 2026 <br>
                Lecturer for 1 class of 19 students. Graduate Diploma (DESS) in Information Technology and Computer Science (TII). Total of 36 hours (3 hours/week).
            </li>
            <li>
                <strong>8INF970 — Cybersecurity Workshop II</strong> <br>
                <em>Université du Québec à Chicoutimi (UQAC)</em> | Winter 2025 <br>
                Lecturer for 1 class of 30 Master's students. Department of Computer Science and Mathematics. Total of 45 hours (3 hours/week). 
            </li>
            <li>
                <strong>8INF882 — Security Incident Management (Detection & Response Tools)</strong> <br>
                <em>Université du Québec à Chicoutimi (UQAC)</em> | Fall 2022, 2024 <br>
                Lecturer for the Department of Computer Science and Mathematics. Taught 1 class of 7 Master's students (2022) and 2 classes of 30 students (2024). Total of 45 hours per semester (3 hours/week).
            </li>
        </ul>
        
        <!-- Curriculum Vitae Section -->
        <h2 id="cv">Curriculum Vitae</h2>
        <hr>
        <p>
            For a comprehensive overview of my academic background, teaching experience, and professional certifications, you can access my full CV below:
        </p>
        
        <div>
            <a href="Cv.pdf" target="_blank" class="cv-button">
                📄 Download my CV (PDF)
            </a>
        </div>

    </div> 
</div>

</body>
</html>
