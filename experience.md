---
layout: page
title: Experience
permalink: /experience/
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600&family=DM+Sans:wght@300;400;500&display=swap');

  body {
    font-family: 'DM Sans', sans-serif;
    color: #1a1a2e;
    background: #fdfdfc;
  }

  .section-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: 1.8rem;
    font-weight: 600;
    color: #1a1a2e;
    border-bottom: 2px solid #c9a96e;
    display: inline-block;
    padding-bottom: 4px;
    margin-bottom: 2rem;
  }

  .experience-container {
    max-width: 780px;
    margin: 0 auto;
    padding: 0 1rem;
  }

  .experience-entry {
    display: flex;
    gap: 2rem;
    align-items: flex-start;
    margin-bottom: 3rem;
    padding-bottom: 3rem;
    border-bottom: 1px solid #e5e5e5;
  }

  .experience-entry:last-child {
    border-bottom: none;
  }

  .company-logo {
    width: 90px;
    height: 90px;
    object-fit: contain;
    flex-shrink: 0;
    border-radius: 10px;
    border: 1px solid #e5e5e5;
    padding: 8px;
    background: #fff;
  }

  .experience-details {
    flex: 1;
  }

  .company-name {
    font-family: 'Cormorant Garamond', serif;
    font-size: 1.4rem;
    font-weight: 600;
    color: #1a1a2e;
    margin: 0 0 0.15rem;
  }

  .job-title {
    font-size: 1rem;
    font-weight: 500;
    color: #c9a96e;
    margin: 0 0 0.15rem;
  }

  .job-dates {
    font-size: 0.85rem;
    font-weight: 300;
    color: #888;
    margin: 0 0 0.75rem;
  }

  .job-details {
    font-size: 0.95rem;
    line-height: 1.7;
    color: #333;
    padding-left: 1rem;
    margin: 0;
  }

  .job-details li {
    margin-bottom: 0.3rem;
  }
</style>

<div class="experience-container">
  <h2 class="section-title">Work Experience</h2>

  <!-- ── Entry 1 ── -->
  <div class="experience-entry">
    <img class="company-logo"
         src="/files/boeing.png"
         alt="The Boeing Company" />
    <div class="experience-details">
      <p class="company-name">The Boeing Company</p>
      <p class="job-title">Structural Design Engineer</p>
      <p class="job-dates">September 2023 – Present</p>
      <ul class="job-details">
        <li>Add detail here</li>
        <li>Add detail here</li>
        <li>Add detail here</li>
      </ul>
    </div>
  </div>

  <!-- ── Entry 2 — duplicate and fill in for each additional company ── -->
  <div class="experience-entry">
    <img class="company-logo"
         src="/files/walsh.png"
         alt="The Walsh Group" />
    <div class="experience-details">
      <p class="company-name">The Walsh Group</p>
      <p class="job-title">Project Engineer Intern</p>
      <p class="job-dates">May - September 2022</p>
      <ul class="job-details">
        <li>Add detail here</li>
        <li>Add detail here</li>
        <li>Add detail here</li>
      </ul>
    </div>
  </div>

</div>
