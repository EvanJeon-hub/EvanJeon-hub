<div>
  
  ![header](https://capsule-render.vercel.app/api?type=Blur&fontColor=d6ace6&height=300&section=header&text=Good%20to%20see%20you%20%F0%9F%A4%97&animation=blinking)
  <canvas>
            
  </canvas>
  * {margin: 0; padding: 0}
  body {background: #000;}
  canvas {display: block;}

  // Initialising the canvas
var canvas = document.querySelector('canvas'),
    ctx = canvas.getContext('2d');

// Setting the width and height of the canvas
canvas.width = window.innerWidth;
canvas.height = window.innerHeight;

// Setting up the letters
var letters = 'ABCDEFGHIJKLMNOPQRSTUVXYZABCDEFGHIJKLMNOPQRSTUVXYZABCDEFGHIJKLMNOPQRSTUVXYZABCDEFGHIJKLMNOPQRSTUVXYZABCDEFGHIJKLMNOPQRSTUVXYZABCDEFGHIJKLMNOPQRSTUVXYZ';
letters = letters.split('');

// Setting up the columns
var fontSize = 10,
    columns = canvas.width / fontSize;

// Setting up the drops
var drops = [];
for (var i = 0; i < columns; i++) {
  drops[i] = 1;
}

// Setting up the draw function
function draw() {
  ctx.fillStyle = 'rgba(0, 0, 0, .1)';
  ctx.fillRect(0, 0, canvas.width, canvas.height);
  for (var i = 0; i < drops.length; i++) {
    var text = letters[Math.floor(Math.random() * letters.length)];
    ctx.fillStyle = '#0f0';
    ctx.fillText(text, i * fontSize, drops[i] * fontSize);
    drops[i]++;
    if (drops[i] * fontSize > canvas.height && Math.random() > .95) {
      drops[i] = 0;
    }
  }
}

// Loop the animation
setInterval(draw, 33);

</div>  

  <div align="center">
  <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🧑‍💻 Contact me 🧑‍💻 </h2>
  <div align="center">
    <a href="https://www.instagram.com/evan_escn">
      <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=Instagram&logoColor=white">
    </a>
    <a href="mailto:ejeon2@uci.edu">
      <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white">
    </a>
    <a href="https://www.linkedin.com/in/soobin-jeon-28070a2bb/">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=LinkedIn&logoColor=white">
    </a>
    <a href="https://discord.com/users/evan_escn">
      <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
    </a>
  </div>
</div>
      
  ## 👀 About Me
  #### :raising_hand: I am a Freshman Student at the University of California, Irvine<br/>
  #### :fire: I'm currently persuing my academic interest in Software Engineering<br/>
  #### :mortar_board: Bachelor of Science - Computer Software Engineering, University of California, Irvine(UCI)
  <br/>
  
  ## 🧱 Tech Stack
  <!--Python-->
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>
  <!--JavaScript-->
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>
  <!--HTML5-->
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/>
  <!--CSS-->
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/>
  <br/>

  ## Github Stats
  ![EVAN-SOOBIN-JEON's GitHub stats](https://github-readme-stats.vercel.app/api?username=evanjeon-hub&theme=radical)
  <br/>

  ## Most Used Language
  ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=evanjeon-hub&size_weight=0.5&count_weight=0.5)

 </div>

<!--
**EvanJeon-hub/EvanJeon-hub** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
