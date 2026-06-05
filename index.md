
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to my site - Rachel Ladouceur</title>
    <style>
        /* Styles généraux pour la page */
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5; /* Fond subtilement gris pour faire ressortir le contenu */
        }

        /* --- Styles du Menu Supérieur --- */
        header {
            background-color: #ededed; /* Fond gris clair identique à la capture d'écran */
            padding: 15px 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            width: 100%;
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
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
            gap: 20px;
            list-style: none;
            margin: 0;
            padding: 0;
        }

        .nav-links a {
            text-decoration: none;
            color: #444;
            font-size: 1em;
            transition: color 0.2s;
        }

        .nav-links a:hover {
            color: #0066cc;
        }

        /* --- Styles du Conteneur Principal --- */
        .content-container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 40px;
            display: flex;
            gap: 40px;
            flex-wrap: wrap;
            background-color: #fff; /* Fond blanc pour le bloc de contenu */
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.08);
        }

        /* Colonne de gauche (Photo de profil et réseaux) */
        .sidebar {
            flex: 1;
            min-width: 220px;
            max-width: 250px;
        }

        .profile-photo {
            width: 90%;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }

        .sidebar h3 {
            margin-top: 0;
            color: #222;
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

        /* Colonne de droite (Contenu textuel principal) */
        .main-content {
            flex: 2;
            min-width: 300px;
        }

        .main-content h2 {
            margin-top: 0;
            color: #222;
        }

        .main-content hr {
            border: 0;
            border-top: 1px solid #eee;
            margin-bottom: 20px;
        }

        .main-content p {
            line-height: 1.6;
            font-size: 1.1em;
            margin-bottom: 1.2em;
        }

        .research-interests, .teaching-list {
            line-height: 1.8;
            font-size: 1.05em;
            padding-left: 20px;
            margin-bottom: 20px;
        }

        /* Style pour le bouton de téléchargement du CV */
        .cv-button {
            background-color: #0066cc; 
            color: white; 
            padding: 12px 25px; 
            text-decoration: none; 
            font-weight: bold; 
            border-radius: 5px; 
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            display: inline-block;
            transition: background-color 0.2s;
            margin-top: 15px;
            margin-bottom: 15px;
        }

        .cv-button:hover {
            background-color: #004ea3;
        }
    </style>
</head>
<body>

<!-- --- BARRE DE NAVIGATION (Menu supérieur) --- -->
<header>
    <div class="nav-container">
        <a href="#" class="site-title">Rachel Ladouceur</a>
        
        <ul class="nav-links">
            <li><a href="#publications">Publications</a></li>
            <li><a href="#teaching">Teaching</a></li>
            <li><a href="#experience">Experience</a></li>
            <!-- Ouvre le PDF directement dans un nouvel onglet si cliqué dans le menu -->
            <li><a href="CV_Rachel_Ladouceur.pdf" target="_blank">CV</a></li>
        </ul>
    </div>
</header>

<!-- --- CONTENU DE LA PAGE --- -->
<div class="content-container">

  <h1 style="width: 100%; margin-top: 0; margin-bottom: 30px; text-align: center; color: #111;">Welcome to my site</h1>

  <!-- Colonne de gauche : Photo et Liens de profils -->
  <div class="sidebar">
    <img src="photo.png" alt="Rachel Ladouceur" class="profile-photo">
    
    <h3>Contact & Links</h3>
    <hr>
    
    <ul class="contact-links">
      <li>💼 <a href="https://www.linkedin.com/in/rachel-ladouceur-a2a86b26" target="_blank">Mon Profil LinkedIn</a></li>
      <li>🎓 <a href="https://scholar.google.com/citations?user=ladouceurrachel" target="_blank">Mon Profil Google Scholar</a></li>
      <li>🆔 <a href="https://orcid.org/0009-0009-9201-0268" target="_blank">Mon Profil ORCID</a></li>
      <li>💻 <a href="https://github.com/ladouceurrachel" target="_blank">Mon Profil GitHub</a></li>
    </ul>
  </div>

  <!-- Colonne de droite : Corps de texte principal -->
  <div class="main-content">
    
    <!-- Section À propos -->
    <hr>
    
      
    <p>Rachel Ladouceur, CPA, CISA, is a PhD candidate in Computer Science at the Université du Québec à Chicoutimi (UQAC), Canada since 2022. Her doctoral work examines the effectiveness of large language models (LLMs) in identifying and explaining disinformation. She works part-time as a student PhD with the National Defence Research Centre.
</p>
      <!-- Section Intérêts de recherche -->
    <h2 style="margin-top: 40px;">Intérêts de recherche</h2>
    <hr>
    <ul class="research-interests">
       <li>Disinformation and influence campaigns Detection</li>
      <li>Analyze narrative patterns</li>
      <li>Large Language Models (LLMs)</li>
    </ul>

<h2>Publications</h2>
    <hr>


  <h3>Article submitted</h3>
  <ul>
      <li><strong>Ladouceur, R.</strong> Ben Abdessalem, H., & Jaafar, F. (2026). Elements of Credibility or Credulity About Fake News Exposure : An Empirical Study. Submitted to ACM Transactions on Social Computing (TSC), April 15th.</li>
 </ul>
 
 <h3>International Conferences</h3>
 <ul>
      <li><strong>Ladouceur, R.</strong>, Njeh, C., Nakouri, H., and Jaafar, F. (2025). Comparisons Between Open-LLMs For Fake News Detection. In Proceedings of the 2025 9th Cyber Security in Networking Conference (CSNet) (pp. 1–5). IEEE.  <a href="https://doi.org/10.1109/CSNet67572.2025.11288261" target="_blank">Consulter l'article sur IEEE Xplore</a>.      
      </li>

   <li><strong>Ladouceur, R.</strong>, Hassan, A., Mejri, M., & Jaafar, F. (2024). Can Deep Learning Detect Fake News Better when Adding Context Features ? In 2024 IEEE International Conference on Cyber Security and Resilience (CSR) (pp. 56–61). <a href="https://doi.org/10.1109/CSR61664.2024.10679393" target="_blank">Consulter l'article sur IEEE Xplore</a>.
      </li>
  </ul>
     
<h3>Book Chapter</h3>
<ul>
  <li><strong>Ladouceur, R.</strong> (2023). Cyber Influence Stakes. In F. Jaafar & S. Pierre (Eds.), Blockchain and Artificial Intelligence-Based Solution to Enhance the Privacy in Digital Identity and IoT (pp. 155–174). CRC Press.</li>

  <li><strong>Ladouceur, R.</strong>, Pierre, S., & Jaafar, F. (2022). Cyberguerre : géopolitique des infrastructures technologiques et des réseaux sociaux. Dans D. Uzunidis & L. Adatto (Dir.), Catastrophes majeures au XXIe siècle : Santé, environnement, alimentation, guerre (Collection Magna Carta). Éditions Le Manuscrit.</li>
</ul>

 <h3>Conference</h3>
<ul>
  <li>ACFAS, Intelligence artificielle et cyberinfluence, Congrès de l’Association francophone professionnelle pour le savoir (ACFAS), mai 2022.</li>
</ul>















  



    <!-- Section Enseignement (Teaching) -->
    <h2 id="teaching" style="margin-top: 40px;">Enseignement & Expérience (Teaching)</h2>
    <hr>
    <p>
       In parallel with my research, I teach in academia to share my practical expertise.
    </p>
    <ul class="teaching-list">
        <li>Summer 2026, <strong>GCGR2010 Cyber Governance and Risk Management</strong>, Graduate Diploma in Information Technology and Computer Science (TII), Université de technologie d’Haïti, 1 class of 19 students. 3-hour course (36 hours total).</li>

  <li>Winter 2026, <strong>GIS4020 Security Incident Management</strong> (including detection and response tools), Graduate Diploma in Information Technology and Computer Science (TII), Université de technologie d’Haïti, 1 class of 19 students. 3-hour course (36 hours total).</li>

  <li>Winter 2025, <strong>8INF970 Cybersecurity Workshop II</strong>, Department of Computer Science and Mathematics, Université du Québec à Chicoutimi, 1 class of 30 master’s students. 3-hour course (45 hours total). Evaluated by 8 students: 69 responses, 3.69/4, standard deviation: 0.53.</li>

  <li>Fall 2022 and 2024, <strong>8INF882 Security Incident Management </strong> (including detection and response tools), Department of Computer Science and Mathematics, Université du Québec à Chicoutimi, 1 class of 7 master’s students (2022) and 2 classes of 30 (2024). 3-hour course (4 hours per session total).</li>
    </ul>





    <!-- Section Curriculum Vitae -->
    <h2 id="cv" style="margin-top: 40px;">Curriculum Vitae</h2>
    <hr>
    <p>
        Vous pouvez consulter ou télécharger mon parcours académique et professionnel complet au format PDF :
    </p>
    
    <div>
        <a href="Cv.pdf" target="_blank" class="cv-button">
            📄 Télécharger mon CV (PDF)
        </a>
    </div>

  </div>
</div>

</body>
</html>




  









  


