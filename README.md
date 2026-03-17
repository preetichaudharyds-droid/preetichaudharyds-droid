## Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Data Scientist Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>

<header>
  <h1>Hi, I'm Preeti </h1>
  <p>Aspiring Data Scientist | Python | SQL | Machine Learning</p>
</header>

<section class="hero">
  <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71" alt="Data Science Image">
</section>

<section class="about">
  <h2>About Me</h2>
  <p>I am a passionate data science enthusiast skilled in Python, SQL, and Machine Learning. I love turning data into actionable insights.</p>
</section>

<section class="skills">
  <h2>Skills</h2>
  <ul>
    <li>Python</li>
    <li>SQL</li>
    <li>Pandas & NumPy</li>
    <li>Machine Learning</li>
    <li>Data Visualization</li>
  </ul>
</section>

<section class="projects">
  <h2>Projects</h2>
  <div class="project-card">
    <h3>Sales Prediction Model</h3>
    <p>Built a machine learning model to predict sales using regression techniques.</p>
  </div>
  <div class="project-card">
    <h3>Customer Segmentation</h3>
    <p>Used clustering algorithms to segment customers based on behavior.</p>
  </div>
</section>

<section class="contact">
  <h2>Contact</h2>
  <p>Email: preetichaudhary.ds@gmail.com</p>
  <p>GitHub: </p>
</section>

<footer>
  <p>© 2026 Your Name</p>
</footer>

</body>
</html>


/* styles.css */
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: #0f172a;
  color: white;
}

header {
  text-align: center;
  padding: 50px 20px;
  background: linear-gradient(90deg, #06b6d4, #3b82f6);
}

.hero img {
  width: 100%;
  height: 400px;
  object-fit: cover;
}

section {
  padding: 40px;
  text-align: center;
}

.skills ul {
  list-style: none;
  padding: 0;
}

.skills li {
  display: inline-block;
  margin: 10px;
  padding: 10px 20px;
  background: #1e293b;
  border-radius: 20px;
}

.project-card {
  background: #1e293b;
  margin: 20px auto;
  padding: 20px;
  border-radius: 10px;
  width: 80%;
}

footer {
  background: #020617;
  padding: 20px;
  text-align: center;
}
