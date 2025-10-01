<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dr. Enrico Talotti - Researcher</title>
<link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;700&display=swap" rel="stylesheet">
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>
<style>
  body {
    margin: 0;
    font-family: 'Fira Code', monospace;
    background-color: #000000; /* black terminal */
    color: #33aa33; /* soft green text */
  }

  a { color: #33aa33; text-decoration: none; }
  a:hover { text-decoration: underline; }

  .container {
    display: flex;
    min-height: 100vh;
  }

  /* Sidebar */
  .sidebar {
    width: 220px;
    background-color: #001100;
    padding: 2rem 1rem;
    border-right: 1px solid #002200;
  }

  .sidebar h2 {
    color: #66cc66;
    font-size: 1.2rem;
    margin-bottom: 1rem;
  }

  .sidebar ul { list-style: none; padding-left: 0; }
  .sidebar li { margin: 1rem 0; }

  /* Main Content */
  .main {
    flex: 1;
    padding: 2rem;
  }

  .section-title {
    color: #66cc66;
    font-size: 1.4rem;
    border-bottom: 1px solid #002200;
    margin-bottom: 1rem;
    padding-bottom: 0.3rem;
  }

  .code-box {
    background-color: #001100;
    border: 1px solid #002200;
    padding: 1rem;
    border-radius: 6px;
    margin-bottom: 2rem;
  }

  .code-line { margin: 0.2rem 0; }

  /* Syntax highlighting */
  .keyword { color: #33aa33; font-weight: bold; }
  .string { color: #55cc55; }
  .comment { color: #225522; font-style: italic; }
  .function { color: #66cc66; }
  .function.link {
    color: #99ff99;       /* brighter green */
    font-weight: bold;
    text-decoration: underline;
    text-decoration-color: #55cc55;
  }

.function.link:hover {
  color: #ccffcc;       /* even lighter on hover */
  text-shadow: 0 0 6px #55ff55; /* subtle glow */
}

  /* Math styling */
  .math {
    background-color: #001100;
    border: 1px solid #002200;
    padding: 1rem;
    border-radius: 6px;
    margin-bottom: 2rem;
    font-size: 1.1rem;
    color: #99ff99;
  }

  footer { text-align: center; color: #225522; font-size: 0.9rem; margin-top: 3rem; }
</style>
</head>
<body>

<div class="container">
  <div class="sidebar">
    <h2>Navigation</h2>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#publications">Publications</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </div>

  <div class="main">
    <!-- About Me -->
    <section id="about">
      <div class="section-title">About Me</div>
      <div class="code-box">
        <div class="code-line"><span class="comment">// Mathematician | Rust Developer</span></div>
        <div class="code-line"><span class="keyword">let</span> name = <span class="string">"Dr. Enrico Talotti"</span>;</div>
        <div class="code-line"><span class="keyword">let</span> focus = <span class="string">"Math Research & Coding"</span>;</div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects">
      <div class="section-title">Projects</div>
      <div class="code-box">
      <div class="code-line">
        <a href="https://github.com/enh11/hypercompositional_structures" target="_blank" class="function link">hyperstructures()</a>  
        <span class="comment">// Rust library for hypercompositional algebra</span>
      </div>

        <!--<div class="code-line"><span class="function">dataVizToolkit()</span>   // Interactive math visualizations</div> -->
        <!--<div class="code-line"><span class="function">mlResearchRepo()</span>   // ML & statistical models</div> -->
      </div>
    </section>

    <!-- Publications with Math -->
    <section id="publications">
      <div class="section-title">Publications</div>
      <div class="code-box">
        <div class="code-line"><span class="comment">// "Understanding Transformer Architectures" - Journal of AI Research, 2023</span></div>
        <div class="code-line"><span class="comment">// "Human-AI Collaboration in Coding Tasks" - ACM CHI, 2022</span></div>
      </div>
      <div class="math">
        $$E = mc^2$$  
        $$\nabla \cdot \mathbf{F} = \rho$$  
        $$\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}$$
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <div class="section-title">Contact</div>
      <div class="code-box">
        <div class="code-line"><span class="keyword">Email:</span> <a href="mailto:etalotti@ung.si" class ="function link">etalotti@ung.si</a></div>
        <div class="code-line"><span class="keyword">GitHub:</span> <a href="https://github.com/enh11" class="function link">github.com/enh11</a></div>
        <div class="code-line"><span class="keyword">LinkedIn:</span> <a href="https://linkedin.com/in/enrico-talotti-aa2527183" class="function link">linkedin.com/in/jenrico-talotti</a></div>
      </div>
    </section>

    <footer>
      &copy; 2025 Dr. Enrico Talotti. All rights reserved.
    </footer>
  </div>
</div>

</body>
</html>
