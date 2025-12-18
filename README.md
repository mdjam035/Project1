# Project1
Demo Project
Index.html
<!DOCTYPE html>
<html>
<head>
  <title>Team Portfolio</title>
  <link rel="stylesheet" href="style.css"
</head>
<body>
  <header>
    <h1>Welcome to Our Team Portfolio</h1>
  </header>
  <section id="team">
    <h2>Meet the Team</h2>
    <div class="profile">
      <h3>Alice</h3>
      <p>Frontend Developer</p>
    </div>
    <div class="profile">
      <h3>Bob</h3>
      <p>UI/UX Designer</p>
    </div>
    <div class="profile">
      <h3>Charlie</h3>
      <p>JavaScript Developer</p>
    </div>
  </section>
  <footer>Contact us at: team@example.com</footer>
  <script src="script.js"> </script>
</body>
</html>

Script.js
document.querySelectorAll('.profile').forEach(profile => {
    profile.addEventListener('mouseenter', () => {
      profile.style.backgroundColor = '#f0f0f0';
    });
    profile.addEventListener('mouseleave', () => {
      profile.style.backgroundColor = 'white';
    });
  });

Style.css
body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
header { background-color: #4CAF50; color: white; padding: 20px; text-align: center; }
.profile { margin: 20px; padding: 10px; border: 1px solid #ddd; }
footer { text-align: center; padding: 10px; background: #f1f1f1; }
Index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Collaboration</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Hello, World!</h1>
    <p id="message">This is a simple collaborative project.</p>
    <button id="changeMessage">Click Me!</button>
    <script src="script.js"></script>
</body>
</html>


Style.css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 0;
    padding: 0;
    background-color: #eef;
}

h1 {
    color: #333;
}

button {
    margin-top: 20px;
    padding: 10px 15px;
    font-size: 16px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
button:hover {
    background-color: #0056b3;
}


Script.js
document.getElementById("changeMessage").addEventListener("click", function() {
    document.getElementById("message").textContent = "You clicked the button!";
});
**/index.html**
<html>
<head><title>Team Portfolio</title></head>
<body>
  <h1>Welcome to Our Team Portfolio</h1>
  <p>Content will go here.</p>
</body>
</html>

**/styles.css**
body { font-family: Arial, sans-serif; background-color: #f0f0f0; } 
h1 { color: navy; }

**/script.js**
document.addEventListener('DOMContentLoaded', () => {
  alert('Welcome to the Team Portfolio!');
});
