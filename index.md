---
layout: default
title: Nina Thoni
---

<section>
  <h1>Data Scientist</h1>
  <h4><strong>Technical Skills:</strong> Python, SQL, Azure, FastAPI, Llama3, React, GitHub Actions, Polars, PostgreSQL, Docker</h4>
  <hr />

  <div class="tab-container">
    <div class="tab-buttons">
      <div class="tab-link active" onclick="openTab(event, 'experience')">Work Experience</div>
      <div class="tab-link" onclick="openTab(event, 'projects')">Portfolio</div>
      <div class="tab-link" onclick="openTab(event, 'education')">Education</div>
    
   </div>

    <div id="experience" class="tab-content" style="display: block;">
    <h2 id="lead-data-scientist--pogust-goodhead-may-2023---jan-2025">
        <strong>Lead Data Scientist @ Pogust Goodhead (<em>May 2023 - Jan 2025</em>)</strong>
    </h2>
    <ul>
        <li>
        <p>Led the development of <strong>Generative AI tools</strong> to streamline case management and lawyer productivity.</p>
        </li>
        <li>
        <p>Designed <strong>AI-powered email &amp; document automation</strong> using <strong>RAG-based applications (Llama3)</strong>, integrated with <strong>Azure Functions, Power Automate, and Azure AI Search</strong>.</p>
        </li>
        <li>
        <p>Built an <strong>LLM-driven classification system</strong> for legal expenses, automating <strong>150,000+ time entry categorizations</strong>, reducing operational costs.</p>
        </li>
    </ul>
    <p><strong>Tech Stack:</strong> Llama3, RAG, Python, Azure AI Search, Azure Functions, Azure Blob Storage, Azure Databricks, Power Automate, CI/CD, PostgreSQL, Docker</p>

    <h2 id="data-scientist--artefact-jan-2022---may-2023">
        <strong>Data Scientist @ Artefact (<em>Jan 2022 - May 2023</em>)</strong>
    </h2>
    <ul>
        <li>
        <p>Developed an <strong>ML pipeline</strong> in <strong>Azure Databricks</strong> to classify <strong>500,000+ Heineken retail locations</strong>, improving segmentation accuracy.</p>
        </li>
        <li>
        <p>Designed <strong>FB Prophet-based forecasting models</strong> for audience size prediction, optimizing <strong>Sanofi’s paid media investments</strong>.</p>
        </li>
    </ul>
    <p><strong>Tech Stack:</strong> Azure Databricks, MLflow, PySpark, Scikit-learn, FB Prophet, Python</p>

    <h2 id="data-analyst--keener-innovations-jan-2021---jul-2021">
        <strong>Data Analyst @ Keener Innovations (<em>Jan 2021 - Jul 2021</em>)</strong>
    </h2>
    <ul>
        <li>
        <p>Built a <strong>cost management system</strong> that streamlined financial tracking, enhancing decision-making processes at the startup.</p>
        </li>
        <li>
        <p>Contributed to HR initiatives by creating <strong>culture frameworks</strong>, bonus structures, and partnership programs to drive organizational alignment.</p>
        </li>
    </ul>

    <h2 id="business-intelligence-intern--anheuser-busch-inbev-jan-2019---aug-2020">
        <strong>Business Intelligence Intern @ Anheuser-Busch InBev (<em>Jan 2019 - Aug 2020</em>)</strong>
    </h2>
    <ul>
        <li>
        <p>Analyzed <strong>sales metrics (volume, market share, pricing)</strong> using SQL &amp; Power BI, supporting executive decision-making.</p>
        </li>
    </ul>

    <hr />
    <h2><strong>Leadership &amp; Achievements</strong></h2>
    <h2><strong>Project Leader @ Anheuser-Busch InBev (<em>Jul 2019 – Oct 2019</em>)</strong></h2>
    <ul>
        <li>Led a <strong>team of 5 interns</strong> on a university alcohol responsibility campaign.</li>
        <li>Recognized as the <strong>top project among 200+ teams</strong>, selected for presentation at ABI’s NY headquarters (cancelled due to COVID).</li>
    </ul>
    <h2><strong>Projects Director @ Meta Consultoria (<em>Jan 2018 – Jan 2019</em>)</strong></h2>
    <ul>
        <li>Managed <strong>35 engineering students</strong>, delivering consulting projects for external clients.</li>
        <li>Supervised <strong>project quality, team mentoring, and client negotiations</strong>.</li>
    </ul>
    </div>

    <div id="projects" class="tab-content">

    <h2><strong>Digit Recognizer App</strong></h2>
    <p><strong>Mar 2025</strong> | <strong><a href="https://github.com/NinaThoni/digit-recognizer-app" target="_blank">GitHub Repo</a></strong></p>
    <ul>
        <li>Built an interactive <strong>Streamlit web app</strong> for digit recognition using a <strong>pre-trained CNN model</strong> on the MNIST dataset.</li>
        <li>Users can draw digits in the browser and log predictions with true labels to a <strong>PostgreSQL database</strong>.</li>
        <li>Deployed a fully containerized solution using <strong>Docker Compose</strong> on an <strong>Azure virtual machine</strong>.</li>
    </ul>
    <p><strong>Tech Stack:</strong> Python, PyTorch, Streamlit, PostgreSQL, Docker, Azure</p>
    <img class="project-img" src="/assets/img/digit_recognizer_app.png" alt="Digit Recognizer Preview">
    

    <h2><strong>Air Quality Chatbot</strong></h2>
    <p><strong>Feb 2025</strong> | <strong><a href="#">Front-End GitHub Repo</a></strong> | <strong><a href="#">Back-End GitHub Repo</a></strong></p>
    <ul>
        <li>Built a <strong>React + FastAPI chatbot</strong> that provides real-time <strong>air quality insights</strong> using <strong>LLM (Mistral via Hugging Face API)</strong>.</li>
        <li>Data is sourced from the <strong>TfL API</strong>, stored in <strong>PostgreSQL (Aiven)</strong>, and updated via <strong>GitHub Actions</strong>.</li>
        <li><strong>Deployed FastAPI on Azure App Service</strong> and <strong>React on Azure Static Web Apps</strong>.</li>
    </ul>
    <p><strong>Tech Stack:</strong> React, FastAPI, PostgreSQL, Azure, Ollama (LLM), TfL API, GitHub Actions, Bootstrap, Polars, Node.js</p>
    <img class="project-img" src="/assets/img/air_quality_app.png" alt="Air Quality Chatbot Preview">
    </div>

    <div id="education" class="tab-content">

    <h2><strong>MSc in Data Science, University of Westminster (Sep 2022)</strong></h2>
    <p>Thesis Project: LSTM vs. ARIMA Model in Forecasting iShares Ibovespa Index Fund (BOVA11)</p>
    <ul>
        <li><strong>Developed forecasting models</strong> using <strong>Python</strong>, comparing classical time series methods against deep learning.</li>
        <li><strong>Analyzed time series components</strong> (seasonality, trends) to optimize model performance.</li>
        <li><strong>Evaluated model accuracy</strong> using RMSE and other forecasting metrics.</li>
    </ul>

    <h2><strong>BSc in Production Engineering, Universidade Federal Fluminense (Dec 2020)</strong></h2>
    <p>Final Project: Vehicle Routing Problem Optimization with Genetic Algorithms<br />
    Developed an <strong>AI-driven solution</strong> for optimizing delivery routes, comparing it to classical Linear Programming techniques.</p>
    <ul>
        <li><strong>Implemented the Genetic Algorithm</strong> to improve vehicle routing efficiency.</li>
        <li><strong>Compared AI-based vs. Linear Programming approaches</strong> to assess computational efficiency and solution quality.</li>
        <li><strong>Used Python for modeling and simulation</strong>, applying real-world logistics data.</li>
    </ul>
    </div>
</div>

<script>
  function openTab(evt, tabName) {
    const tabContents = document.getElementsByClassName("tab-content");
    const tabLinks = document.getElementsByClassName("tab-link");

    for (let i = 0; i < tabContents.length; i++) {
      tabContents[i].style.display = "none";
    }

    for (let i = 0; i < tabLinks.length; i++) {
      tabLinks[i].classList.remove("active");
    }

    document.getElementById(tabName).style.display = "block";
    evt.currentTarget.classList.add("active");
  }
</script>
