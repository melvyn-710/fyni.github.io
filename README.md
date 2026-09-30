# fyni.github.io
---
layout: null
title: Fyni | Portfolio
---
<!DOCTYPE html>
<html lang="en" data-theme="dark">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Fyni | Portfolio</title>
<meta name="description" content="Hi, I'm Fyni. Welcome to my personal website and portfolio.">
<style>
:root{--bg:#0b0b14;--bg2:#13132a;--text:#f2f2ff;--muted:#9a9ac0;--a1:#7c3aed;--a2:#06b6d4;--border:#24244a}
[data-theme="light"]{--bg:#fafaff;--bg2:#eeeefb;--text:#15152b;--muted:#585880;--border:#d8d8f0}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;background:var(--bg);color:var(--text);line-height:1.65;transition:background .3s,color .3s}
a{color:inherit;text-decoration:none}
.wrap{max-width:1050px;margin:auto;padding:0 1.5rem}
header{position:sticky;top:0;z-index:20;background:color-mix(in srgb,var(--bg) 85%,transparent);backdrop-filter:blur(10px);border-bottom:1px solid var(--border)}
nav{display:flex;justify-content:space-between;align-items:center;height:64px}
.logo{font-size:1.4rem;font-weight:800;background:linear-gradient(90deg,var(--a1),var(--a2));-webkit-background-clip:text;background-clip:text;color:transparent}
.links{display:flex;gap:1.6rem;align-items:center}
.links a{font-weight:500;color:var(--muted)}
.links a:hover{color:var(--text)}
#theme{background:var(--bg2);border:1px solid var(--border);color:var(--text);border-radius:50%;width:36px;height:36px;cursor:pointer;font-size:1rem}
.hero{padding:7rem 0 5rem;text-align:center;background:radial-gradient(circle at 50% 0,rgba(124,58,237,.25),transparent 60%)}
.hi{color:var(--a2);font-weight:600;letter-spacing:.1em;text-transform:uppercase;font-size:.9rem}
.hero h1{font-size:clamp(2.6rem,8vw,5rem);line-height:1.1;margin:.6rem 0 1rem}
.grad{background:linear-gradient(90deg,var(--a1),var(--a2));-webkit-background-clip:text;background-clip:text;color:transparent}
.role{font-size:1.4rem;color:var(--muted);min-height:2.2rem}
.cursor{border-right:2px solid var(--a2);margin-left:2px;animation:blink 1s steps(1) infinite}
@keyframes blink{50%{border-color:transparent}}
.hero p.lead{max-width:600px;margin:1.2rem auto 2rem;color:var(--muted);font-size:1.1rem}
.btns{display:flex;gap:1rem;justify-content:center;flex-wrap:wrap}
.btn{padding:.85rem 2rem;border-radius:999px;font-weight:600;display:inline-block;transition:transform .2s}
.btn:hover{transform:translateY(-3px)}
.primary{background:linear-gradient(90deg,var(--a1),var(--a2));color:#fff}
.ghost{border:1px solid var(--border);background:var(--bg2)}
section{padding:5rem 0}
h2.title{font-size:2.2rem;text-align:center;margin-bottom:.5rem}
.sub{text-align:center;color:var(--muted);margin-bottom:3rem}
.about{display:grid;grid-template-columns:1fr 1fr;gap:3rem;align-items:center}
.avatar{aspect-ratio:1;max-width:320px;margin:auto;width:100%;border-radius:30% 70% 70% 30%/30% 30% 70% 70%;background:linear-gradient(135deg,var(--a1),var(--a2));display:flex;align-items:center;justify-content:center;font-size:6rem;font-weight:800;color:#fff;animation:morph 8s ease-in-out infinite}
@keyframes morph{50%{border-radius:70% 30% 30% 70%/70% 70% 30% 30%}}
.about p{color:var(--muted);margin-bottom:1rem}
.stats{display:flex;gap:2rem;margin-top:1.5rem}
.stats b{display:block;font-size:1.8rem}
.stats span{color:var(--muted);font-size:.9rem}
.chips{display:flex;flex-wrap:wrap;gap:.7rem;justify-content:center}
.chip{padding:.5rem 1.2rem;border-radius:999px;background:var(--bg2);border:1px solid var(--border);font-weight:500}
.chip:hover{border-color:var(--a2)}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(290px,1fr));gap:1.5rem}
.card{background:var(--bg2);border:1px solid var(--border);border-radius:16px;padding:1.8rem;transition:transform .25s,border-color .25s}
.card:hover{transform:translateY(-6px);border-color:var(--a1)}
.card .ico{font-size:2rem;margin-bottom:.8rem}
.card h3{margin-bottom:.4rem}
.card p{color:var(--muted);font-size:.97rem}
.card .tag{display:inline-block;margin-top:1rem;color:var(--a2);font-weight:600;font-size:.9rem}
.contact{text-align:center}
.contact p{color:var(--muted);max-width:520px;margin:0 auto 2rem}
.social{display:flex;gap:1rem;justify-content:center;margin-top:2rem;flex-wrap:wrap}
.social a{color:var(--muted);font-weight:500}
.social a:hover{color:var(--a2)}
footer{text-align:center;padding:2rem;color:var(--muted);border-top:1px solid var(--border);font-size:.9rem}
.reveal{opacity:0;transform:translateY(30px);transition:opacity .7s,transform .7s}
.reveal.show{opacity:1;transform:none}
@media (max-width:760px){.about{grid-template-columns:1fr}.links a.hide{display:none}.stats{justify-content:center}}
</style>
</head>
<body>
<header>
<div class="wrap">
<nav>
<a href="#top" class="logo">Fyni.</a>
<div class="links">
<a class="hide" href="#about">About</a>
<a class="hide" href="#skills">Skills</a>
<a class="hide" href="#projects">Projects</a>
<a href="#contact">Contact</a>
<button id="theme" aria-label="Toggle theme">☀</button>
</div>
</nav>
</div>
</header>
<div class="hero" id="top">
<div class="wrap">
<div class="hi">Hello, I'm</div>
<h1><span class="grad">Fyni</span></h1>
<div class="role"><span id="typed"></span><span class="cursor"></span></div>
<p class="lead">I build clean, useful things for the web and love turning ideas into real projects. Welcome to my corner of the internet.</p>
<div class="btns">
<a class="btn primary" href="#projects">See My Work</a>
<a class="btn ghost" href="#contact">Contact Me</a>
</div>
</div>
</div>
<section id="about">
<div class="wrap about reveal">
<div class="avatar">F</div>
<div>
<h2 class="title" style="text-align:left">About Me</h2>
<p>I'm Fyni, a curious creator who enjoys learning new things and sharing what I build. Replace this text with your own story: where you are from, what you do and what drives you.</p>
<p>When I'm not working on projects, you'll find me exploring new ideas, reading and improving my skills.</p>
<div class="stats">
<div><b>10+</b><span>Projects</span></div>
<div><b>3+</b><span>Years learning</span></div>
<div><b>100%</b><span>Passion</span></div>
</div>
</div>
</div>
</section>
<section id="skills" style="background:var(--bg2)">
<div class="wrap reveal">
<h2 class="title">My Skills</h2>
<p class="sub">Tools and technologies I enjoy working with</p>
<div class="chips">
<span class="chip">HTML</span><span class="chip">CSS</span><span class="chip">JavaScript</span><span class="chip">Git &amp; GitHub</span><span class="chip">Python</span><span class="chip">UI Design</span><span class="chip">Problem Solving</span><span class="chip">Teamwork</span>
</div>
</div>
</section>
<section id="projects">
<div class="wrap reveal">
<h2 class="title">Projects</h2>
<p class="sub">A few things I've made</p>
<div class="grid">
<div class="card"><div class="ico">🌐</div><h3>Personal Website</h3><p>This very site, built with HTML and CSS and hosted for free on GitHub Pages.</p><a class="tag" href="https://github.com/fyni">View on GitHub →</a></div>
<div class="card"><div class="ico">📱</div><h3>Project Two</h3><p>Describe your second project here. What problem does it solve and what did you use?</p><a class="tag" href="https://github.com/fyni">View on GitHub →</a></div>
<div class="card"><div class="ico">🚀</div><h3>Project Three</h3><p>Add another project, idea or achievement you're proud of to show visitors.</p><a class="tag" href="https://github.com/fyni">View on GitHub →</a></div>
</div>
</div>
</section>
<section id="contact" style="background:var(--bg2)">
<div class="wrap contact reveal">
<h2 class="title">Let's Connect</h2>
<p>Have a question, idea or opportunity? I'd love to hear from you. Send me a message and I'll reply as soon as I can.</p>
<a class="btn primary" href="mailto:your-email@example.com">Say Hello ✉</a>
<div class="social">
<a href="https://github.com/fyni">GitHub</a>
<a href="https://twitter.com/">Twitter / X</a>
<a href="https://linkedin.com/">LinkedIn</a>
<a href="https://instagram.com/">Instagram</a>
</div>
</div>
</section>
<footer>
<p>© <span id="year"></span> Fyni. Built with ❤ and hosted on GitHub Pages.</p>
</footer>
<script>
var words = ["Web Designer", "Developer", "Creative Thinker", "Lifelong Learner"];
var w = 0, c = 0, del = false, el = document.getElementById("typed");
function type() {
  var word = words[w];
  el.textContent = word.substring(0, c);
  if (!del && c < word.length) { c++; setTimeout(type, 100); }
  else if (!del) { del = true; setTimeout(type, 1400); }
  else if (c > 0) { c--; setTimeout(type, 50); }
  else { del = false; w = (w + 1) % words.length; setTimeout(type, 300); }
}
type();
document.getElementById("year").textContent = new Date().getFullYear();
var root = document.documentElement, btn = document.getElementById("theme");
btn.onclick = function () {
  var light = root.getAttribute("data-theme") === "dark";
  root.setAttribute("data-theme", light ? "light" : "dark");
  btn.textContent = light ? "☾" : "☀";
};
var io = new IntersectionObserver(function (entries) {
  entries.forEach(function (e) { if (e.isIntersecting) e.target.classList.add("show"); });
}, { threshold: 0.15 });
document.querySelectorAll(".reveal").forEach(function (n) { io.observe(n); });
</script>
</body>
</html>
