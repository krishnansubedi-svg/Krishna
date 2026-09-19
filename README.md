<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Krishna Subedi</title>
<meta name="description" content="Krishna Subedi's personal website">
<link rel="preconnect" href="https://fonts.googleapis.com">
 <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
 <link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,800&family=Newsreader:opsz,wght@6..72,400;6..72,500&display=swap" rel="stylesheet">
 <style>
 :root {
 --bg: #eef2f7;
 --ink: #14213d;
 --muted: #4a5670;
 --accent: #f2a900;
 --teal: #1b7f79;
 --line: #c9d3e2;
 }
 * { box-sizing: border-box; }
 html { scroll-behavior: smooth; }
 body {
 margin: 0;
 background: var(--bg);
 color: var(--ink);
 font-family: "Newsreader", Georgia, serif;
 font-size: 1.15rem;
 line-height: 1.65;
 }
 a { color: var(--teal); text-underline-offset: 3px; }
 a:focus-visible, button:focus-visible { outline: 3px solid var(--accent); outline-offset: 3px; }
 .wrap { max-width: 44rem; margin: 0 auto; padding: 0 1.4rem; }

 nav { padding: 1.4rem 0; }
 nav .wrap { display: flex; gap: 1.4rem; flex-wrap: wrap; }
 nav a {
 font-family: "Bricolage Grotesque", system-ui, sans-serif;
 font-weight: 500;
 color: var(--ink);
 text-decoration: none;
 font-size: 1rem;
 }
 nav a:hover { color: var(--teal); }

 header { padding: 3.5rem 0 3rem; }
 h1 {
 font-family: "Bricolage Grotesque", system-ui, sans-serif;
 font-weight: 800;
 font-size: clamp(3.2rem, 14vw, 6.5rem);
 line-height: 0.95;
 letter-spacing: -0.03em;
 margin: 0 0 1.4rem;
 background: linear-gradient(transparent 68%, var(--accent) 68%, var(--accent) 92%, transparent 92%);
 display: inline;
 }
 .intro { font-size: 1.4rem; max-width: 34rem; margin: 1.6rem 0 0; color: var(--muted); }

 section { padding: 2.6rem 0; border-top: 1px solid var(--line); }
 h2 {
 font-family: "Bricolage Grotesque", system-ui, sans-serif;
 font-weight: 800;
 font-size: 1.7rem;
 margin: 0 0 1rem;
 letter-spacing: -0.01em;
 }
 p { margin: 0 0 1rem; max-width: 38rem; }

 .work { list-style: none; padding: 0; margin: 0; }
 .work li { padding: 1.1rem 0; border-bottom: 1px solid var(--line); }
 .work li:last-child { border-bottom: 0; }
 .work a.title {
 font-family: "Bricolage Grotesque", system-ui, sans-serif;
 font-weight: 800;
 font-size: 1.35rem;
 color: var(--ink);
 text-decoration: none;
 }
 .work a.title:hover { color: var(--teal); text-decoration: underline; }
 .work span { display: block; color: var(--muted); }

 .contact a.btn {
 display: inline-block;
 font-family: "Bricolage Grotesque", system-ui, sans-serif;
 font-weight: 800;
 background: var(--ink);
 color: #fff;
 padding: 0.75rem 1.4rem;
 border-radius: 6px;
 text-decoration: none;
 margin: 0.4rem 0.6rem 0.4rem 0;
 }
 .contact a.btn:hover { background: var(--teal); }

 footer { padding: 2.5rem 0 3rem; color: var(--muted); font-size: 0.95rem; }

 @media (prefers-color-scheme: dark) {
 :root { --bg: #0f1a2e; --ink: #eef2f7; --muted: #a7b3c9; --line: #26355a; --teal: #4fd1c5; }
 .contact a.btn { background: var(--accent); color: #14213d; }
 .contact a.btn:hover { background: #fff; }
 }
 </style>
</head>
<body>
 <nav>
 <div class="wrap">
 <a href="#about">About</a>
 <a href="#work">Work</a>
 <a href="#contact">Contact</a>
 </div>
 </nav>

 <header>
 <div class="wrap">
 <h1>Krishna Subedi</h1>
 <p class="intro">I build websites and small online shops. This is where my work lives.</p>
 </div>
 </header>

 <main>
 <section id="about">
 <div class="wrap">
 <h2>About</h2>
 <!-- Edit the text below to tell your own story -->
 <p>Hi, I'm Krishna. I'm learning web development and making my own projects with HTML. I enjoy turning an idea into a page that anyone can open and use.</p>
 <p>Right now I'm working on an online shop and improving my personal site.</p>
 </div>
 </section>

 <section id="work">
 <div class="wrap">
 <h2>Work</h2>
 <ul class="work">
 <li>
 <a class="title" href="https://krishnansubedi-svg.github.io/krishlshop/">krishlshop</a>
 <span>An online shop built with HTML.</span>
 </li>
 <!-- Copy the <li> block above to add another project -->
 </ul>
 </div>
 </section>

 <section id="contact" class="contact">
 <div class="wrap">
 <h2>Contact</h2>
 <p>Want to work together or just say hello? Reach me here.</p>
 <a class="btn" href="mailto:your-email@example.com">Send an email</a>
 <a class="btn" href="https://github.com/krishnansubedi-svg">See my GitHub</a>
 </div>
 </section>
 </main>

 <footer>
 <div class="wrap">© 2026 Krishna Subedi</div>
 </footer>
</body>
</html>
