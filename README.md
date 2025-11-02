<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Terms & Agreement</title>
  <style>
    :root{
      --bg:#0f1724; /* deep navy */
      --card:#0b1220;
      --muted:#9aa4b2;
      --accent:#60a5fa;
      --accent-2:#7c3aed;
      --glass: rgba(255,255,255,0.04);
      --radius:14px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }

    html,body{height:100%;margin:0;background:linear-gradient(180deg,var(--bg),#071029);color:#e6eef8}
    .wrap{min-height:100vh;display:flex;align-items:center;justify-content:center;padding:40px}

    .card{
      width:100%;max-width:900px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:var(--radius);box-shadow:0 8px 30px rgba(2,6,23,0.6);overflow:hidden;border:1px solid rgba(255,255,255,0.03)
    }

    .card-header{
      display:flex;justify-content:space-between;align-items:center;padding:22px 28px;background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-bottom:1px solid rgba(255,255,255,0.02)
    }

    .brand{
      display:flex;gap:12px;align-items:center
    }
    .logo{
      width:44px;height:44px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;font-weight:700;color:white;box-shadow:0 6px 18px rgba(96,165,250,0.12)
    }

    h1{font-size:18px;margin:0}
    p.lead{margin:0;color:var(--muted);font-size:13px}

    .card-body{display:grid;grid-template-columns:1fr 320px;gap:18px;padding:20px}

    .terms{
      background:var(--glass);padding:18px;border-radius:12px;min-height:420px;max-height:520px;overflow:auto;border:1px solid rgba(255,255,255,0.02)
    }

    .terms h2{margin-top:0}
    .terms p{color:#d7e3f5;line-height:1.55}
    .terms ol{padding-left:18px}

    .side{
      display:flex;flex-direction:column;gap:12px
    }
    .side .summary{background:rgba(255,255,255,0.02);padding:14px;border-radius:10px}
    .meta{font-size:13px;color:var(--muted)}

    .controls{display:flex;gap:10px;align-items:center}
    .btn{
      display:inline-flex;align-items:center;justify-content:center;padding:10px 14px;border-radius:10px;border:none;background:linear-gradient(90deg,var(--accent),var(--accent-2));color:white;font-weight:600;cursor:pointer;box-shadow:0 6px 18px rgba(124,58,237,0.12)
    }
    .btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--accent)}
    .btn:disabled{opacity:0.5;cursor:not-allowed}

    .accept-row{display:flex;gap:10px;align-items:center;padding:14px;border-radius:10px;background:linear-gradient(180deg, rgba(0,0,0,0.12), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.02)}
    .accept-row label{font-size:14px}

    .small{font-size:13px;color:var(--muted)}

    /* responsive */
    @media (max-width:880px){
      .card-body{grid-template-columns:1fr;}
      .side{order:2}
      .terms{order:1}
    }

    /* Nice scrollbar */
    .terms::-webkit-scrollbar{width:10px}
    .terms::-webkit-scrollbar-thumb{background:linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.02));border-radius:10px}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card" role="region" aria-labelledby="termsTitle">
      <div class="card-header">
        <div class="brand">
          <div class="logo">T&amp;A</div>
          <div>
            <h1 id="termsTitle">Terms &amp; Agreement</h1>
            <p class="lead">Please read these terms carefully before using this service.</p>
          </div>
        </div>
        <div class="meta small">Last updated: <strong id="updatedDate">2025-11-02</strong></div>
      </div>

      <div class="card-body">
        <section class="terms" aria-label="Terms and conditions text">
          <h2>1. Acceptance of Terms</h2>
          <p>By accessing and using this service, you accept and agree to be bound by the terms and provision of this agreement. If you do not agree to abide by these terms, you are not authorized to use the service.</p>

          <h2>2. User Responsibilities</h2>
          <p>You agree to use the service only for lawful purposes and in a way that does not infringe the rights of others. You must keep your account credentials secure and notify us immediately of any unauthorized use.</p>

          <h2>3. Data &amp; Privacy</h2>
          <p>We collect and store data necessary for the operation of the service. Sensitive information must be provided with consent. Refer to our Privacy Policy for details on handling personal data.</p>

          <h2>4. Alerts &amp; Notifications</h2>
          <p>The system may send alerts (email or SMS) for critical events. By agreeing to these terms you consent to receive these messages; you may configure or opt out in your account settings where available.</p>

          <h2>5. Limitations of Liability</h2>
          <p>To the fullest extent permitted by law, the service and its operators shall not be liable for any indirect, incidental, special or consequential damages arising out of the use of the service.</p>

          <h2>6. Termination</h2>
          <p>We may suspend or terminate access to the service at any time for violations of these terms or for reasons of safety and security.</p>

          <h2>7. Changes to Terms</h2>
          <p>We reserve the right to modify or replace these Terms at any time. If a revision is material, we will make reasonable efforts to notify users.</p>

          <h2>8. Governing Law</h2>
          <p>These terms shall be governed by and construed in accordance with the laws of the applicable jurisdiction.</p>

          <h2>9. Contact</h2>
          <p>If you have questions about these terms, please contact support through the app or email.</p>

          <hr />
          <p class="small">By clicking "I Agree" you confirm that you have read, understood, and accepted these terms.</p>
        </section>

        <aside class="side" aria-label="Acceptance and actions">
          <div class="summary">
            <h3 style="margin:0 0 8px 0">Summary</h3>
            <p class="small">These terms cover user duties, alerting behavior, data usage, liability limits, and termination rules. Please read the full text before accepting.</p>
          </div>

          <div class="accept-row" role="form" aria-labelledby="consentLabel">
            <input id="consent" type="checkbox" aria-describedby="consentDesc" />
            <div>
              <label for="consent" id="consentLabel">I agree to the Terms &amp; Agreement</label>
              <div id="consentDesc" class="small">You must accept to continue using the service.</div>
            </div>
          </div>

          <div class="controls">
            <button id="agreeBtn" class="btn" disabled>✔ I Agree</button>
            <button id="printBtn" class="btn ghost">Print</button>
          </div>

          <div class="small" style="margin-top:6px">Review date: <strong id="reviewDate">30 days</strong> • Contact: <a href="mailto:support@example.com" style="color:var(--accent);text-decoration:none">support@example.com</a></div>
        </aside>
      </div>
    </div>
  </div>

  <script>
    const consent = document.getElementById('consent');
    const agreeBtn = document.getElementById('agreeBtn');
    const printBtn = document.getElementById('printBtn');

    consent.addEventListener('change', (e) => {
      agreeBtn.disabled = !e.target.checked;
    });

    agreeBtn.addEventListener('click', () => {
      // Example: save acceptance (replace with an API call if needed)
      const payload = {
        accepted: true,
        timestamp: new Date().toISOString()
      };

      // store in localStorage as an example
      localStorage.setItem('termsAccepted', JSON.stringify(payload));

      agreeBtn.textContent = 'Accepted ✓';
      agreeBtn.disabled = true;
      consent.disabled = true;
      alert('Thank you — terms accepted.');
    });

    printBtn.addEventListener('click', () => {
      window.print();
    });
  </script>
</body>
</html>
