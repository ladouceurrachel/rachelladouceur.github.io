
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
            background-color: #f5f5f5; /* Light gray background to make the content card pop */
        }

        /* --- Main Content Container --- */
        .content-container {
            max-width: 1000px;
            margin: 50px auto; /* Centered with a nice top/bottom margin */
            padding: 40px;
            display: flex;
            gap: 50px;
            flex-wrap: wrap;
            background-color: #fff; /* Clean white card layout */
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.08);
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

        .main-content h2 {
            margin-top: 35px;
            color: #222;
            font-size: 1.4em;
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

        .custom-list {
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
        }

        .publication-list li {
            margin-bottom: 12px;
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
    </style>
</head>
<body>

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

  <!-- Right Main Content -->
  <div class="main-content">
    
    <h1>Rachel Ladouceur</h1>
    <div class="subtitle">PhD Candidate | Academic Lecturer | CPA, CISA</div>
    
    <!-- About Me Section -->
    <hr>
    <p>
      Rachel Ladouceur, CPA, CISA, is a PhD candidate in Computer Science at the Université du Québec à Chicoutimi (UQAC), Canada since 2022. Her doctoral work examines the effectiveness of large language models (LLMs) in identifying and explaining disinformation. She works part-time as a student PhD with the National Defence Research Centre.
    </p>

    <!-- Research Interests Section -->
    <h2>Research Interests</h2>
    <hr>
    <ul class="custom-list">
      <li>Disinformation and influence campaigns Detection</li>
      <li>Analyze narrative patterns</li>
      <li>Large Language Models (LLMs)</li>
    </ul>

    <!-- Publications Section -->
    <h2>Publications</h2>
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

    <!-- Curriculum Vitae Section -->
    <h2>Curriculum Vitae</h2>
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
  


