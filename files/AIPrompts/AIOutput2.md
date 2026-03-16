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
         src="/assets/images/company1-logo.png"
         alt="My Company" />
    <div class="experience-details">
      <p class="company-name">My Company</p>
      <p class="job-title">Design Engineer</p>
      <p class="job-dates">2020 – Present</p>
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
         src="/assets/images/company2-logo.png"
         alt="Company 2" />
    <div class="experience-details">
      <p class="company-name">Company 2</p>
      <p class="job-title">Job Title</p>
      <p class="job-dates">2018 – 2020</p>
      <ul class="job-details">
        <li>Add detail here</li>
        <li>Add detail here</li>
        <li>Add detail here</li>
      </ul>
    </div>
  </div>

</div>
