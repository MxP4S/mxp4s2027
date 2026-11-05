---
layout: default
title: Home
---

<link rel="stylesheet" href="{{ '/css/mxp4s.css' | relative_url }}">

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

⋮⋮⋮⋮



