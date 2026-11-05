<style>
  :root {
    --mxp-navy: #0b1f35;
    --mxp-slate: #16324f;
    --mxp-cyan: #39c6df;
    --mxp-blue: #4b8ff7;
    --mxp-violet: #9a79e8;
    --mxp-gold: #f1b35b;
    --mxp-ink: #17263a;
    --mxp-muted: #5b6b7c;
    --mxp-paper: #f5f8fc;
    --mxp-white: #ffffff;
  }

  .mxp4s-home {
    width: min(1180px, calc(100vw - 32px));
    margin-left: 50%;
    transform: translateX(-50%);
    color: var(--mxp-ink);
    font-size: 1.02rem;
    line-height: 1.7;
  }

  .mxp4s-home * {
    box-sizing: border-box;
  }

  .mxp-hero {
    position: relative;
    overflow: hidden;
    margin: 1.25rem 0 2rem;
    border-radius: 22px;
    background:
      radial-gradient(circle at 88% 12%, rgba(154, 121, 232, 0.28), transparent 30%),
      radial-gradient(circle at 12% 90%, rgba(57, 198, 223, 0.22), transparent 32%),
      linear-gradient(135deg, #081827 0%, var(--mxp-navy) 48%, #142d49 100%);
    box-shadow: 0 22px 55px rgba(9, 31, 53, 0.22);
  }

  .mxp-hero-copy {
    position: relative;
    z-index: 1;
    max-width: 900px;
    padding: clamp(2rem, 5vw, 4.5rem) clamp(1.4rem, 5vw, 4.5rem) 2.25rem;
    color: var(--mxp-white);
  }

  .mxp-eyebrow {
    display: inline-block;
    margin-bottom: 0.9rem;
    color: #a9ecf6;
    font-size: 0.8rem;
    font-weight: 800;
    letter-spacing: 0.13em;
    text-transform: uppercase;
  }

  .mxp-hero h1 {
    margin: 0;
    color: var(--mxp-white);
    font-size: clamp(2rem, 5vw, 4.4rem);
    line-height: 1.04;
    letter-spacing: -0.035em;
  }

  .mxp-hero h1 span {
    color: #a9ecf6;
  }

  .mxp-hero-lead {
    max-width: 760px;
    margin: 1.2rem 0 0;
    color: #dce9f5;
    font-size: clamp(1.05rem, 2vw, 1.35rem);
    line-height: 1.55;
  }

  .mxp-event-line {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem 1.2rem;
    margin-top: 1.45rem;
    color: #eef7ff;
    font-size: 0.95rem;
    font-weight: 650;
  }

  .mxp-event-line span::before {
    content: "";
    display: inline-block;
    width: 0.52rem;
    height: 0.52rem;
    margin-right: 0.55rem;
    border-radius: 50%;
    background: var(--mxp-cyan);
    box-shadow: 0 0 16px rgba(57, 198, 223, 0.75);
  }

  .mxp-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin-top: 1.6rem;
  }

  .mxp-actions a {
    display: inline-block;
    padding: 0.68rem 1rem;
    border: 1px solid rgba(255, 255, 255, 0.24);
    border-radius: 999px;
    background: rgba(255, 255, 255, 0.08);
    color: var(--mxp-white);
    font-size: 0.9rem;
    font-weight: 750;
    text-decoration: none;
    transition: transform 150ms ease, background 150ms ease, border-color 150ms ease;
  }

  .mxp-actions a:first-child {
    border-color: var(--mxp-cyan);
    background: var(--mxp-cyan);
    color: #072033;
  }

  .mxp-actions a:hover {
    transform: translateY(-2px);
    border-color: #a9ecf6;
    background: rgba(255, 255, 255, 0.15);
  }

  .mxp-actions a:first-child:hover {
    background: #74dceb;
  }

  .mxp-hero figure {
    margin: 0;
    background: #081827;
  }

  .mxp-hero figure img {
    display: block;
    width: 100%;
    height: auto;
    border-top: 1px solid rgba(255, 255, 255, 0.12);
  }

  .mxp-hero figcaption {
    padding: 0.75rem 1.25rem 1rem;
    color: #afc4d8;
    font-size: 0.82rem;
    text-align: center;
  }

  .mxp-section {
    margin: 3.25rem 0;
  }

  .mxp-section h2 {
    margin: 0 0 0.8rem;
    color: var(--mxp-navy);
    font-size: clamp(1.65rem, 3vw, 2.45rem);
    line-height: 1.2;
    letter-spacing: -0.025em;
  }

  .mxp-section-intro {
    max-width: 850px;
    margin: 0;
    color: var(--mxp-muted);
    font-size: 1.08rem;
  }

  .mxp-mission {
    display: grid;
    grid-template-columns: minmax(0, 1.35fr) minmax(260px, 0.65fr);
    gap: 1.4rem;
    align-items: stretch;
  }

  .mxp-mission-main,
  .mxp-program-card {
    padding: clamp(1.35rem, 3vw, 2.15rem);
    border: 1px solid #dce6f1;
    border-radius: 18px;
    background: var(--mxp-white);
    box-shadow: 0 12px 30px rgba(18, 50, 79, 0.08);
  }

  .mxp-mission-main p:first-of-type {
    margin-top: 0;
  }

  .mxp-mission-main p:last-child {
    margin-bottom: 0;
  }

  .mxp-program-card {
    border: 0;
    background: linear-gradient(145deg, #edf8fc, #f4f1fc);
  }

  .mxp-program-card h3 {
    margin: 0 0 1rem;
    color: var(--mxp-navy);
    font-size: 1.3rem;
  }

  .mxp-program-card ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .mxp-program-card li {
    position: relative;
    margin: 0.75rem 0;
    padding-left: 1.35rem;
  }

  .mxp-program-card li::before {
    content: "";
    position: absolute;
    top: 0.65em;
    left: 0;
    width: 0.55rem;
    height: 0.55rem;
    border-radius: 3px;
    background: linear-gradient(135deg, var(--mxp-cyan), var(--mxp-violet));
  }

  .mxp-principles {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
    margin-top: 1.45rem;
  }

  .mxp-principle {
    min-height: 205px;
    padding: 1.45rem;
    border: 1px solid #dce6f1;
    border-radius: 16px;
    background: var(--mxp-paper);
  }

  .mxp-principle:nth-child(1) {
    border-top: 4px solid var(--mxp-cyan);
  }

  .mxp-principle:nth-child(2) {
    border-top: 4px solid var(--mxp-violet);
  }

  .mxp-principle:nth-child(3) {
    border-top: 4px solid var(--mxp-gold);
  }

  .mxp-principle h3 {
    margin: 0 0 0.55rem;
    color: var(--mxp-navy);
    font-size: 1.16rem;
  }

  .mxp-principle p {
    margin: 0;
    color: var(--mxp-muted);
    font-size: 0.96rem;
  }

  .mxp-callout {
    padding: clamp(1.6rem, 4vw, 3rem);
    border-radius: 20px;
    background:
      linear-gradient(110deg, rgba(57, 198, 223, 0.11), rgba(154, 121, 232, 0.11)),
      var(--mxp-white);
    border: 1px solid #d8e6f2;
  }

  .mxp-callout strong {
    color: var(--mxp-navy);
  }

  .mxp-callout p:last-child {
    margin-bottom: 0;
  }

  .mxp-quicklinks {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 0.8rem;
    margin: 3rem 0 1.5rem;
  }

  .mxp-quicklinks a {
    padding: 1rem;
    border: 1px solid #dce6f1;
    border-radius: 14px;
    background: var(--mxp-white);
    color: var(--mxp-slate);
    font-weight: 750;
    text-align: center;
    text-decoration: none;
    box-shadow: 0 8px 22px rgba(18, 50, 79, 0.06);
  }

  .mxp-quicklinks a:hover {
    border-color: var(--mxp-blue);
    color: #245fae;
  }

  @media (max-width: 820px) {
    .mxp-mission,
    .mxp-principles {
      grid-template-columns: 1fr;
    }

    .mxp-principle {
      min-height: auto;
    }

    .mxp-quicklinks {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 520px) {
    .mxp4s-home {
      width: min(100%, calc(100vw - 20px));
    }

    .mxp-hero {
      border-radius: 15px;
    }

    .mxp-quicklinks {
      grid-template-columns: 1fr;
    }
  }
</style>

<main class="mxp4s-home">
  <header class="mxp-hero">
    <div class="mxp-hero-copy">
      <span class="mxp-eyebrow">Second MxP4S Workshop</span>
      <h1>Mixed- and Adaptive-Precision Numerics for <span>Scientific Computing</span></h1>
      <p class="mxp-hero-lead">
        Scientific computing needs more performance without surrendering reliable results.
        MxP4S brings together the algorithms, software, hardware, and applications that can make that possible.
      </p>

  <div class="mxp-event-line" aria-label="Event details">
    <span>IPDPS 2027</span>
    <span>Seattle, Washington, USA</span>
    <span>June 1–5, 2027</span>
  </div>

  <nav class="mxp-actions" aria-label="Primary workshop links">
    <a href="dates.html">Important dates</a>
    <a href="topics.html">Topics of interest</a>
    <a href="format.html">Format and schedule</a>
    <a href="organizers.html">Organizers</a>
  </nav>
</div>

<figure>
  <img
    src="{{ '/img/mixed_precision_workgroup.png' | relative_url }}"
    alt="Researchers representing FP64, FP32, TF32, BF16, FP16, FP8, and INT8 collaborate on a scientific problem, alongside an FP64 system built from an FP8 core."
  >
  <figcaption>Different precisions, complementary strengths, one shared scientific objective.</figcaption>
</figure>

  </header>

  <section class="mxp-section mxp-mission" aria-labelledby="welcome-heading">
    <div class="mxp-mission-main">
      <h2 id="welcome-heading">Welcome to MxP4S 2027</h2>
      <p>
        The second Workshop on Mixed- and Adaptive-Precision Numerics for Scientific Computing
        (MxP4S) will be held in conjunction with the
        <a href="https://www.ipdps.org/">41st IEEE International Parallel &amp; Distributed Processing Symposium</a>
        in Seattle, Washington, USA. The exact workshop date and detailed schedule will be announced.
      </p>
      <p>
        We welcome researchers and practitioners working across numerical methods, scientific simulation,
        high-performance computing, computer architecture, and performance-portable software. The workshop
        is designed to connect advances in numerical accuracy with the rapidly changing capabilities of
        modern computing systems.
      </p>
    </div>

<aside class="mxp-program-card" aria-label="Workshop program highlights">
  <h3>Program highlights</h3>
  <ul>
    <li>Six selected-paper presentations</li>
    <li>Invited talks from distinguished researchers and practitioners</li>
    <li>Discussion across algorithms, systems, and scientific applications</li>
    <li>Opportunities for audience participation</li>
  </ul>
</aside>

  </section>

  <section class="mxp-section" aria-labelledby="why-heading">
    <h2 id="why-heading">Why mixed precision matters for science</h2>
    <p class="mxp-section-intro">
      On many emerging accelerators, low-precision arithmetic throughput is growing much faster than
      native double-precision throughput. Scientific computing can benefit from this shift—but only when
      performance, accuracy, stability, and reproducibility are treated as a single design problem.
    </p>

<div class="mxp-principles">
  <article class="mxp-principle">
    <h3>A growing performance opportunity</h3>
    <p>
      AI-driven hardware is delivering enormous capability in formats such as FP16, BF16, FP8, and INT8.
      Scientific applications need methods that can translate this capability into useful time-to-solution
      and energy-efficiency gains.
    </p>
  </article>

  <article class="mxp-principle">
    <h3>Accuracy cannot be an afterthought</h3>
    <p>
      First-principles simulations and numerical solvers often have strict requirements for stability and
      trustworthy results. Effective mixed-precision methods must expose, control, and—when necessary—recover
      the accuracy lost in lower-precision computation.
    </p>
  </article>

  <article class="mxp-principle">
    <h3>Precision should adapt to the problem</h3>
    <p>
      The goal is not simply to replace FP64 with one smaller format. It is to determine which precision is
      sufficient at each stage, when higher precision is essential, and how algorithms and systems can adapt
      as a computation evolves.
    </p>
  </article>
</div>

  </section>

  <section class="mxp-section mxp-callout" aria-labelledby="challenge-heading">
    <h2 id="challenge-heading">From hardware capability to dependable scientific results</h2>
    <p>
      Many scientific methods do not automatically benefit from the hardware advances created for neural-network
      training and inference. Unlocking that performance requires new numerical techniques, error analyses,
      programming models, software tools, benchmarks, and co-design across the full computing stack.
    </p>
    <p>
      <strong>MxP4S focuses on this bridge.</strong> We seek practical principles for using low precision where it
      helps, retaining high precision where it matters, and building adaptive approaches that deliver both high
      performance and reliable science on current and future HPC platforms.
    </p>
  </section>

  <nav class="mxp-quicklinks" aria-label="Workshop information">
    <a href="dates.html">Important dates</a>
    <a href="topics.html">Topics of interest</a>
    <a href="format.html">Format and schedule</a>
    <a href="organizers.html">Organizers</a>
  </nav>
</main>
