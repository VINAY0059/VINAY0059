## Hi there 👋

<!--
**VINAY0059/VINAY0059** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tilted Pill Tags Cloud</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      min-height: 100vh;
      background-color: #f6f3e7;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 40px 20px;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    }

    .tags-container {
      max-width: 1080px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      gap: 14px 18px;
    }

    .tag {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: #ffffff;
      color: #1a1a1a;
      padding: 9px 18px;
      border-radius: 9999px;
      font-size: 14px;
      font-weight: 500;
      box-shadow: 0 4px 14px rgba(0, 0, 0, 0.05);
      white-space: nowrap;
      cursor: default;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .tag:hover {
      transform: scale(1.06) rotate(0deg) !important;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      z-index: 10;
    }

    /* Colored status dots */
    .dot {
      width: 7px;
      height: 7px;
      border-radius: 50%;
      display: inline-block;
      flex-shrink: 0;
    }

    .dot.blue   { background-color: #3b82f6; }
    .dot.yellow { background-color: #eab308; }
    .dot.green  { background-color: #22c55e; }
    .dot.coral  { background-color: #f43f5e; }

    /* Slight alternating rotations to reproduce the organic scatter */
    .r-neg-4 { transform: rotate(-4deg); }
    .r-neg-3 { transform: rotate(-3deg); }
    .r-neg-2 { transform: rotate(-2deg); }
    .r-neg-1 { transform: rotate(-1deg); }
    .r-pos-1 { transform: rotate(1deg); }
    .r-pos-2 { transform: rotate(2.5deg); }
    .r-pos-3 { transform: rotate(3.5deg); }
    .r-pos-4 { transform: rotate(4.5deg); }
  </style>
</head>
<body>

  <div class="tags-container">
    <!-- Row 1 -->
    <div class="tag r-pos-1"><span class="dot blue"></span> AI & LLM</div>
    <div class="tag r-neg-2"><span class="dot yellow"></span> Agents & retrieval</div>
    <div class="tag r-pos-2"><span class="dot green"></span> Languages</div>
    <div class="tag r-neg-1"><span class="dot coral"></span> Backend & cloud</div>
    <div class="tag r-pos-3"><span class="dot yellow"></span> Frontend</div>
    <div class="tag r-neg-2"><span class="dot blue"></span> Mobile & ops</div>
    <div class="tag r-pos-1"><span class="dot coral"></span> Design</div>

    <!-- Row 2 -->
    <div class="tag r-neg-4"><span class="dot blue"></span> ✳ Claude</div>
    <div class="tag r-pos-2"><span class="dot blue"></span> GPT</div>
    <div class="tag r-neg-1"><span class="dot blue"></span> Llama</div>
    <div class="tag r-pos-3"><span class="dot blue"></span> RAG pipelines</div>
    <div class="tag r-neg-3"><span class="dot blue"></span> Tool calling</div>
    <div class="tag r-pos-2"><span class="dot blue"></span> Prompt engineering</div>
    <div class="tag r-neg-2"><span class="dot blue"></span> Workflow automation</div>

    <!-- Row 3 -->
    <div class="tag r-pos-3"><span class="dot yellow"></span> 🪢 Model Context Protocol</div>
    <div class="tag r-neg-3"><span class="dot yellow"></span> 🦜 LangChain</div>
    <div class="tag r-pos-2"><span class="dot yellow"></span> LangGraph</div>
    <div class="tag r-neg-4"><span class="dot yellow"></span> ❖ Langflow</div>
    <div class="tag r-pos-1"><span class="dot yellow"></span> Ollama</div>
    <div class="tag r-neg-2"><span class="dot yellow"></span> Qdrant</div>
    <div class="tag r-pos-3"><span class="dot yellow"></span> Sub-agents</div>

    <!-- Row 4 -->
    <div class="tag r-neg-2"><span class="dot yellow"></span> Connectors</div>
    <div class="tag r-pos-1"><span class="dot yellow"></span> Claude Code</div>
    <div class="tag r-neg-3"><span class="dot yellow"></span> Claude Fable</div>
    <div class="tag r-pos-2"><span class="dot yellow"></span> Claude Cowork</div>
    <div class="tag r-neg-1"><span class="dot yellow"></span> Codex</div>
    <div class="tag r-pos-3"><span class="dot yellow"></span> Antigravity</div>
    <div class="tag r-neg-3"><span class="dot green"></span> 🐍 Python</div>

    <!-- Row 5 -->
    <div class="tag r-pos-2"><span class="dot green"></span> JavaScript</div>
    <div class="tag r-neg-2"><span class="dot green"></span> TypeScript</div>
    <div class="tag r-pos-3"><span class="dot coral"></span> FastAPI</div>
    <div class="tag r-neg-1"><span class="dot coral"></span> Node.js</div>
    <div class="tag r-pos-2"><span class="dot coral"></span> REST APIs</div>
    <div class="tag r-neg-3"><span class="dot coral"></span> WebSockets</div>
    <div class="tag r-pos-1"><span class="dot coral"></span> Firebase</div>

    <!-- Row 6 -->
    <div class="tag r-neg-2"><span class="dot coral"></span> Google Cloud</div>
    <div class="tag r-pos-3"><span class="dot coral"></span> ▲ Vercel</div>
    <div class="tag r-neg-1"><span class="dot yellow"></span> ⚛ React</div>
    <div class="tag r-pos-2"><span class="dot yellow"></span> Next.js</div>
    <div class="tag r-neg-3"><span class="dot yellow"></span> ⚡ Vite</div>
    <div class="tag r-pos-1"><span class="dot yellow"></span> Tailwind CSS</div>
    <div class="tag r-neg-2"><span class="dot yellow"></span> GSAP</div>
    <div class="tag r-pos-2"><span class="dot yellow"></span> Framer</div>

    <!-- Row 7 -->
    <div class="tag r-pos-1"><span class="dot yellow"></span> Three.js</div>
    <div class="tag r-neg-3"><span class="dot blue"></span> Flutter</div>
    <div class="tag r-pos-2"><span class="dot blue"></span> Git</div>
    <div class="tag r-neg-2"><span class="dot blue"></span> GitHub Actions</div>
    <div class="tag r-pos-3"><span class="dot blue"></span> Domains & DNS</div>
    <div class="tag r-neg-1"><span class="dot blue"></span> Search Console</div>
    <div class="tag r-pos-2"><span class="dot coral"></span> Canva</div>

    <!-- Row 8 -->
    <div class="tag r-neg-2"><span class="dot coral"></span> Brand systems</div>
    <div class="tag r-pos-1"><span class="dot coral"></span> Print collateral</div>
    <div class="tag r-neg-3"><span class="dot coral"></span> Logo vectorisation</div>
  </div>

</body>
</html>
