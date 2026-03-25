<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Supuni Kaushalya Jayarathne | Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #0a0a0a; /* Deep dark background */
      color: #ffffff;
      scroll-behavior: smooth;
    }

    h1, h2, h3 {
      margin: 0.5em 0;
      text-shadow: 0 0 5px #ff7bd5, 0 0 10px #ff7bd5, 0 0 20px #9d7bff;
    }

    /* Gradient bar animation */
    .gradient-bar img {
      width: 100%;
      display: block;
    }

    /* Floating animation */
    @keyframes floating {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-15px); }
      100% { transform: translateY(0px); }
    }

    .floating-img {
      border-radius: 20px;
      box-shadow: 0 0 15px #ff7bd5, 0 0 30px #9d7bff;
      animation: floating 3s ease-in-out infinite;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .floating-img:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px #ff7bd5, 0 0 40px #7bdcff;
    }

    /* Centered container */
    .center {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
      margin: 20px 0;
    }

    /* Neon Tech Stack Cards */
    table {
      width: 90%;
      margin: auto;
      text-align: center;
      border-collapse: collapse;
    }

    table img {
      margin: 10px;
      transition: transform 0.3s, filter 0.3s;
      filter: drop-shadow(0 0 5px #ff7bd5) drop-shadow(0 0 10px #7bdcff);
    }

    table img:hover {
      transform: scale(1.2);
      filter: drop-shadow(0 0 10px #ff7bd5) drop-shadow(0 0 20px #7bdcff);
    }

    /* Badges */
    .badges a img {
      margin: 5px;
      filter: drop-shadow(0 0 5px #ff7bd5) drop-shadow(0 0 10px #7bdcff);
      transition: transform 0.3s;
    }

    .badges a img:hover {
      transform: scale(1.1);
    }

    /* Section separator */
    hr {
      border: 1px solid #333;
      margin: 40px 0;
    }

    /* About & Connect section */
    .section {
      text-align: center;
      max-width: 900px;
      margin: auto;
      padding: 10px;
    }

    /* Links */
    a {
      text-decoration: none;
    }

    /* Neon text effect for highlights */
    .neon-text {
      color: #ff7bd5;
      text-shadow: 0 0 5px #ff7bd5, 0 0 10px #9d7bff, 0 0 20px #7bdcff;
    }

    /* Dark card background for tech stack */
    table td {
      background: #111;
      border-radius: 15px;
      padding: 15px;
      margin: 10px;
    }
  </style>
</head>
<body>

  <!-- Animated Gradient Background -->
  <div class="gradient-bar">
    <img src="https://raw.githubusercontent.com/supuni2006/assets/main/gradient-bar.gif" alt="Gradient Bar" />
  </div>

  <!-- Header -->
  <h1 align="center">✨ I'm <span class="neon-text">Supuni Kaushalya Jayarathne</span> ✨</h1>
  <div align="center">
    <img src="https://drive.google.com/uc?id=14xqv5Vq1iSHgQblRQwoVmMGU7XPq05u4" width="30px"/>
  </div>

  <!-- Floating Images -->
  <div class="center">
    <img src="https://drive.google.com/uc?id=1z7qDiym-ygiSM3F4u1xDKgxSeH0-qAfM" width="250px" class="floating-img" style="animation-duration:3s;"/>
    <img src="https://drive.google.com/uc?id=1qzjjmpa6oY9a3xq3mCqWoufaMO5LgDMs" height="200px" class="floating-img" style="animation-duration:3.2s;"/>
    <img src="https://drive.google.com/uc?id=14xqv5Vq1iSHgQblRQwoVmMGU7XPq05u4" width="230px" class="floating-img" style="animation-duration:3.4s;"/>
  </div>

  <!-- About Me -->
  <div class="section">
    <p>I am an Undergraduate Student at <b class="neon-text">IIT Sri Lanka</b>, passionate about <b class="neon-text">Software Development</b> and continuously improving my skills 🌱</p>
  </div>

  <hr>

  <!-- About Me Details -->
  <div class="section">
    <h2>🌸 About Me</h2>
    <ul style="list-style:none; padding:0;">
      <li>🔭 Seeking internship opportunities</li>
      <li>🌱 Learning <b class="neon-text">Python, Java, Web Development</b>, and problem-solving</li>
      <li>📫 Contact: <b class="neon-text">supuni2006k@gmail.com</b></li>
      <li>⚡ Fun fact: I love <b class="neon-text">designing, sports, and creative tech ideas!</b></li>
    </ul>
  </div>

  <hr>

  <!-- Tech Stack -->
  <div class="section">
    <h2>🎨 Tech Stack</h2>
    <table>
      <tr>
        <td width="33%">
          <h3>🌈 Frontend</h3>
          <img src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/bootstrap-plain.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/tailwindcss.svg" height="50"/>
        </td>
        <td width="33%">
          <h3>💫 Backend</h3>
          <img src="https://profilinator.rishav.dev/skills-assets/nodejs-original-wordmark.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/mongodb-original-wordmark.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/express-original-wordmark.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/mysql-original-wordmark.svg" height="50"/>
        </td>
        <td width="33%">
          <h3>⭐ Languages</h3>
          <img src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/python-original.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/java-original.svg" height="50"/>
          <img src="https://profilinator.rishav.dev/skills-assets/php-original.svg" height="50"/>
        </td>
      </tr>
    </table>
  </div>

  <hr>

  <!-- Connect -->
  <div class="section badges">
    <h2>💗 Connect With Me</h2>
    <div align="center">
      <a href="https://github.com/supuni2006" target="_blank">
        <img src="https://img.shields.io/badge/github-000000?style=for-the-badge&logo=github&logoColor=white" />
      </a>
      <a href="https://www.linkedin.com/in/supuni-kaushalya-9140a12a6/" target="_blank">
        <img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
      </a>
      <a href="https://www.instagram.com/supu_jayarathne/" target="_blank">
        <img src="https://img.shields.io/badge/instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
      </a>
    </div>
    <br>
    <div align="center">
      <img src="https://komarev.com/ghpvc/?username=supuni2006&&style=flat-square" />
    </div>
  </div>

</body>
</html>
