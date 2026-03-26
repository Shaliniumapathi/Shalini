<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me</title>
  
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(120deg, #1e3c72, #2a5298);
      color: #fff;
      text-align: center;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }

    h1 {
      font-size: 2.5rem;
      animation: fadeIn 1.5s ease-in-out;
    }

    .section {
      background: rgba(255,255,255,0.1);
      padding: 20px;
      border-radius: 15px;
      margin-top: 25px;
      animation: slideUp 1.5s ease-in-out;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .skill-card {
      padding: 15px;
      border-radius: 12px;
      background: rgba(255,255,255,0.1);
      transition: 0.3s;
    }

    .skill-card:hover {
      transform: translateY(-8px);
      background: rgba(255,255,255,0.2);
    }

    .skill-card i {
      font-size: 28px;
      margin-bottom: 10px;
      color: #ffd700;
    }

    .progress {
      height: 6px;
      background: rgba(255,255,255,0.2);
      border-radius: 10px;
      overflow: hidden;
      margin-top: 8px;
    }

    .progress-bar {
      height: 100%;
      background: #ffd700;
      animation: load 2s ease-in-out;
    }

    .projects {
      text-align: left;
    }

    .project-item {
      margin: 10px 0;
      padding: 10px;
      border-left: 4px solid #ffd700;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideUp {
      from { transform: translateY(40px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes load {
      from { width: 0; }
    }

  </style>
</head>
<body>

  <div class="container">

    <h1>Hi, I'm Your Name 👋</h1>
    <p>Full Stack Developer | MERN Stack | AI Enthusiast</p>

    <!-- Summary -->
    <div class="section">
      <h2>Summary</h2>
      <p>
        Passionate Full Stack Developer skilled in building responsive web applications using MERN stack.
        Interested in AI tools and modern UI/UX design.
      </p>
    </div>

    <!-- Skills -->
    <div class="section">
      <h2>Skills</h2>

      <div class="skills-grid">

        <div class="skill-card">
          <i class="fa-brands fa-html5"></i>
          <p>HTML</p>
          <div class="progress"><div class="progress-bar" style="width: 90%"></div></div>
        </div>

        <div class="skill-card">
          <i class="fa-brands fa-css3-alt"></i>
          <p>CSS</p>
          <div class="progress"><div class="progress-bar" style="width: 85%"></div></div>
        </div>

        <div class="skill-card">
          <i class="fa-brands fa-js"></i>
          <p>JavaScript</p>
          <div class="progress"><div class="progress-bar" style="width: 80%"></div></div>
        </div>

        <div class="skill-card">
          <i class="fa-brands fa-react"></i>
          <p>React</p>
          <div class="progress"><div class="progress-bar" style="width: 75%"></div></div>
        </div>

        <div class="skill-card">
          <i class="fa-brands fa-node-js"></i>
          <p>Node.js</p>
          <div class="progress"><div class="progress-bar" style="width: 70%"></div></div>
        </div>

        <div class="skill-card">
          <i class="fa-solid fa-server"></i>
          <p>Express.js</p>
          <div class="progress"><div class="progress-bar" style="width: 70%"></div></div>
        </div>

        <div class="skill-card">
          <i class="fa-solid fa-leaf"></i>
          <p>MongoDB</p>
          <div class="progress"><div class="progress-bar" style="width: 65%"></div></div>
        </div>

      </div>
    </div>

    <!-- Projects -->
    <div class="section projects">
      <h2>Backend Projects</h2>

      <div class="project-item">
        <strong>Employee Management System</strong><br>
        Built REST APIs using Node.js & Express with CRUD operations.
      </div>

      <div class="project-item">
        <strong>AI Resume Analyzer</strong><br>
        Backend integration for analyzing resumes using AI APIs.
      </div>

      <div class="project-item">
        <strong>E-commerce Backend</strong><br>
        Developed product, user authentication and order APIs.
      </div>

    </div>

  </div>

</body>
</html>
