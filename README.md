<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>The Motor Club — Rideshare & Delivery Car Rentals</title>
  <meta name="description" content="Weekly rideshare & delivery car rentals in Naples/Marco Island. Quick approval. Simple weekly payments. Start earning fast." />
  <meta name="robots" content="index,follow" />
  <meta property="og:title" content="The Motor Club — Weekly Driver Rentals" />
  <meta property="og:description" content="Need a car to start earning this week? Quick approval • Weekly payments • Naples/Marco Island." />
  <meta property="og:type" content="website" />
  <style>
    :root{
      --bg:#0b0f17; --card:#111827; --muted:#94a3b8; --text:#e5e7eb;
      --brand:#22c55e; --brand2:#38bdf8; --danger:#fb7185; --line:#1f2937;
      --shadow: 0 18px 55px rgba(0,0,0,.35);
      --radius: 18px;
    }
    *{box-sizing:border-box}
    body{
      margin:0; font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      background: radial-gradient(1200px 600px at 20% -10%, rgba(56,189,248,.25), transparent 55%),
                  radial-gradient(900px 500px at 90% 0%, rgba(34,197,94,.20), transparent 55%),
                  var(--bg);
      color:var(--text);
      line-height:1.45;
    }
    a{color:inherit}
    .wrap{max-width:1100px; margin:0 auto; padding:28px 18px 90px}
    header{display:flex; align-items:center; justify-content:space-between; gap:14px; padding:10px 0 18px}
    .logo{display:flex; align-items:center; gap:10px; font-weight:800; letter-spacing:.2px;}
    .badge{
      width:42px; height:42px; border-radius:14px;
      background: linear-gradient(135deg, var(--brand), var(--brand2));
      display:grid; place-items:center; box-shadow: var(--shadow);
      font-weight:900; color:#06210f;
    }
    .nav{display:flex; gap:14px; flex-wrap:wrap; color:var(--muted); font-weight:600; font-size:14px}
    .nav a{text-decoration:none; opacity:.9}
    .nav a:hover{opacity:1; color:var(--text)}
    .hero{display:grid; gap:18px; grid-template-columns: 1.15fr .85fr; align-items:stretch; margin-top:8px;}
    @media (max-width: 900px){ .hero{grid-template-columns:1fr} }
    .card{
      background: linear-gradient(180deg, rgba(255,255,255,.03), transparent 60%), var(--card);
      border:1px solid rgba(255,255,255,.06);
      border-radius: var(--radius);
      padding:22px;
      box-shadow: var(--shadow);
    }
    .pill{
      display:inline-flex; gap:8px; align-items:center;
      padding:8px 12px; border-radius:999px;
      background: rgba(34,197,94,.12);
      border:1px solid rgba(34,197,94,.25);
      color:#bbf7d0; font-weight:700; font-size:13px;
    }
    h1{margin:10px 0 10px; font-size:44px; line-height:1.05}
    @media (max-width: 520px){ h1{font-size:34px} }
    p{margin:0 0 12px; color:var(--muted); font-size:16px}
    .ctaRow{display:flex; gap:12px; flex-wrap:wrap; margin-top:14px}
    .btn{
      border:none; cursor:pointer; text-decoration:none;
      font-weight:800; letter-spacing:.2px;
      padding:12px 16px; border-radius:14px;
      display:inline-flex; align-items:center; gap:10px;
    }
    .btnPrimary{
      background: linear-gradient(135deg, var(--brand), var(--brand2));
      color:#061019;
      box-shadow: 0 14px 40px rgba(34,197,94,.18);
    }
    .btnGhost{
      background: rgba(148,163,184,.10);
      border:1px solid rgba(148,163,184,.22);
      color:var(--text);
    }
    .kpis{display:grid; grid-template-columns:repeat(3,1fr); gap:12px; margin-top:14px}
    @media (max-width: 520px){ .kpis{grid-template-columns:1fr} }
    .kpi{padding:12px; border-radius:16px; border:1px solid rgba(255,255,255,.06); background: rgba(255,255,255,.02)}
    .kpi b{font-size:18px}
    .kpi div{color:var(--muted); font-size:13px; margin-top:2px}
    .section{margin-top:18px}
    .grid3{display:grid; grid-template-columns:repeat(3,1fr); gap:12px}
    @media (max-width: 900px){ .grid3{grid-template-columns:1fr} }
    h2{margin:0 0 10px; font-size:22px}
    .list{display:grid; gap:10px; margin-top:10px}
    .row{display:flex; gap:10px; align-items:flex-start}
    .dot{
      width:10px; height:10px; border-radius:999px; margin-top:6px;
      background: linear-gradient(135deg, var(--brand), var(--brand2));
      flex:0 0 10px;
    }
    .small{font-size:13px; color:var(--muted)}
    .price{
      display:flex; justify-content:space-between; gap:10px; align-items:center;
      padding:12px; border-radius:16px;
      border:1px solid rgba(255,255,255,.06);
      background: rgba(255,255,255,.02);
    }
    .price strong{font-size:16px}
    .tag{
      font-size:12px; font-weight:800;
      padding:6px 10px; border-radius:999px;
      border:1px solid rgba(56,189,248,.25);
      background: rgba(56,189,248,.12);
      color:#bae6fd;
      white-space:nowrap;
    }
    form{display:grid; gap:10px; margin-top:10px}
    input, select, textarea{
      width:100%; padding:12px 12px; border-radius:14px;
      border:1px solid rgba(255,255,255,.10);
      background: rgba(0,0,0,.20);
      color:var(--text);
      outline:none;
    }
    textarea{min-height:90px; resize:vertical}
    .two{display:grid; grid-template-columns:1fr 1fr; gap:10px}
    @media (max-width: 700px){ .two{grid-template-columns:1fr} }
    .faq details{
      border:1px solid rgba(255,255,255,.06);
      background: rgba(255,255,255,.02);
      border-radius:16px;
      padding:12px 14px;
    }
    .faq summary{cursor:pointer; font-weight:800}
    .footer{margin-top:18px; display:flex; justify-content:space-between; gap:10px; flex-wrap:wrap; color:var(--muted); font-size:13px}
    .sticky{
      position:fixed; left:0; right:0; bottom:0;
      padding:10px 12px;
      background: rgba(11,15,23,.85);
      border-top:1px solid rgba(255,255,255,.06);
      backdrop-filter: blur(10px);
    }
    .sticky .wrap{padding:0; display:flex; gap:10px; justify-content:center}
    .btnCall{background: rgba(34,197,94,.16); border:1px solid rgba(34,197,94,.35); color:#d1fae5}
    .btnText{background: rgba(56,189,248,.14); border:1px solid rgba(56,189,248,.32); color:#e0f2fe}
    .hidden{display:none !important}
  </style>
</head>

<body>
  <div class="wrap">
    <header>
      <div class="logo">
        <div class="badge">MC</div>
        <div>
          <div style="font-size:16px">The Motor Club</div>
          <div class="small">Naples / Marco Island • Weekly driver rentals</div>
        </div>
      </div>
      <nav class="nav">
        <a href="#how">How it works</a>
        <a href="#pricing">Pricing</a>
        <a href="#requirements">Requirements</a>
        <a href="#apply">Apply</a>
      </nav>
    </header>

    <section class="hero">
      <div class="card">
        <span class="pill">🚗 Rideshare & Delivery Cars • Quick Approval</span>
        <h1>Need a car to start earning <span style="color:#a7f3d0">this week</span>?</h1>
        <p>
          Weekly car rentals for Uber, Lyft, DoorDash, Uber Eats, Instacart & gig work.
          Clean, reliable vehicles + a simple weekly payment system.
        </p>

        <div class="ctaRow">
          <a class="btn btnPrimary" href="#apply">⚡ Apply Now</a>
          <a class="btn btnGhost" href="#pricing">See Pricing</a>
        </div>

        <div class="kpis">
          <div class="kpi"><b>Local pickup</b><div>Naples / Marco Island area</div></div>
          <div class="kpi"><b>Weekly payments</b><div>Autopay preferred • no chasing</div></div>
          <div class="kpi"><b>GPS protected</b><div>Vehicles are monitored</div></div>
        </div>

        <div class="small" style="margin-top:10px">
          *Availability changes weekly. Final terms are in the rental agreement.
        </div>
      </div>

      <div class="card">
        <h2>What you get</h2>
        <div class="list">
          <div class="row"><div class="dot"></div><div><b>Reliable car</b><div class="small">Inspected before hand-off</div></div></div>
          <div class="row"><div class="dot"></div><div><b>Fast onboarding</b><div class="small">Quick approval + pickup scheduling</div></div></div>
          <div class="row"><div class="dot"></div><div><b>Clear rules</b><div class="small">Pay weekly, drive. Miss payments = return.</div></div></div>
          <div class="row"><div class="dot"></div><div><b>Simple support</b><div class="small">Basic maintenance per agreement</div></div></div>
        </div>

        <div style="margin-top:14px; border-top:1px solid rgba(255,255,255,.06); padding-top:14px">
          <h2>Service area</h2>
          <p class="small">Naples • Marco Island • Bonita Springs • Estero • Fort Myers (case-by-case)</p>
        </div>
      </div>
    </section>

    <section id="how" class="section card">
      <h2>How it works</h2>
      <div class="grid3">
        <div class="card" style="padding:16px">
          <b>1) Apply</b>
          <div class="small">Submit your info + which app you drive for.</div>
        </div>
        <div class="card" style="padding:16px">
          <b>2) Get approved</b>
          <div class="small">We verify basics and schedule pickup.</div>
        </div>
        <div class="card" style="padding:16px">
          <b>3) Pay & drive</b>
          <div class="small">Weekly payments • stay current • keep it clean.</div>
        </div>
      </div>
    </section>

    <section id="pricing" class="section card">
      <h2>Pricing (example tiers)</h2>
      <p class="small">Adjust these to your real numbers. Your angle: local, fast, and slightly cheaper with tighter rules.</p>

      <div class="grid3" style="margin-top:12px">
        <div class="card" style="padding:16px">
          <div class="price"><strong>Economy</strong><span class="tag">$325–$350 / week</span></div>
          <div class="small" style="margin-top:10px">Prius / Corolla / Elantra-type cars (best for heavy miles)</div>
        </div>

        <div class="card" style="padding:16px">
          <div class="price"><strong>Standard</strong><span class="tag">$350–$400 / week</span></div>
          <div class="small" style="margin-top:10px">Accord / Camry / Altima-type cars (vacation + rideshare)</div>
        </div>

        <div class="card" style="padding:16px">
          <div class="price"><strong>Premium</strong><span class="tag">Ask</span></div>
          <div class="small" style="margin-top:10px">SUVs & higher-end vehicles (higher deposit + stricter screening)</div>
        </div>
      </div>
    </section>

    <section id="requirements" class="section card">
      <h2>Minimum requirements</h2>
      <div class="grid3">
        <div class="card" style="padding:16px">
          <b>Driver</b>
          <div class="small" style="margin-top:8px">
            • Valid driver’s license<br>
            • 21+ (25+ for some vehicles)<br>
            • Clean driving history preferred
          </div>
        </div>
        <div class="card" style="padding:16px">
          <b>Payments</b>
          <div class="small" style="margin-top:8px">
            • First week due at pickup<br>
            • Deposit required (varies)<br>
            • Weekly autopay preferred
          </div>
        </div>
        <div class="card" style="padding:16px">
          <b>Rules</b>
          <div class="small" style="margin-top:8px">
            • Keep vehicle clean<br>
            • No smoking in vehicle<br>
            • Missed payment = return
          </div>
        </div>
      </div>
    </section>

    <section id="apply" class="section card">
      <h2>Apply now</h2>
      <p class="small">Fastest path: submit this form + we text you pickup options. (This form saves leads in Netlify.)</p>

      <!-- NETLIFY FORMS (no extra service needed) -->
      <form name="motorclub-application"
            method="POST"
            data-netlify="true"
            netlify-honeypot="bot-field"
            action="/thanks.html">

        <input type="hidden" name="form-name" value="motorclub-application" />

        <!-- Honeypot field -->
        <p class="hidden">
          <label>Don’t fill this out: <input name="bot-field" /></label>
        </p>

        <div class="two">
          <input name="Name" placeholder="Full name" required />
          <input name="Phone" placeholder="Phone number" inputmode="tel" required />
        </div>

        <div class="two">
          <select name="Platform" required>
            <option value="">Which app do you drive for?</option>
            <option>Uber</option>
            <option>Lyft</option>
            <option>DoorDash</option>
            <option>Uber Eats</option>
            <option>Instacart</option>
            <option>Other</option>
          </select>

          <select name="Start" required>
            <option value="">How soon do you want to start?</option>
            <option>Today</option>
            <option>This week</option>
            <option>Next week</option>
          </select>
        </div>

        <div class="two">
          <select name="Tier" required>
            <option value="">Which tier are you looking for?</option>
            <option>Economy</option>
            <option>Standard</option>
            <option>Premium</option>
          </select>

          <select name="Payment Method" required>
            <option value="">Preferred payment method</option>
            <option>Card / Autopay</option>
            <option>Cash App</option>
            <option>Zelle</option>
            <option>Other</option>
          </select>
        </div>

        <textarea name="Notes" placeholder="Anything we should know? (preferred vehicle, schedule, driving history, etc.)"></textarea>

        <button class="btn btnPrimary" type="submit">✅ Submit Application</button>

        <div class="small">
          By submitting, you agree to be contacted about availability and terms. Insurance and final pricing depend on vehicle/program and are confirmed in the agreement.
        </div>
      </form>
    </section>

    <section class="section card faq">
      <h2>FAQ</h2>
      <div class="list">
        <details>
          <summary>Do you do “no credit check”?</summary>
          <div class="small" style="margin-top:8px">Some vehicles may not require credit checks. Approval is based on availability and payment reliability.</div>
        </details>
        <details>
          <summary>Is insurance included?</summary>
          <div class="small" style="margin-top:8px">It depends on the vehicle/program. We confirm during approval and in the agreement.</div>
        </details>
        <details>
          <summary>What happens if I miss a payment?</summary>
          <div class="small" style="margin-top:8px">If payment isn’t received, the vehicle must be returned per agreement. Vehicles are GPS monitored.</div>
        </details>
      </div>
    </section>

    <div class="footer">
      <div>© <span id="year"></span> The Motor Club</div>
      <div class="small">Naples / Marco Island • Weekly rentals</div>
    </div>
  </div>

  <!-- Sticky buttons (EDIT YOUR PHONE + EMAIL) -->
  <div class="sticky">
    <div class="wrap">
      <a class="btn btnCall" href="tel:+1YOURPHONENUMBER">📞 Call</a>
      <a class="btn btnText" href="sms:+1YOURPHONENUMBER?&body=Hi%20I%20want%20to%20apply%20for%20a%20weekly%20rental.%20When%20can%20I%20start%3F">💬 Text</a>
      <a class="btn btnPrimary" href="#apply">⚡ Apply</a>
    </div>
  </div>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html> Starter Kit: Basics

[![Built with Starlight](https://astro.badg.es/v2/built-with-starlight/tiny.svg)](https://starlight.astro.build)

```
npm create astro@latest -- --template starlight
```

<!-- ASTRO:REMOVE:START -->

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/starlight/tree/main/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/starlight/tree/main/examples/basics)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/withastro/starlight&create_from_path=examples/basics)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fwithastro%2Fstarlight%2Ftree%2Fmain%2Fexamples%2Fbasics&project-name=my-starlight-docs&repository-name=my-starlight-docs)

<!-- ASTRO:REMOVE:END -->

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro + Starlight project, you'll see the following folders and files:

```
.
├── public/
├── src/
│   ├── assets/
│   ├── content/
│   │   └── docs/
│   └── content.config.ts
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

Starlight looks for `.md` or `.mdx` files in the `src/content/docs/` directory. Each file is exposed as a route based on its file name.

Images can be added to `src/assets/` and embedded in Markdown with a relative link.

Static assets, like favicons, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Check out [Starlight’s docs](https://starlight.astro.build/), read [the Astro documentation](https://docs.astro.build), or jump into the [Astro Discord server](https://astro.build/chat).
