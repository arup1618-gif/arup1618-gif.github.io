---
layout: null
---
<style>
  body {
    font-family: Georgia, "Times New Roman", serif;
    background: linear-gradient(to bottom right, #a0d2eb, #e5eaf5, #d0bdf4);
    background-attachment: fixed; 
    color: #111; 
    margin: 0;
    padding: 0;
    line-height: 1.6;
    font-size: 16px; /* Changed from 18px to standard 16px */
  }
  .navbar {
    background-color: #8458B3; 
    padding: 12px 20px;
  }
  .navbar a {
    color: white;
    text-decoration: none;
    margin-right: 25px;
    font-size: 16px; /* Changed to match body text */
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
    border: 3px solid #8458B3; 
    border-radius: 4px;
  }
  h1 {
    font-size: 32px; /* Scaled down slightly */
    margin-top: 10px;
    margin-bottom: 20px;
    color: #8458B3; 
  }
  h2 {
    font-size: 24px; /* Scaled down slightly */
    color: #8458B3; 
    border-bottom: 2px solid #8458B3;
    padding-bottom: 5px;
    margin-top: 40px;
    margin-bottom: 20px;
  }
  h3 {
    font-size: 20px; /* Scaled down slightly */
    color: #8458B3;
    margin-top: 30px;
  }
  p {
    margin-bottom: 15px;
  }
  .cv-table {
    width: 100%;
    border-collapse: collapse;
    font-size: 16px; /* Changed to match body text */
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
    color: #8458B3; 
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

<div class="navbar">
  <a href="index.html">Home</a>
  <a href="index.html#cv">Education</a>
  <a href="index.html#events">Conferences & Schools</a>
  <a href="notes.html">Mathematical Notes</a>
  <a href="personal.html">Beyond Maths</a>
</div>

<div class="container" id="home">
  
  <div class="header-flex">
    <div class="header-left">
      <h1>Arup Datta</h1>
      <p>
        School of Mathematics<br>
        International Centre for Theoretical Sciences (ICTS) - TIFR<br>
        Bengaluru, Karnataka, India<br>
        Email: arup.datta[at]icts.res.in
      </p>
      <p>I am a Ph.D. student at the School of Mathematics in the International Centre for Theoretical Sciences (ICTS), Bengaluru.</p>
      <p>My primary interest lies in the study of Lie groups and their discrete subgroups, particularly from the perspective of the interaction between algebra, geometry, and topology.</p>
    </div>
    
    <div class="header-right">
      <img src="profile.jpg" alt="Arup Datta Photo">
    </div>
  </div>

  <h2 id="cv">Education</h2>
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

  <h2>Scholarships & Awards</h2>
  <ul>
    <li><strong>ISHAN UDAY</strong> Special Scholarship Scheme for North Eastern Region (2016 – 2021)</li>
  </ul>

  <h2>Mentorship Experience</h2>
  <ul>
    <li><strong>Oct – Nov 2022:</strong> Mentor, Online Foundation Course in Mathematics (OFCM), MTTS Trust</li>
    <li><strong>Jun – Jul 2021:</strong> Mentor, Mathematics Training and Talent Search Programme (MTTS)</li>
    <li><strong>Oct 2020:</strong> Mentor, Online Foundation Course in Mathematics (OFCM), MTTS Trust</li>
  </ul>

  <h2 id="events">Conferences, Workshops & Schools</h2>
  <ul>
    <li><strong>06 - 10 Jul 2026:</strong> Automorphic forms: Arithmetic and Representation Theoretical Aspects, ICTS Bengaluru</li>
    <li><strong>Nov - Dec 2020:</strong> Online Teachers Enrichment Workshop "Linear Algebra and its Applications", NCM (TIFR and IIT Bombay)</li>
    <li><strong>May - Jun 2020:</strong> Visiting Student's Research Programme (VSRP), TIFR Mumbai</li>
    <li><strong>Jan - Feb 2020:</strong> Winter School on Mathematics for M.Sc. students, ISI, North-East Centre, Tezpur</li>
    <li><strong>Jul 2019:</strong> International Conference on Recent Advances in Mathematics and its Applications (ICRAMA), Tripura University</li>
    <li><strong>2018, 2019, 2020:</strong> Mathematics Training and Talent Search Programme (MTTS)</li>
  </ul>

</div>
