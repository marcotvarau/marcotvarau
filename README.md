<!-- README.md -->

<!-- HTML profile snippet inside Markdown -->
<div lang="en">
  <h1>Hi, I'm Marco Thulio</h1>
  <p>
    I'm a <strong>Full-Stack Engineer</strong> at <a href="https://islandinnovation.co" target="_blank">Island Innovation</a>,
    with a degree in Control and Automation Engineering from <a href="https://www.ufmg.br" target="_blank">UFMG</a>.
  </p>
  
  <h2>📈 Career Highlights</h2>
  <ul>
    <li>
      <strong>BTG Pactual</strong><br/>
      <em>Business Intelligence Analyst</em> (2020–2022)<br/>
      <ul>
        <li>Developed FP&A dashboards in Power BI to support executive decision-making.</li>
        <li>Built forecasting models in Python (Pandas, Scikit-learn) for revenue and expense projections.</li>
        <li>Automated ETL pipelines using AWS Lambda and S3, reducing manual reporting by 70%.</li>
      </ul>
    </li>
    <li>
      <strong>CS Academy</strong><br/>
      <em>CRM & Data Analytics Instructor</em> (2018–2020)<br/>
      <ul>
        <li>Designed and delivered hands-on courses on HubSpot CRM and SQL for over 200 students.</li>
        <li>Created interactive Python notebooks and workshops for data cleaning and visualization.</li>
      </ul>
    </li>
    <li>
      <strong>LWSA</strong><br/>
      <em>Data Engineer</em> (2016–2018)<br/>
      <ul>
        <li>Built MongoDB and PostgreSQL data warehouses to centralize customer and sales data.</li>
        <li>Implemented data integration using Node.js and ETL frameworks for marketing automation.</li>
      </ul>
    </li>
    <li>
      <strong>Island Innovation</strong><br/>
      <em>Full-Stack Engineer</em> (2022–Present)<br/>
      <ul>
        <li>Develop and maintain global platforms with React, Next.js, and Tailwind CSS.</li>
        <li>Design REST APIs using Node.js (Express) and Python (FastAPI) with MongoDB backend.</li>
        <li>Orchestrate cloud deployments on AWS (EC2, Lambda, S3) and automate CI/CD with GitHub Actions.</li>
      </ul>
    </li>
  </ul>

  <h2>💻 Technologies I Use</h2>
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

  <h2>🎓 Education</h2>
  <p>Control and Automation Engineering, UFMG</p>

  <h2>📫 Contact & Links</h2>
  <ul>
    <li>🌐 <a href="https://www.marco-thulio.dev">marco-thulio.dev</a></li>
    <li>🔗 <a href="https://www.linkedin.com/in/marco-thulio">LinkedIn/marco-thulio</a></li>
    <li>✉️ <a href="mailto:marcothulio49@gmail.com">marcothulio49@gmail.com</a></li>
  </ul>

  <!-- Optional script for dynamic badge shuffle -->
  <script>
    const shuffleIcons = () => {
      const container = document.getElementById('tech-skills');
      for (let i = container.children.length; i >= 0; i--) {
        container.appendChild(container.children[Math.random() * i | 0]);
      }
    };
    setInterval(shuffleIcons, 5000);
  </script>
</div>
