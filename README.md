<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>JavaScript Learning Repo</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --muted:#9aa4b2;
      --accent:#7dd3fc;
      --glass: rgba(255,255,255,0.03);
    }
    body{
      margin:0;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(180deg,#071027 0%, #071822 100%);
      color:#e6eef6;
      line-height:1.5;
      padding:32px;
    }
    .container{
      max-width:900px;
      margin:0 auto;
    }
    header{
      background: linear-gradient(90deg, rgba(125,211,252,0.06), rgba(255,255,255,0.02));
      border-radius:12px;
      padding:20px;
      box-shadow: 0 6px 18px rgba(2,6,23,0.6);
      display:flex;
      gap:16px;
      align-items:center;
    }
    .logo{
      width:72px;
      height:72px;
      border-radius:10px;
      background: linear-gradient(135deg,#06273b,#154b62);
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight:700;
      color:var(--accent);
      font-size:20px;
      box-shadow: inset 0 -6px 18px rgba(255,255,255,0.02);
    }
    h1{ margin:0; font-size:1.6rem; }
    p.lead{ margin:6px 0 0; color:var(--muted); }

    .card{
      margin-top:20px;
      background:var(--card);
      border-radius:12px;
      padding:18px;
      box-shadow: 0 6px 14px rgba(2,6,23,0.55);
      border:1px solid rgba(255,255,255,0.02);
    }

    h2{ margin-top:0; color:#dff6ff; }
    ul { padding-left:20px; margin-top:6px; color:var(--muted); }
    code {
      background:var(--glass);
      padding:2px 6px;
      border-radius:6px;
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, "Roboto Mono", monospace;
      color:#bfe9ff;
    }

    .meta{
      display:flex;
      gap:12px;
      flex-wrap:wrap;
      margin-top:10px;
      color:var(--muted);
      font-size:0.95rem;
    }

    .btn {
      display:inline-block;
      text-decoration:none;
      padding:8px 12px;
      border-radius:8px;
      background:linear-gradient(90deg,#0ea5a5,#06b6d4);
      color:#042329;
      font-weight:600;
      box-shadow: 0 6px 18px rgba(6,30,32,0.45);
    }

    footer { margin-top:22px; color:var(--muted); font-size:0.9rem; text-align:center; }
    @media (max-width:600px){
      header{ flex-direction:column; align-items:flex-start; gap:10px; }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">JS</div>
      <div>
        <h1>JavaScript Learning Repo</h1>
        <p class="lead">A repository for exploring and documenting JavaScript concepts. From fundamentals to advanced ideas, explained in a clear and practical way.</p>
        <div class="meta">
          <div>⭐ Personal learning notes</div>
          <div>•</div>
          <div>🔁 Regularly updated</div>
          <div>•</div>
          <div><a href="#contributing" class="btn">Contribute</a></div>
        </div>
      </div>
    </header>

    <section class="card" id="about">
      <h2>About</h2>
      <p style="color:var(--muted)">
        This repository is my personal space to explore JavaScript. It contains explanations, examples, project code, and notes that help me understand and remember concepts. The content is flexible — it may contain short notes, full projects, explanations, or other resources as I progress.
      </p>
    </section>

    <section class="card" id="structure">
      <h2>Repository structure (example)</h2>
      <ul>
        <li><code>/notes/</code> — conceptual notes and explanations</li>
        <li><code>/projects/</code> — small projects and demos</li>
        <li><code>/exercises/</code> — practice exercises and solutions</li>
        <li><code>/resources/</code> — links, references, and useful articles</li>
      </ul>
      <p style="color:var(--muted)">You don't need to follow this structure exactly — it's just a suggested starting point.</p>
    </section>

    <section class="card" id="how-to-use">
      <h2>How to use</h2>
      <ul>
        <li>Browse the folders to find notes, example projects, or exercises.</li>
        <li>Read files in the order that makes sense for you — each file includes a short explanation.</li>
        <li>Run project examples locally (see each project's README or code comments for instructions).</li>
      </ul>
    </section>

    <section class="card" id="contributing">
      <h2>Contributing</h2>
      <p style="color:var(--muted)">Contributions are welcome! If you want to add a note, fix a typo, or share an example, feel free to open a pull request. Keep changes small and include clear explanations for any new content.</p>
      <ul>
        <li>Fork the repo and create a branch for your change.</li>
        <li>Open a PR with a clear title and description.</li>
        <li>Please be respectful — this is a personal learning project.</li>
      </ul>
    </section>

    <section class="card" id="license">
      <h2>License</h2>
      <p style="color:var(--muted)">Unless specified otherwise, content in this repo is available under the <strong>MIT License</strong>. Update the license file if you prefer a different one.</p>
    </section>

    <section class="card" id="contact">
      <h2>Contact</h2>
      <p style="color:var(--muted)">Created by <strong>Your Name</strong>. You can reach me via GitHub profile or open an issue in this repository for questions or suggestions.</p>
    </section>

    <footer>
      <div>Made for learning — feel free to explore and build. 🚀</div>
    </footer>
  </div>
</body>
</html>
