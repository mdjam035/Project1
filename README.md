# Project1
Demo Project
Index.html


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
