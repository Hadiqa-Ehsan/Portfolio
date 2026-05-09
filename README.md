<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hadiqa Ehsan | Advanced Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
 font-family:'Poppins',sans-serif;
 background:linear-gradient(135deg,#020617,#0f172a,#020617);
 color:#e2e8f0;
}

nav{
 position:fixed;width:100%;top:0;
 display:flex;justify-content:space-between;
 padding:20px 60px;
 background:rgba(2,6,23,0.7);
 backdrop-filter:blur(12px);
 z-index:1000
}
nav h1{color:#38bdf8}
nav a{color:#e2e8f0;margin-left:20px;text-decoration:none}

.hero{height:100vh;display:flex;align-items:center;justify-content:center}

.profile-card{
 background:#0f172a;padding:40px;border-radius:20px;text-align:center;
 box-shadow:0 0 50px rgba(56,189,248,0.3);
}

.profile-card img{
 width:180px;height:180px;border-radius:50%;border:5px solid #38bdf8;
}

.profile-card h2{margin-top:15px;font-size:28px}
.profile-card p{color:#94a3b8;margin:10px 0}

.badges span{
 display:inline-block;background:#1e293b;padding:8px 14px;margin:5px;border-radius:20px;font-size:13px
}

section{padding:100px 60px;max-width:1300px;margin:auto}

.box{
 background:#0f172a;
 padding:40px;
 border-radius:20px;
 box-shadow:0 0 30px rgba(0,0,0,0.4);
 margin-bottom:40px;
}

h3{color:#38bdf8;margin-bottom:20px;font-size:26px}

.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:25px}

.card{
 background:#1e293b;padding:25px;border-radius:15px;transition:.4s;
}
.card:hover{transform:translateY(-10px) scale(1.03);box-shadow:0 20px 50px rgba(0,0,0,0.6)}

.card h4{margin-bottom:10px}
.card p{color:#94a3b8;font-size:14px}

.btn{
 display:inline-block;margin-top:12px;padding:8px 18px;
 background:#38bdf8;color:#020617;border-radius:20px;text-decoration:none
}

.skills-bars .bar{margin:20px 0}
.skills-bars span{display:block;margin-bottom:6px}
.progress{height:10px;background:#1e293b;border-radius:10px;overflow:hidden}
.progress div{height:100%;background:#38bdf8}

.timeline{border-left:3px solid #38bdf8;padding-left:20px}
.timeline div{margin-bottom:20px}

.contact-links a{
 display:block;margin:10px 0;color:#38bdf8;text-decoration:none
}

.stats{text-align:center}
.stats img{margin:10px}

footer{text-align:center;padding:20px;color:#94a3b8}
</style>
</head>

<body>

<nav>
<h1>Hadiqa</h1>
<div>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</div>
</nav>

<div class="hero">
<div class="profile-card">
<img src="/mnt/data/image.png">
<h2>Hadiqa Ehsan</h2>
<p>AI Engineer | Full-Stack Developer</p>
<div class="badges">
<span>AI</span><span>MERN</span><span>ML</span><span>Data Science</span>
</div>
<p>Building real-world intelligent applications 🚀</p>
</div>
</div>

<section id="about">
<div class="box">
<h3>About Me</h3>
<p>I am a BSCS student passionate about Artificial Intelligence, Full Stack Development, and building impactful real-world applications.</p>
<p>I have worked on multiple AI systems, MERN projects, and data analysis tools. My focus is on creating scalable, intelligent and user-friendly solutions.</p>
</div>
</section>

<section id="skills">
<div class="box">
<h3>Skills</h3>
<div class="skills-bars">
<div class="bar"><span>JavaScript</span><div class="progress"><div style="width:85%"></div></div></div>
<div class="bar"><span>Python</span><div class="progress"><div style="width:90%"></div></div></div>
<div class="bar"><span>React</span><div class="progress"><div style="width:80%"></div></div></div>
<div class="bar"><span>Node.js</span><div class="progress"><div style="width:75%"></div></div></div>
<div class="bar"><span>Machine Learning</span><div class="progress"><div style="width:85%"></div></div></div>
<div class="bar"><span>MongoDB</span><div class="progress"><div style="width:80%"></div></div></div>
</div>
</div>
</section>

<section>
<div class="box">
<h3>Journey</h3>
<div class="timeline">
<div><b>2026</b> - Building advanced AI & MERN applications</div>
<div><b>2025</b> - Developed full stack projects</div>
<div><b>2024</b> - Started programming & fundamentals</div>
</div>
</div>
</section>

<section id="projects">
<div class="box">
<h3>Projects</h3>
<div class="grid">
<div class="card"><h4>AI Plant Disease Detector</h4><p>Deep learning app detecting plant diseases.</p><a href="https://github.com/Hadiqa-Ehsan/AI_Plant_Disease_Detector" class="btn">GitHub</a></div>
<div class="card"><h4>PropTrack MERN</h4><p>Real estate platform with dashboards.</p><a href="https://github.com/Hadiqa-Ehsan/PropTrack-MERN" class="btn">GitHub</a></div>
<div class="card"><h4>Virtual Pet System</h4><p>C# based simulation project.</p><a href="https://github.com/Hadiqa-Ehsan/VirtualPetSystem" class="btn">GitHub</a></div>
<div class="card"><h4>Budget Tracker</h4><p>Finance tracking system.</p><a href="https://github.com/Hadiqa-Ehsan/Budget_Tracker" class="btn">GitHub</a></div>
<div class="card"><h4>Python Projects</h4><p>Collection of mini apps and games.</p><a href="https://github.com/Hadiqa-Ehsan/python-projects" class="btn">GitHub</a></div>
<div class="card"><h4>Data Analysis</h4><p>Performance analysis projects.</p><a href="https://github.com/Hadiqa-Ehsan/Sales_Data_Analyzer" class="btn">GitHub</a></div>
</div>
</div>
</section>

<section class="stats">
<div class="box">
<h3>GitHub Stats</h3>
<img src="https://github-readme-stats.vercel.app/api?username=Hadiqa-Ehsan&show_icons=true&theme=tokyonight">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Hadiqa-Ehsan&theme=tokyonight">
<br>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hadiqa-Ehsan&layout=compact&theme=tokyonight">
</div>
</section>

<section id="contact">
<div class="box">
<h3>Contact</h3>
<div class="contact-links">
<a href="mailto:hadiqaehsan4@gmail.com">📧 Email</a>
<a href="https://github.com/Hadiqa-Ehsan">💻 GitHub</a>
<a href="https://www.linkedin.com/">🔗 LinkedIn</a>
</div>
</div>
</section>

<footer>
<p>© 2026 Hadiqa Ehsan</p>
</footer>

</body>
</html>
