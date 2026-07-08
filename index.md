---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Arup Datta - Home</title>
<style>
  /* This section controls the colors and layout */
  body {
    font-family: Georgia, "Times New Roman", serif;
    /* Ice Cold to Freeze Purple to Medium Purple */
    background: linear-gradient(to bottom right, #a0d2eb, #e5eaf5, #d0bdf4);
    background-attachment: fixed; /* Keeps the gradient smooth while scrolling */
    color: #111; /* Slightly softer than pure black for easier reading */
    margin: 0;
    padding: 0;
    line-height: 1.6;
    font-size: 18px;
  }
  .navbar {
    background-color: #8458B3; /* Purple Pain for the top bar */
    padding: 12px 20px;
  }
  .navbar a {
    color: white;
    text-decoration: none;
    margin-right: 25px;
    font-size: 18px;
    font-weight: bold;
  }
  .navbar a:hover {
    text-decoration: underline;
  }
  .container {
    max-width: 1100px;
    margin: 30px auto;
    padding: 0 20px;
  }
  .header-flex {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 40px;
  }
  .header-left {
    max-width: 68%;
  }
  .header-right img {
    max-width: 260px;
    border: 3px solid #8458B3; /* Adds a matching border to your photo */
    border-radius: 4px;
  }
  h1 {
    font-size: 34px;
    margin-top: 10px;
    margin-bottom: 20px;
    color: #8458B3; /* Purple Pain for your name */
  }
  h2 {
    font-size: 26px;
    color: #8458B3; /* Purple Pain for section headers */
    border-bottom: 2px solid #8458B3;
    padding-bottom: 5px;
    margin-top: 40px;
    margin-bottom: 20px;
  }
  h3 {
    font-size: 22px;
    color: #8458B3;
    margin-top: 30px;
  }
  p {
    margin-bottom: 15px;
  }
  .cv-table {
    width: 100%;
    border-collapse: collapse;
    font-size: 18px;
  }
  .cv-table td {
    padding: 6px 0;
    vertical-align: top;
  }
  .cv-date {
    width: 170px;
    font-weight: bold;
    color: #444;
  }
  a {
    color: #8458B3; /* Links match the theme */
    font-weight: bold;
  }
  a:hover {
    color: #111;
  }
  ul {
    margin-top: 5px;
    padding-left: 20px;
  }
  li {
    margin-bottom: 10px;
  }
</style>
</head>
<body>

<!-- TOP NAVIGATION BAR -->
<div class="navbar">
  <a href="#home">Home</a>
  <a href="#cv">CV</a>
  <a href="#notes">Mathematical Notes</a>
  <a href="#events">Conferences, Workshops & Schools</a>
</div>

<!-- MAIN CONTENT CONTAINER -->
<div class="container" id="home">
  
  <div class="header-flex">
    <div class="header-left">
      <h1>Arup Datta</h1>
      <p>
        School of Mathematics<br>
        International Centre for Theoretical Sciences (ICTS) - TIFR<br>
        Bengaluru, Karnataka, India<br>
        Phone: +91-9366810821<br>
        Email: arup.datta[at]icts.res.in
      </p>
      <p>I am a Ph.D. student at the School of Mathematics in the International Centre for Theoretical Sciences (ICTS), Bengaluru.</p>
      <p>My primary interest lies in the study of Lie groups and their discrete subgroups, particularly from the perspective of the interaction between algebra, geometry, and topology.</p>
    </div>
    
    <div class="header-right">
      <img src="profile.jpg" alt="Arup Datta Photo">
    </div>
  </div>

  <!-- CV SECTION -->
  <h2 id="cv">Short CV</h2>
  <table class="cv-table">
    <tr>
      <td class="cv-date">2024 – Present</td>
      <td><strong>Ph.D. in Mathematics</strong>, International Centre for Theoretical Sciences - TIFR, Bengaluru</td>
    </tr>
    <tr>
      <td class="cv-date">2016 – 2021</td>
      <td><strong>Integrated M.Sc. in Mathematics</strong>, Tripura University, Suryamaninagar</td>
    </tr>
  </table>

  <h3>Project</h3>
  <p><strong>Dirichlet’s Theorem on the Infinitude of Primes</strong></p>
  <ul>
    <li><a href="dirichlet-project.pdf">📄 Read Project Report (PDF)</a></li>
    <li><em>Abstract:</em> The objective of this project is to prove Dirichlet's theorem on the infinitude of primes. Along the way, we will study Dirichlet L-functions and explore the orthogonality relations of characters, which play a crucial role in the proof.</li>
  </ul>

  <!-- EVENTS SECTION -->
  <h2 id="events">Conferences, Workshops & Schools</h2>
  <ul>
    <li><strong>Nov - Dec 2020:</strong> Online Teachers Enrichment Workshop "Linear Algebra and its Applications", NCM (TIFR and IIT Bombay)</li>
    <li><strong>May - Jun 2020:</strong> Visiting Student's Research Programme (VSRP), TIFR Mumbai</li>
    <li><strong>Jan - Feb 2020:</strong> Winter School on Mathematics for M.Sc. students, ISI, North-East Centre, Tezpur</li>
    <li><strong>Jul 2019:</strong> International Conference on Recent Advances in Mathematics and its Applications (ICRAMA), Tripura University</li>
    <li><strong>2018, 2019, 2020:</strong> Mathematics Training and Talent Search Programme (MTTS)</li>
  </ul>

  <!-- NOTES SECTION -->
  <h2 id="notes">Mathematical Notes</h2>
  
  <h3>Core Subjects</h3>
  <ul>
    <li><strong>Advanced Topics Course (Topological groups and manifolds)</strong>
      <ul><li><a href="manifolds/">📝 View Notes on Manifolds</a></li></ul>
    </li>
    <li><strong>Algebra</strong>
      <ul><li>📝 Notes coming soon</li></ul>
    </li>
    <li><strong>Analysis 1 (Measure theory)</strong>
      <ul><li>📝 Notes coming soon</li></ul>
    </li>
    <li><strong>Topology</strong>
      <ul><li>📝 Notes coming soon</li></ul>
    </li>
    <li><strong>Algebra 2 (Field, Galois, and Representation theory)</strong>
      <ul><li>📝 Notes coming soon</li></ul>
    </li>
    <li><strong>Functional Analysis</strong>
      <ul><li>📝 Notes coming soon</li></ul>
    </li>
    <li><strong>Complex Analysis</strong>
      <ul><li>📝 Notes coming soon</li></ul>
    </li>
    <li><strong>Problem Solving Techniques in Analysis</strong></li>
    <li><strong>Probability Theory</strong>
      <ul><li>📝 Notes coming soon</li></ul>
    </li>
  </ul>

  <h3>Special Topics</h3>
  <ul>
    <li><strong>p-adic Fields</strong>
      <ul><li>📝 Notes coming soon</li></ul>
    </li>
  </ul>

</div>
</body>
</html>
