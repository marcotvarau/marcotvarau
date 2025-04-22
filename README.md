<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marco Thulio – Full-Stack Engineer</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      padding: 2rem;
      max-width: 800px;
      margin: auto;
      color: #333;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }
    a {
      color: #1e90ff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    ul {
      list-style: none;
      padding: 0;
      display: flex;
      gap: 1.5rem;
    }
    ul li {
      margin: 0;
    }
    #tech-skills {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      margin-top: 1rem;
    }
    .tech-icon img {
      width: 160px;
      transition: transform 0.3s ease;
    }
    .tech-icon img:hover {
      transform: scale(1.1) rotate(5deg);
    }
    #dynamic {
      margin-top: 2rem;
      color: #555;
      font-style: italic;
      animation: fadeIn 4s ease-in-out infinite alternate;
    }
    @keyframes fadeIn {
      from { opacity: 0.5; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>
  <h1>Hi, I'm Marco Thulio</h1>
  <p>
    I am a <strong>Full-Stack Engineer</strong> at 
    <a href="https://islandinnovation.co" target="_blank" rel="noopener">Island Innovation</a>.
    I graduated in Control and Automation Engineering from 
    <a href="https://www.ufmg.br" target="_blank" rel="noopener">UFMG</a>.
  </p>

  <ul>
    <li><a href="https://www.marco-thulio.dev" target="_blank">Website</a></li>
    <li><a href="https://www.linkedin.com/in/marco-thulio" target="_blank">LinkedIn</a></li>
    <li><a href="mailto:marcothulio49@gmail.com">Email</a></li>
  </ul>

  <h2>Technologies I Work With</h2>
  <div id="tech-skills">
    <div class="tech-icon">
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    </div>
    <div class="tech-icon">
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
    </div>
    <div class="tech-icon">
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
    </div>
    <div class="tech-icon">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    </div>
    <div class="tech-icon">
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
    </div>
    <div class="tech-icon">
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
    </div>
    <div class="tech-icon">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
    </div>
    <div class="tech-icon">
      <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
    </div>
  </div>

  <p id="dynamic">Crafting code that powers impactful digital solutions.</p>

  <script>
    // Shuffle tech icons every 5 seconds for a dynamic effect
    const shuffleIcons = () => {
      const container = document.getElementById('tech-skills');
      for (let i = container.children.length; i >= 0; i--) {
        container.appendChild(container.children[Math.random() * i | 0]);
      }
    };
    setInterval(shuffleIcons, 5000);
  </script>
</body>
</html>
