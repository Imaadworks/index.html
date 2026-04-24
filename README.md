<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Imaad Danish | Tech Portfolio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family: 'Courier New', monospace;
scroll-behavior:smooth;
}

body{
background:#020617;
color:#e2e8f0;
overflow-x:hidden;
}

/* GRID BACKGROUND */

body::before{
content:"";
position:fixed;
width:100%;
height:100%;
background:
linear-gradient(rgba(0,255,255,0.05) 1px, transparent 1px),
linear-gradient(90deg, rgba(0,255,255,0.05) 1px, transparent 1px);
background-size:40px 40px;
z-index:-1;
}

/* NAV */

nav{
position:fixed;
width:100%;
top:0;
background:#020617cc;
backdrop-filter:blur(8px);
padding:15px;
text-align:center;
border-bottom:1px solid #0ff;
}

nav a{
margin:0 20px;
color:#0ff;
text-decoration:none;
font-weight:bold;
letter-spacing:1px;
transition:0.3s;
}

nav a:hover{
color:#f0f;
text-shadow:0 0 10px #f0f;
}

/* HERO */

header{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

header h1{
font-size:70px;
color:#0ff;
text-shadow:0 0 20px #0ff, 0 0 40px #0ff;
}

.typing{
margin-top:15px;
font-size:20px;
border-right:2px solid #0ff;
white-space:nowrap;
overflow:hidden;
width:0;
animation:typing 4s steps(40,end) forwards, blink 0.7s infinite;
}

@keyframes typing{
to{width:350px;}
}

@keyframes blink{
50%{border-color:transparent;}
}

/* SECTIONS */

section{
padding:100px 10%;
}

h2{
font-size:34px;
color:#0ff;
text-shadow:0 0 10px #0ff;
margin-bottom:20px;
}

/* CARDS */

.card{
background:#020617;
border:1px solid #0ff;
padding:20px;
border-radius:10px;
box-shadow:0 0 15px rgba(0,255,255,0.2);
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 25px #0ff;
}

/* SKILLS */

.skills span{
display:inline-block;
margin:6px;
padding:8px 14px;
border:1px solid #0ff;
border-radius:20px;
color:#0ff;
}

/* PROJECT GRID */

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:20px;
}

/* CONTACT */

.contact-buttons button{
background:transparent;
border:1px solid #0ff;
color:#0ff;
padding:10px 20px;
margin:10px;
cursor:pointer;
transition:0.3s;
border-radius:5px;
}

.contact-buttons button:hover{
background:#0ff;
color:#020617;
box-shadow:0 0 20px #0ff;
}

/* FOOTER */

footer{
text-align:center;
padding:25px;
border-top:1px solid #0ff;
color:#0ff;
}

/* GLOW LINE */

.line{
width:100%;
height:2px;
background:linear-gradient(90deg,transparent,#0ff,transparent);
margin:40px 0;
}

</style>
</head>

<body>

<nav>
<a href="#about">ABOUT</a>
<a href="#skills">SKILLS</a>
<a href="#projects">PROJECTS</a>
<a href="#contact">CONTACT</a>
</nav>

<header>
<h1>Imaad Danish</h1>
<div class="typing">> Student | Robotics | Tech_</div>
</header>

<section id="about">
<h2>ABOUT</h2>
<div class="card">
<p>
Passionate about building futuristic technology, AI systems, and automation tools.
I love exploring robotics and developing smart solutions for real-world problems.
</p>
</div>
<div class="line"></div>
</section>

<section id="skills">
<h2>SKILLS</h2>
<div class="skills">
<span>Python</span>
<span>Flutter</span>
<span>Web Dev</span>
<span>AI/ML</span>
<span>Robotics</span>
</div>
<div class="line"></div>
</section>

<section id="projects">
<h2>PROJECTS</h2>

<div class="projects">

<div class="card">
<h3>AI Chatbot</h3>
<p>Intelligent chatbot with ML logic.</p>
</div>

<div class="card">
<h3>Security Camera</h3>
<p>Live mobile surveillance system.</p>
</div>

<div class="card">
<h3>Automation Scripts</h3>
<p>Task automation tools for efficiency.</p>
</div>

</div>

<div class="line"></div>

</section>

      
      <h2>Technologia // 67</h2>
      <p>
      </p>
      <div class="easter-embed-grid">
        <div class="easter-embed">
          <iframe
            width="110"
            height="200"
            src="https://www.myinstants.com/instant/67-sound-90775/embed/"
            frameborder="0"
            scrolling="no"
            title="67 soundboard"
          ></iframe>
        </div>
        <div class="easter-embed">
        <iframe
          width="110"
          height="200"
          src="https://www.myinstants.com/instant/technologia-53863/embed/"
          frameborder="0"
          scrolling="no"
          title="Technologia soundboard"
        ></iframe>
        </div>
      </div>

    <script src="script.js"></script>

<section id="contact">
<h2>CONTACT</h2>

<div class="contact-buttons">

<a href="mailto:khaleekahmand@gmail.com">
<button>EMAIL</button>
</a>

<a href="https://github.com/imaadworks" target="_blank">
<button>GITHUB</button>
</a>

<a href="https://wa.me/9199975 54431" target="_blank">
<button>WHATSAPP</button>
</a>

<a href="https://youtube.com/@cryonixvfxofficial?si=yLVwCCqpt4wL_EFy" target="_blank">
<button>YouTube</button>

<footer>
<p>© 2026 Imaad Danish | Build for the future of robotics</p>
</footer>
