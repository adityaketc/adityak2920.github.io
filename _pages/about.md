---
permalink: /
excerpt: "About me"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="reveal" markdown="1">
<div class="profile-pic" role="img" aria-label="Aditya Kumar"></div>

<a class="status-pill" href="mailto:adityak2920@gmail.com">
  <span class="dot"></span> Open to opportunities · Bangalore, IN
</a>

# Aditya Kumar

<p class="subtitle">Software Engineer · Backend &amp; ML Infrastructure</p>

<div class="section">
    <div class="links">
        <a href="mailto:adityak2920@gmail.com">Email</a>
        <a href="https://linkedin.com/in/adityaketc">LinkedIn</a>
        <a href="https://github.com/adityaketc">GitHub</a>
    </div>
</div>
</div>

<nav class="section-nav reveal" aria-label="Page sections">
  <a href="#experience">experience</a>
  <a href="#skills">skills</a>
  <a href="#education">education</a>
  <a href="#writing">writing</a>
</nav>

<div class="reveal" markdown="1">

Software Engineer with <span class="metric">5 years</span> of experience building large-scale systems serving <span class="metric">3M+ users</span>. High-agency engineer with end-to-end ownership, from identifying opportunities and navigating stakeholder requirements to driving technical execution and deployment. Deep expertise in backend systems and Machine Learning infrastructure at scale.

<div class="now-card">
  <span class="now-label">Now</span>
  <span>Building the unified e-commerce stack at <strong>Kirana Club</strong> — OMS, logistics allocation, and a real-time ClickHouse pipeline doing <span class="metric">20M+ events/day</span>.</span>
</div>

</div>

<div class="reveal" id="experience" markdown="1">

## Experience

<div class="exp" markdown="1">
  <div class="exp-head">
    <span class="exp-company">Kirana Club</span>
    <span class="exp-role">Software Development Engineer</span>
    <span class="exp-when">Jan 2023 — Present</span>
  </div>

- Architected and led the development of a **unified e-commerce platform** (Go, Next.js) that orchestrates the complete order lifecycle for thousands of daily transactions, integrating a custom Order Management System (OMS) with automated logistics allocation and warehouse management for hundreds of sellers.
- Developed a centralized suite for SKU cataloging, automated pricing, and coupon management alongside a real-time analytics platform to track sales trends and supply chain bottlenecks, reducing order processing time from <span class="metric">hours to near-instantaneous</span> while significantly improving delivery success rates.
- Built an end-to-end customer support platform with designing the ticketing interface, agent workflow, and automated routing/prioritisation logic to manage thousands of daily inquiries. Streamlined processes across users, agents, and sellers to resolve exceptions, reducing TAT from <span class="metric">hours to minutes</span> and directly driving increased repeat orders.
- Engineered a high-performance spatial service using SQL spatial indexing and **H3 Grid Indexing** with bounding box optimizations, achieving <span class="metric">&lt;30ms latency</span> for reverse geocoding and <span class="metric">&lt;100ms p99</span> for "Nearby Users" queries.
- Designed and deployed a **self-managed ClickHouse** cluster to handle <span class="metric">20M+ daily events</span> for high-velocity impression data, optimizing data modeling and partitioning for high-throughput analytics.

</div>

<div class="exp" markdown="1">
  <div class="exp-head">
    <span class="exp-company">Retail Pulse</span>
    <span class="exp-role">Machine Learning Engineer</span>
    <span class="exp-when">Aug 2020 — Jan 2023</span>
  </div>

- Architected and deployed a multi-stage product recognition pipeline for Indian retail environments combining YOLO object detector (trained on 25k+ images), DML embeddings (trained on 5M+ images) with FAISS-based matching, quality filtering, and screen recapture detection. The pipeline achieved <span class="metric">92% product-level</span> and <span class="metric">85% SKU-level</span> accuracy across <span class="metric">25,000+ SKUs</span>, processing <span class="metric">10M+ images/month</span> in production.
- Developed a client-facing analytics platform visualizing real-time store execution metrics, enabling major FMCG clients to monitor shelf compliance and stock availability.

</div>

<div class="exp" markdown="1">
  <div class="exp-head">
    <span class="exp-company">Sparrosense</span>
    <span class="exp-role">Data Science Intern</span>
  </div>

- Developed self-supervised steel pouring classification in steel manufacturing process.

</div>

<div class="exp" markdown="1">
  <div class="exp-head">
    <span class="exp-company">Humonics Global</span>
    <span class="exp-role">Data Science Intern</span>
    <span class="exp-when">Jun 2019 — Jan 2020</span>
  </div>

- Built instance segmentation models for automated car insurance claims achieving 0.8 mAP and optimized the inference pipeline using TorchScript and C++ to achieve a <span class="metric">1.5x speedup</span> in production.

</div>

</div>

<div class="reveal" id="skills" markdown="1">

## Technical Skills

<div class="skills-grid">
  <div class="skill-group">
    <div class="skill-group__label">Languages</div>
    <div class="chips">
      <span class="chip">Golang</span>
      <span class="chip">Python</span>
      <span class="chip">TypeScript</span>
      <span class="chip">SQL</span>
      <span class="chip">C++</span>
    </div>
  </div>
  <div class="skill-group">
    <div class="skill-group__label">Backend &amp; Systems</div>
    <div class="chips">
      <span class="chip">FastAPI</span>
      <span class="chip">Node.js</span>
      <span class="chip">Next.js</span>
      <span class="chip">gRPC</span>
      <span class="chip">Docker</span>
      <span class="chip">RabbitMQ</span>
      <span class="chip">System Design</span>
    </div>
  </div>
  <div class="skill-group">
    <div class="skill-group__label">Data &amp; Storage</div>
    <div class="chips">
      <span class="chip">PostgreSQL</span>
      <span class="chip">Redis</span>
      <span class="chip">ClickHouse</span>
      <span class="chip">Elasticsearch</span>
      <span class="chip">Firebase</span>
      <span class="chip">H3</span>
    </div>
  </div>
  <div class="skill-group">
    <div class="skill-group__label">Machine Learning</div>
    <div class="chips">
      <span class="chip">PyTorch</span>
      <span class="chip">YOLO</span>
      <span class="chip">OpenCV</span>
      <span class="chip">Deep Metric Learning</span>
      <span class="chip">Model Serving</span>
    </div>
  </div>
</div>

</div>

<div class="reveal" id="education" markdown="1">

## Education
**Guru Gobind Singh Indraprastha University** · New Delhi, India
*B.Tech in Electronics and Communication Engineering* · 2017 — 2021

## Achievements
- **Open Source Contributor:** Contributed to OpenCV library with merged PRs.
- **Scholarship:** Recipient of Secure and Private AI Scholarship from Facebook and Udacity.

</div>

<div class="reveal" id="writing" markdown="1">

## Recent Writing
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

</div>

<div class="reveal colophon">
  <span>adityaketc / built with jekyll</span>
  <span>last updated · {{ site.time | date: "%b %Y" }}</span>
</div>
