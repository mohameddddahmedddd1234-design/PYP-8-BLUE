!-- PYP 8 Two-Page Class Website (ready-to-use)
Instructions to open in Google:
1) Open with Google Chrome: Save this file as "pyp8.html" and double-click it — it will open in any web browser including Google Chrome.
2) To show on Google Sites: Upload "pyp8.html" and image files to a public hosting service (GitHub Pages, Netlify, or Google Drive's public link workaround), then on Google Sites use Insert → Embed and paste the hosted URL. (If you want, I can help host it on GitHub Pages.)
-->

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8" />
  <title>PYP 8 Class</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    :root{--bg:#fdf7c3;--accent:#ffbf00;--card:#fff9d6}
    body { font-family: 'Comic Sans MS', 'Trebuchet MS', sans-serif; background: #fdf7c3; text-align: center; margin:0; padding:30px; }
    .wrap{max-width:1000px;margin:0 auto;background:linear-gradient(180deg,var(--card),#fff);border-radius:18px;padding:24px;box-shadow:0 6px 20px rgba(0,0,0,0.08);}
    .page{display:none}
    #page1{display:block}
    h1{font-size:36px;margin:6px 0}
    p.lead{font-size:18px;color:#333}
    img.classphoto{width:85%;max-width:540px;border:6px dashed var(--accent);border-radius:12px;margin:14px 0}
    button{padding:12px 20px;margin:10px;font-size:18px;border-radius:12px;border:2px solid #b07300;background:#fff3a8;cursor:pointer;transition:transform .18s ease}
    button:hover{transform:translateY(-4px)}
    .sessions{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-top:12px}
    .tag{background:#fff5cf;padding:8px 12px;border-radius:999px;border:1px solid #ffd66e;font-weight:600}
    .essay{text-align:left;background:linear-gradient(90deg, rgba(255,255,255,0.9), rgba(255,255,240,0.9));padding:18px;border-radius:12px;margin:18px 0;line-height:1.6}
    .stars{font-size:28px;margin:8px}
    .footer{font-size:14px;color:#666;margin-top:12px}
    @media(max-width:600px){h1{font-size:26px}img.classphoto{width:100%}}
  </style>
</head>
<body>
<div class="wrap">
  <!-- PAGE 1 -->
  <div id="page1" class="page">
    <div class="stars">⭐⭐⭐ PYP 8 blue ⭐⭐⭐</div>
    <h1>Welcome to PYP 8 blue!</h1>

    <!-- Replace classphoto.png with your saved photo file name -->
    <img class="classphoto" src="classphoto.png" alt="Class Photo" />

    <h2>Our Sessions</h2>
    <div class="sessions">
      <div class="tag">Arabic</div>
      <div class="tag">Math</div>
      <div class="tag">UOI</div>
      <div class="tag">English</div>
      <div class="tag">Art</div>
      <div class="tag">Music</div>
      <div class="tag">ICT</div>
      <div class="tag">PE</div>
      <div class="tag">Drama</div>
      <div class="tag">Social</div>
      <div class="tag">Reading</div>
       <div class="tag">Religon</div>
    </div>

    <br />
    <button onclick="showPage('page2')">Go to Page 2 ➜</button>
  </div>

  <!-- PAGE 2 -->
  <div id="page2" class="page">
    <div class="stars">🌟🌟🌟 Our Story 🌟🌟🌟</div>
    <h1>About Our Class</h1>

    <div class="essay">
      <h3>Who we are</h3>
      <p>
        We are PYP 8 — a friendly, curious, and creative group of learners. Every morning we come ready to explore new ideas, ask questions, and help one another grow. Our classroom is a place where mistakes are welcome because they show us how to get better.
      </p>

      <h3>What we do</h3>
      <p>
        Our days are full of variety: Arabic stories that spark our imagination, math puzzles that make our brains work fast, and Units of Inquiry (UOI) projects where we become little researchers. In English we read and write, in Art we paint and imagine, and in Music we move with rhythm. ICT helps us use technology safely, PE keeps us active, Drama lets us express ourselves, and Social studies teach us about the world. Reading time is our cozy moment to travel with books.
      </p>

      <h3>How we learn together</h3>
      <p>
        We learn best when we listen, try, and support each other. Teamwork and kindness are part of our class rules. We celebrate small wins — a correct answer, a finished drawing, a new helpful friend — and we solve problems together with respect.
      </p>

      <h3>From my mind (a little extra)</h3>
      <p>
        Imagine a class where every desk has a tiny star sticker — a reminder that everyone shines in their own way. Some of us are problem solvers, some are artists, some are storytellers, and together we make a bright constellation. If we keep being curious, brave, and kind, there’s nothing we can't do.
      </p>

      <h3>Short promise</h3>
      <p>
        We promise to listen, to try our best, and to help others. This is our little community — PYP 8 — and we are proud of it.
      </p>
    </div>

    <button onclick="showPage('page1')">⬅ Back to Page 1</button>

    <div class="footer">Tip: To show this page on Google Sites, host this file and use Insert → Embed with the page URL.</div>
  </div>
</div>

<script>
  function showPage(id){
    document.querySelectorAll('.page').forEach(p=>p.style.display='none');
    document.getElementById(id).style.display='block';
    window.scrollTo(0,0);
  }
</script>
</body>
</html>

