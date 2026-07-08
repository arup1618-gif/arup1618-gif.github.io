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
    background-color: #fdfaf0; /* Pale beige color like the screenshot */
    color: #000;
    margin: 0;
    padding: 0;
    line-height: 1.5;
  }
  .navbar {
    background-color: #777; /* Gray top bar */
    padding: 8px 20px;
  }
  .navbar a {
    color: white;
    text-decoration: none;
    margin-right: 25px;
    font-size: 15px;
  }
  .navbar a:hover {
    text-decoration: underline;
  }
  .container {
    max-width: 1100px;
    margin: 20px auto;
    padding: 0 20px;
  }
  .header-flex {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 30px;
  }
  .header-left {
    max-width: 70%;
  }
  .header-right img {
    max-width: 250px;
    border: 1px solid #ccc;
  }
  h1 {
    font-size: 22px;
    margin-top: 10px;
    margin-bottom: 20px;
  }
  h2 {
    font-size: 18px;
    border-bottom: 1px solid #ccc;
    padding-bottom: 5px;
    margin-top: 30px;
    margin-bottom: 15px;
  }
  p {
    font-size: 15px;
    margin-bottom: 15px;
  }
  .cv-table {
    width: 100%;
    border-collapse: collapse;
    font-size: 15px;
  }
  .cv-table td {
    padding: 4px 0;
    vertical-align: top;
  }
  .cv-date {
    width: 160px;
  }
  a {
    color: #000;
  }
  ul {
    margin-top: 5px;
    padding-left: 20px;
    font-size: 15px;
  }
  li {
    margin-bottom: 6px;
  }
</style>
</head>
<body>

<!-- TOP NAVIGATION BAR -->
<div class="navbar">
  <a href="#home">Home</a>
  <a href="#cv">CV</a>
  <a href="#notes">Coursework & Notes</a>
  <a href="#events">Events</a>
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
      <td><strong>Ph.D. in Mathematics</strong>, International Centre for Theoretical Sciences - TIFR, Bengaluru <em>(Expected: 2029)</em></td>
    </tr>
    <tr>
      <td class="cv-date">2016 – 2021</td>
      <td><strong>Integrated M.Sc. in Mathematics</strong>, Tripura University, Suryamaninagar <em>(Percentage: 90.1)</em></td>
    </tr>
  </table>

  <h3>Research Project</h3>
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
  <h2 id="notes">PhD Coursework & Lecture Notes</h2>
  <ul>
    <li><strong>Advanced Topics Course (Topological groups and manifolds)</strong>
      <ul><li><a href="manifolds/">📝 View Notes on Manifolds</a></li></ul>
    </li>
    <li><strong>Probability Theory</strong>
      <ul><li>📝 Notes coming soon</li></ul>
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
  </ul>

</div>
</body>
</html>
