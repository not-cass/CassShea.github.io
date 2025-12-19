# CassShea.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Cass Shea – Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f7f7f7;
  color: #222;
}

header {
  text-align: center;
  padding: 3rem 1rem;
}

main {
  max-width: 900px;
  margin: auto;
  padding: 1rem;
}

.project {
  background: white;
  padding: 1.5rem;
  margin-bottom: 2rem;
  border-radius: 8px;
}

.project img,
.project video {
  width: 100%;
  margin-top: 1rem;
  border-radius: 4px;
}

button.toggle {
  background: none;
  border: 1px solid #222;
  padding: 0.5rem 1rem;
  cursor: pointer;
  margin-bottom: 0.5rem;
}

button.toggle:hover {
  background: #222;
  color: white;
}

.hidden {
  display: none;
}

a {
  display: inline-block;
  margin-top: 0.75rem;
}


<header>
  <h1>Cass Shea</h1>
  <p>Portfolio</p>
</header>

<main>

  <!-- PROJECT 1 -->
  <section class="project">
    <h2>Project 1</h2>

    <button class="toggle">View Project Statement</button>
    <p class="statement hidden">
      This project explores visual composition through Illustrator, focusing on
      form, color, and conceptual clarity.
    </p>

    <img src="images/project1.jpg" alt="Project 1 image">

    <a href="https://drive.google.com/your-illustrator-link" target="_blank">
      View .AI File (Google Drive)
    </a>
  </section>

  <!-- PROJECT 2 -->
  <section class="project">
    <h2>Project 2</h2>

    <button class="toggle">View Project Statement</button>
    <p class="statement hidden">
      This project focuses on photo manipulation and layering techniques using Photoshop.
    </p>

    <img src="images/project2.jpg" alt="Project 2 image">

    <a href="https://drive.google.com/your-psd-link" target="_blank">
      View .PSD File (Google Drive)
    </a>
  </section>

  <!-- PROJECT 3 -->
  <section class="project">
    <h2>Project 3: Moving Image</h2>

    <button class="toggle">View Project Statement</button>
    <p class="statement hidden">
      A time-based project exploring motion, pacing, and visual rhythm.
    </p>

    <video controls>
      <source src="images/project3.mp4" type="video/mp4">
      Your browser does not support video.
    </video>
  </section>

  <!-- PROJECT 4 -->
  <section class="project">
    <h2>Project 4: 3D Model</h2>

    <button class="toggle">View Project Statement</button>
    <p class="statement hidden">
      A 3D exploration of form and spatial relationships.
    </p>

    <img src="images/project4.jpg" alt="Project 4 image">
  </section>

</main>

<script src="script.js"></script>
</body>
</html>
