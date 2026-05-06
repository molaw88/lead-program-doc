<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DOC Work Assignment Modernization</title>

  <style>
    :root {
      --navy:#071B33;
      --blue:#123E6B;
      --gold:#C9A227;
      --gray:#F4F6F8;
      --dark:#1F2933;
      --white:#FFFFFF;
      --muted:#6B7280;
      --green:#2E7D32;
      --red:#B91C1C;
      --amber:#B7791F;
    }

    * { margin:0; padding:0; box-sizing:border-box; }
    html { scroll-behavior:smooth; }

    body {
      font-family: Georgia, "Times New Roman", serif;
      color:var(--dark);
      background:var(--white);
      line-height:1.6;
    }

    section, header, footer { width:100%; }

    .content-wrapper {
      width:100%;
      max-width:1400px;
      margin:0 auto;
    }

    nav {
      position:fixed;
      top:0;
      width:100%;
      background:rgba(7,27,51,.96);
      color:white;
      z-index:1000;
      display:flex;
      justify-content:center;
      align-items:center;
      padding:16px 40px;
      backdrop-filter:blur(8px);
      border-bottom:1px solid rgba(255,255,255,.08);
    }

    .nav-container {
      width:100%;
      max-width:1400px;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    .logo {
      color:var(--gold);
      font-weight:bold;
      letter-spacing:.08em;
      text-transform:uppercase;
      white-space:nowrap;
      font-size:1rem;
    }

    .nav-links {
      display:flex;
      align-items:center;
      gap:24px;
      flex-wrap:wrap;
      justify-content:center;
    }

    .nav-links a {
      color:white;
      text-decoration:none;
      font-size:.95rem;
      transition:.2s ease;
    }

    .nav-links a:hover { color:var(--gold); }

    header {
      min-height:100vh;
      background:
      linear-gradient(rgba(7,27,51,.9), rgba(7,27,51,.92)),
      url("https://images.unsplash.com/photo-1505664194779-8beaceb93744?auto=format&fit=crop&w=1600&q=80");
      background-size:cover;
      background-position:center;
      display:flex;
      align-items:center;
      padding:100px 8%;
      color:white;
    }

    .hero { max-width:950px; }

    .eyebrow {
      color:var(--gold);
      text-transform:uppercase;
      letter-spacing:.18em;
      font-size:.85rem;
      margin-bottom:18px;
      font-weight:bold;
    }

    h1 {
      font-size:clamp(3rem,7vw,6rem);
      line-height:.95;
      margin-bottom:24px;
    }

    h2 {
      font-size:clamp(2.1rem,4vw,4rem);
      line-height:1.1;
      margin-bottom:18px;
    }

    h3 { margin-bottom:10px; color:var(--blue); }

    header p {
      font-size:clamp(1.2rem,2vw,1.7rem);
      max-width:850px;
      color:#E5E7EB;
    }

    .button {
      background:var(--gold);
      padding:13px 26px;
      display:inline-block;
      margin-top:28px;
      text-decoration:none;
      color:var(--navy);
      font-weight:bold;
      border-radius:3px;
      transition:.2s ease;
    }

    .button:hover { transform:translateY(-2px); }

    section { padding:85px 8%; }

    .section-dark { background:var(--navy); color:white; }
    .section-gray { background:var(--gray); }
    .section-dark h3 { color:var(--gold); }

    .intro {
      max-width:950px;
      font-size:1.15rem;
      color:var(--muted);
      margin-bottom:35px;
    }

    .section-dark .intro { color:#CBD5E1; }

    .grid {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:22px;
      margin-top:30px;
    }

    .card {
      background:white;
      padding:26px;
      border-left:5px solid var(--gold);
      box-shadow:0 10px 25px rgba(0,0,0,.08);
      border-radius:4px;
      transition:.2s ease;
    }

    .card:hover { transform:translateY(-4px); }

    .section-dark .card {
      background:#0E2A4A;
      color:white;
      box-shadow:none;
    }

    .card p { color:var(--muted); }
    .section-dark .card p { color:#D1D5DB; }

    .big-quote {
      font-size:clamp(1.6rem,3vw,2.8rem);
      line-height:1.25;
      margin-top:35px;
      border-left:6px solid var(--gold);
      padding-left:24px;
      max-width:1100px;
      color:var(--blue);
    }

    .section-dark .big-quote { color:white; }

    .workflow {
      display:flex;
      flex-wrap:wrap;
      gap:12px;
      margin-top:30px;
    }

    .step {
      background:var(--blue);
      color:white;
      padding:18px;
      flex:1 1 160px;
      text-align:center;
      font-weight:bold;
      border-radius:3px;
    }

    .timeline {
      border-left:4px solid var(--gold);
      padding-left:28px;
      max-width:1000px;
      margin-top:35px;
    }

    .phase {
      margin-bottom:32px;
      position:relative;
    }

    .phase::before {
      content:"";
      position:absolute;
      left:-40px;
      top:6px;
      width:18px;
      height:18px;
      background:var(--gold);
      border-radius:50%;
    }

    .phase h3 {
      color:var(--gold);
      font-size:1.4rem;
    }

    .phase p { color:#E5E7EB; }

    .metric {
      text-align:center;
      padding:28px;
      background:white;
      border-top:6px solid var(--gold);
      box-shadow:0 8px 22px rgba(0,0,0,.08);
      border-radius:4px;
    }

    .metric span {
      display:block;
      font-size:2.35rem;
      font-weight:bold;
      color:var(--blue);
      margin-bottom:8px;
    }

    .status-green { border-top-color:var(--green); }
    .status-red { border-top-color:var(--red); }
    .status-amber { border-top-color:var(--amber); }

    .status-green span { color:var(--green); }
    .status-red span { color:var(--red); }
    .status-amber span { color:var(--amber); }

    small { color:var(--muted); }

    footer {
      background:#03101F;
      color:#CBD5E1;
      padding:35px 8%;
      text-align:center;
      font-size:.95rem;
    }

    @media(max-width:768px){
      nav { padding:16px 20px; }

      .nav-container {
        flex-direction:column;
        align-items:center;
        text-align:center;
      }

      .nav-links {
        margin-top:10px;
        gap:12px;
      }

      header { padding-top:170px; }
      .workflow { flex-direction:column; }
    }
  </style>
</head>

<body>

<nav>
  <div class="nav-container">
    <div class="logo">DOC Modernization</div>
    <div class="nav-links">
      <a href="#problem">Problem</a>
      <a href="#friction">Friction</a>
      <a href="#roadmap">Roadmap</a>
      <a href="#dashboard">Dashboard</a>
      <a href="#future">Future</a>
      <a href="#metrics">Metrics</a>
    </div>
  </div>
</nav>

<header>
  <div class="content-wrapper">
    <div class="hero">
      <div class="eyebrow">Massachusetts Department of Correction</div>
      <h1>Modernizing Work Assignment Tracking</h1>
      <p>
        From manual compliance to real-time workforce management: a project management approach to reducing administrative lag, standardizing execution, and improving institutional efficiency.
      </p>
      <a href="#problem" class="button">View Project ↓</a>
    </div>
  </div>
</header>

<section id="problem">
  <div class="content-wrapper">
    <h2>The Problem</h2>
    <p class="intro">
      The Department has policies requiring daily attendance tracking and monthly performance evaluations. Yet across facilities, execution can vary based on forms, practices, staff workflow, and system usability.
    </p>

    <div class="big-quote">
      The issue is not whether data is collected—it is how long it takes to become usable.
    </div>

    <div class="grid">
      <div class="card">
        <h3>Policy Exists</h3>
        <p>Attendance and performance responsibilities are clearly identified within institutional work assignment procedures.</p>
      </div>

      <div class="card">
        <h3>Execution Varies</h3>
        <p>Facilities may differ in job titles, pay rates, forms, hiring practices, waitlists, and accountability procedures.</p>
      </div>

      <div class="card">
        <h3>Data Lags</h3>
        <p>Manual entry creates delay between the actual work activity and the point when the data becomes useful for decision-making.</p>
      </div>
    </div>
  </div>
</section>

<section class="section-gray">
  <div class="content-wrapper">
    <h2>Current IMS Workflow</h2>
    <p class="intro">
      Work assignment tracking is currently managed through IMS. Supervisors manually enter attendance and complete monthly performance ratings.
    </p>

    <div class="workflow">
      <div class="step">Work Assignment</div>
      <div class="step">Daily Attendance</div>
      <div class="step">Manual IMS Entry</div>
      <div class="step">Monthly Rating</div>
      <div class="step">Payroll / Good Time</div>
    </div>

    <div class="big-quote">
      The system records activity, but it does not yet fully manage performance in real time.
    </div>
  </div>
</section>

<section id="friction" class="section-dark">
  <div class="content-wrapper">
    <h2>Operational Friction Analysis</h2>
    <p class="intro">Where the system breaks down between policy, practice, and technology.</p>

    <div class="grid">
      <div class="card">
        <h3>Administrative Lag</h3>
        <p>Delays between real-world activity and system entry reduce the usefulness of attendance and performance data.</p>
      </div>

      <div class="card">
        <h3>Manual Entry Risk</h3>
        <p>Heavy reliance on individual staff entry increases inconsistency, missing fields, and delayed completion.</p>
      </div>

      <div class="card">
        <h3>Lack of Standardization</h3>
        <p>Job titles, forms, pay rates, and institutional practices vary, limiting department-wide consistency.</p>
      </div>

      <div class="card">
        <h3>Fragmented Systems</h3>
        <p>Attendance, payroll, earned good time, and reentry preparation are connected in purpose but not fully integrated in workflow.</p>
      </div>

      <div class="card">
        <h3>Limited Visibility</h3>
        <p>Leadership lacks a single real-time dashboard showing compliance, performance trends, and process bottlenecks.</p>
      </div>

      <div class="card">
        <h3>Training Gaps</h3>
        <p>Work Assignment Officers and supervisors need consistent training, shared forms, and recurring coordination meetings.</p>
      </div>
    </div>
  </div>
</section>

<section id="roadmap" class="section-dark">
  <div class="content-wrapper">
    <h2>Project Roadmap</h2>
    <p class="intro">A phased project management approach to modernization.</p>

    <div class="timeline">
      <div class="phase">
        <h3>Phase 1 — Current State Validation</h3>
        <p>Meet with Work Assignment Officers, supervisors, facility leadership, and stakeholders to understand how attendance and performance tracking actually occurs across institutions.</p>
      </div>

      <div class="phase">
        <h3>Phase 2 — Friction Mapping</h3>
        <p>Document delays, duplication, inconsistent forms, unclear responsibilities, and manual entry risks in the current workflow.</p>
      </div>

      <div class="phase">
        <h3>Phase 3 — Future State Design</h3>
        <p>Design a standardized model that includes consistent job descriptions, digital forms, clearer responsibilities, and stronger connection between attendance, payroll, earned good time, and reentry goals.</p>
      </div>

      <div class="phase">
        <h3>Phase 4 — Stakeholder Co-Design</h3>
        <p>Return to frontline users and stakeholders to pressure-test the proposed design. Adjust the model based on real operational constraints.</p>
      </div>

      <div class="phase">
        <h3>Phase 5 — Pilot Implementation</h3>
        <p>Test the redesigned workflow at selected facilities using standardized forms, defined training, and measurable compliance expectations.</p>
      </div>

      <div class="phase">
        <h3>Phase 6 — Evaluation & Scale</h3>
        <p>Measure results, identify remaining barriers, refine the process, and determine whether the model should be expanded department-wide.</p>
      </div>
    </div>
  </div>
</section>

<section id="dashboard" class="section-gray">
  <div class="content-wrapper">
    <h2>Command-Level Compliance Dashboard</h2>
    <p class="intro">
      Leadership does not need raw attendance data. Leadership needs compliance at a glance.
    </p>

    <div class="grid">
      <div class="metric status-green">
        <span>92%</span>
        Attendance Entered Within 2 Hours<br>
        <small>Target: 95%</small>
      </div>

      <div class="metric status-red">
        <span>14</span>
        High-Risk Missing Evaluations<br>
        <small>Past 1st / 3rd Monthly Deadline</small>
      </div>

      <div class="metric status-amber">
        <span>78%</span>
        On Track for 80% Participation<br>
        <small>Earned Good Time Forecast</small>
      </div>

      <div class="metric">
        <span>80%</span>
        Minimum Participation Threshold<br>
        <small>Required for Earned Good Time Eligibility</small>
      </div>
    </div>

    <div class="big-quote">
      Leadership should not search for compliance issues—they should see them immediately.
    </div>
  </div>
</section>

<section>
  <div class="content-wrapper">
    <h2>Standardized Reason Code Library</h2>
    <p class="intro">
      Free-text comments create data silos. Standardized reason codes create system-wide insight.
    </p>

    <div class="grid">
      <div class="card">
        <h3>Medical / Sick Call</h3>
        <p>Health-related absences documented through medical channels.</p>
      </div>

      <div class="card">
        <h3>Legal / Court / Attorney</h3>
        <p>Absences due to legal obligations, parole hearings, attorney visits, or scheduled proceedings.</p>
      </div>

      <div class="card">
        <h3>Institutional Lockdown</h3>
        <p>Facility-wide or unit-specific restrictions preventing attendance.</p>
      </div>

      <div class="card">
        <h3>Program Conflict</h3>
        <p>Conflict with education, treatment, religious services, or other approved programming.</p>
      </div>

      <div class="card">
        <h3>Unexcused Absence</h3>
        <p>Absence without approved or documented reason.</p>
      </div>
    </div>

    <div class="big-quote">
      Standardized inputs transform isolated comments into actionable intelligence.
    </div>
  </div>
</section>

<section class="section-gray">
  <div class="content-wrapper">
    <h2>Mobile-First Supervisor Interface</h2>
    <p class="intro">
      The system must move to where the work happens. Supervisors are often in kitchens, gyms, shops, laundry areas, and maintenance spaces—not sitting at a desktop.
    </p>

    <div class="grid">
      <div class="card">
        <h3>Tablet-Based Entry</h3>
        <p>Supervisors can record attendance directly in the field at the start or end of the shift.</p>
      </div>

      <div class="card">
        <h3>One-Tap Status Updates</h3>
        <p>Quick selection for Present, Absent, Excused, or Unexcused with required reason codes.</p>
      </div>

      <div class="card">
        <h3>Real-Time Sync</h3>
        <p>Data updates immediately across the system, reducing end-of-day or end-of-week entry delays.</p>
      </div>
    </div>

    <div class="big-quote">
      The closer data entry is to the moment of action, the more valuable the data becomes.
    </div>
  </div>
</section>

<section class="section-dark">
  <div class="content-wrapper">
    <h2>Technical Framework</h2>
    <p class="intro">
      The IMS replacement creates an opportunity to move from desktop-based manual entry to a secure, tablet-based workforce management model.
    </p>

    <div class="grid">
      <div class="card">
        <h3>Managed Tablet Deployment</h3>
        <p>Dedicated 8-inch ruggedized tablets preserve professional optics, reduce input errors, and avoid the appearance of personal phone use.</p>
      </div>

      <div class="card">
        <h3>Kiosk Mode Security</h3>
        <p>Devices are locked through Mobile Device Management so they run only the approved DOC application with restricted access.</p>
      </div>

      <div class="card">
        <h3>Store-and-Forward Architecture</h3>
        <p>Attendance can be captured offline in dead zones and automatically synced when the tablet reaches a secure Wi-Fi hotspot.</p>
      </div>

      <div class="card">
        <h3>QR Identity Validation</h3>
        <p>Supervisors scan incarcerated individual ID codes to verify assignment status and reduce manual typing errors.</p>
      </div>

      <div class="card">
        <h3>Subtractive Compliance</h3>
        <p>Missing attendance entries trigger alerts, dashboard flags, and payroll linkage so compliance becomes built into the workflow.</p>
      </div>

      <div class="card">
        <h3>API Integration</h3>
        <p>Tablet entries, reason codes, timestamps, and performance data map directly into the new IMS backend.</p>
      </div>
    </div>

    <div class="big-quote">
      The goal is not to digitize the old process. The goal is to redesign the process so compliance becomes the path of least resistance.
    </div>
  </div>
</section>

<section class="section-gray">
  <div class="content-wrapper">
    <h2>Modernization Comparison</h2>
    <p class="intro">
      The redesigned model shifts work assignment tracking from delayed manual entry to real-time, verified, and standardized data capture.
    </p>

    <div class="grid">
      <div class="card">
        <h3>Legacy: Delayed Entry</h3>
        <p>Attendance is often entered after the shift, creating reliance on memory, paper notes, or delayed desktop access.</p>
      </div>

      <div class="card">
        <h3>Modernized: Point of Action</h3>
        <p>Attendance is captured directly where the work occurs using tablet-based entry.</p>
      </div>

      <div class="card">
        <h3>Legacy: Free Text</h3>
        <p>Absence explanations may be buried in inconsistent manual comments.</p>
      </div>

      <div class="card">
        <h3>Modernized: Reason Codes</h3>
        <p>Standardized codes allow the Department to analyze absence trends across facilities.</p>
      </div>

      <div class="card">
        <h3>Legacy: Static Desktop</h3>
        <p>Supervisors must return to an office workstation to complete entries.</p>
      </div>

      <div class="card">
        <h3>Modernized: Offline Sync</h3>
        <p>Store-and-forward architecture allows work to continue even without constant connectivity.</p>
      </div>
    </div>
  </div>
</section>

<section id="future">
  <div class="content-wrapper">
    <h2>Future State System Design</h2>
    <p class="intro">
      The upcoming IMS replacement creates a once-in-a-generation opportunity to align process, technology, and behavior into one operational model.
    </p>

    <div class="grid">
      <div class="card">
        <h3>Real-Time Data Capture</h3>
        <p>Attendance should be entered as close to the point of activity as possible.</p>
      </div>

      <div class="card">
        <h3>Smart Forms</h3>
        <p>If absent, the system requires a reason code. If performance is unsatisfactory, the system requires documentation.</p>
      </div>

      <div class="card">
        <h3>Hard Stops</h3>
        <p>Incomplete attendance and evaluation records cannot be submitted without required fields.</p>
      </div>

      <div class="card">
        <h3>Standardized Job Framework</h3>
        <p>Use consistent general job titles with functional job titles across institutions.</p>
      </div>

      <div class="card">
        <h3>Integrated Workflow</h3>
        <p>Connect attendance, payroll, earned good time, and reentry preparation into one coherent process.</p>
      </div>

      <div class="card">
        <h3>Automated Alerts</h3>
        <p>Flag missing attendance entries, overdue evaluations, and incomplete required fields.</p>
      </div>
    </div>
  </div>
</section>

<section class="section-dark">
  <div class="content-wrapper">
    <h2>Workforce Development Integration</h2>
    <p class="intro">
      Work assignments should not only track labor. They should build employability, document skills, and support successful reentry.
    </p>

    <div class="grid">
      <div class="card">
        <h3>Satisfactory Performance</h3>
        <p>Contributes to Earned Good Time calculations and positive progress tracking.</p>
      </div>

      <div class="card">
        <h3>Unsatisfactory Performance</h3>
        <p>Triggers review flags for Work Assignment Officers to determine whether reassignment or intervention is needed.</p>
      </div>

      <div class="card">
        <h3>Skill Tracking</h3>
        <p>Assignments contribute to a documented skills profile connected to reentry planning and resume development.</p>
      </div>
    </div>

    <div class="big-quote">
      Work assignments become more than institutional labor—they become a pathway to workforce readiness.
    </div>
  </div>
</section>

<section id="metrics">
  <div class="content-wrapper">
    <h2>Pilot Metrics</h2>
    <p class="intro">
      Modernization must be measured through speed, accuracy, consistency, compliance, and usability.
    </p>

    <div class="grid">
      <div class="metric">
        <span>Same-Day</span>
        Attendance Entry Rate
      </div>

      <div class="metric">
        <span>2 Hours</span>
        Entry After Shift End<br>
        <small>Target Compliance Window</small>
      </div>

      <div class="metric">
        <span>On-Time</span>
        Monthly Performance Completion
      </div>

      <div class="metric">
        <span>Lower</span>
        Error and Missing Field Rate
      </div>

      <div class="metric">
        <span>80%</span>
        Minimum Participation Threshold<br>
        <small>Required for Earned Good Time Eligibility</small>
      </div>

      <div class="metric">
        <span>Faster</span>
        Time Required Per Entry
      </div>
    </div>
  </div>
</section>

<section class="section-dark">
  <div class="content-wrapper">
    <h2>Conclusion</h2>
    <p class="intro">
      Upgrading IMS alone will not solve the problem. The opportunity is to redesign the process before the platform is fully rebuilt.
    </p>

    <div class="big-quote">
      This is not only a policy issue. It is an execution issue. And execution can be redesigned.
    </div>
  </div>
</section>

<footer>
  <div class="content-wrapper">
    Work Assignment Data Modernization Initiative | Project Management Framework | Massachusetts Department of Correction
  </div>
</footer>

</body>
</html>
