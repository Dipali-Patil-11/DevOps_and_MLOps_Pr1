# DevOps_and_MLOps_Pr1
Web Application Deployment using HTML,CSS,Javascript and Deploy on Github.

[Start]
 |
Create Project Folder
 |
Create HTML / CSS / JS Files
 |
Design UI (HTML + CSS)
 |
Add JavaScript Logic
 |
Test Locally
 |
Create GitHub Repository
 |
Upload Project Files
 |
Enable GitHub Pages
 |
Website Live
 |
[End]
---------------------------------------------------------------------------------------
STEP 1: Create folder my-web-app
Create files:
index.html
style.css
script.js
------------------------------------------------------------------------------------------
STEP 2: HTML CODE (index.html)
<!DOCTYPE html>
<html>
  <head>
    <title>Student DevOps Project</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header>
      <h1>My DevOps Web Application</h1>
      <p>HTML • CSS • JavaScript • GitHub</p>
    </header>
    <nav>
      <a href="#">Home</a>
      <a href="#">Services</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
    <section class="hero">
      <h2>Welcome</h2>
      <p>This project demonstrates web development and GitHub deployment.</p>
      <button onclick="showMessage()">Click Me</button>
      <p id="msg"></p>
    </section>
    <section class="cards">
      <div class="card">Fast Deployment</div>
      <div class="card">Simple UI</div>
      <div class="card">DevOps Ready</div>
    </section>
    <footer>
      <p>© 2026 Student Project</p>
    </footer>
    <script src="script.js"></script>
  </body>
</html>
-------------------------------------------------------------------------------------------------
STEP 3: CSS CODE (style.css)
body {
  margin: 0;
  font-family: Arial;
  background: #f4f6f9;
}

header {
  background: #1f2933;
  color: white;
  padding: 20px;
  text-align: center;
}

nav {
  background: #3b82f6;
  padding: 10px;
  text-align: center;
}

nav a {
  color: white;
  margin: 15px;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 40px;
}

button {
  padding: 12px 25px;
  background: #3b82f6;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 16px;
}

.cards {
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 20px;
}

.card {
  background: white;
  padding: 20px;
  width: 150px;
  text-align: center;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
  background: #1f2933;
  color: white;
  text-align: center;
  padding: 10px;
}
-------------------------------------------------------------------------------------------------
STEP 4: JAVASCRIPT CODE (script.js)
function showMessage() {
  document.getElementById("msg").innerHTML = "Website deployed successfully using GitHub Pages!";
}
----------------------------------------------------------------------------------------------------
STEP 5: Open index.html in browser.
---------------------------------------------------------------------------------------------------
STEP 6: Create GitHub Repository named my-web-app
----------------------------------------------------------------------------------------------------
STEP 7: Upload all files and Commit.



----------------------------------------------------------------------------------------------------
STEP 8: Settings → Pages → Main Branch → Save.
----------------------------------------------------------------------------------------------------
RESULT:
Modern responsive web application deployed successfully.
