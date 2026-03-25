---
layout: page
title: Education
permalink: /education/
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600&family=DM+Sans:wght@300;400;500&display=swap');

  h1.post-title, .page-heading {
    display: none;
  }

  body {
    font-family: 'DM Sans', sans-serif;
    color: #1a1a2e;
    background: #fdfdfc;
  }

  .post-content, .page-content {
    padding-top: 0 !important;
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

  .education-container {
    max-width: 780px;
    margin: 0 auto;
    padding: 0 1rem;
  }

  .education-entry {
    display: flex;
    gap: 2rem;
    align-items: flex-start;
    margin-bottom: 3rem;
    padding-bottom: 3rem;
    border-bottom: 1px solid #e5e5e5;
  }

  .education-entry:last-child {
    border-bottom: none;
  }

  .school-logo {
    width: 90px;
    height: 90px;
    object-fit: contain;
    flex-shrink: 0;
    border-radius: 10px;
    border: 1px solid #e5e5e5;
    padding: 8px;
    background: #fff;
  }

  .education-details {
    flex: 1;
  }

  .school-name {
    font-family: 'Cormorant Garamond', serif;
    font-size: 1.4rem;
    font-weight: 600;
    color: #1a1a2e;
    margin: 0 0 0.15rem;
  }

  .degree-title {
    font-size: 1rem;
    font-weight: 500;
    color: #c9a96e;
    margin: 0 0 0.15rem;
  }

  .degree-dates {
    font-size: 0.85rem;
    font-weight: 300;
    color: #888;
    margin: 0 0 1rem;
  }

  .subsection-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: 1.1rem;
    font-weight: 600;
    color: #1a1a2e;
    margin: 1rem 0 0.5rem;
  }

  .courses-table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.9rem;
    margin-bottom: 1rem;
  }

  .courses-table th {
    text-align: left;
    font-weight: 500;
    color: #888;
    border-bottom: 1px solid #e5e5e5;
    padding: 0.4rem 0.75rem 0.4rem 0;
  }

  .courses-table td {
    padding: 0.4rem 0.75rem 0.4rem 0;
    color: #333;
    border-bottom: 1px solid #f0f0f0;
  }

  .courses-table tr:last-child td {
    border-bottom: none;
  }

  .project-entry {
    margin-bottom: 0.75rem;
  }

  .project-name {
    font-size: 0.95rem;
    font-weight: 500;
    color: #1a1a2e;
    margin: 0 0 0.1rem;
  }

  .project-tech {
    font-size: 0.85rem;
    font-style: italic;
    color: #888;
    margin: 0 0 0.2rem;
  }

  .project-desc {
    font-size: 0.9rem;
    color: #555;
    line-height: 1.6;
    margin: 0;
  }
</style>

<div class="education-container">
  <h2 class="section-title">Education</h2>

<!-- ── Entry 1: Columbia University ── -->
  <div class="education-entry">
    <div class="education-details">
      <p class="school-name">Columbia University</p>
      <p class="degree-title">B.S. in Mechanical Engineering</p>
      <p class="degree-dates">2023</p>
      <p class="project-desc"><strong>Minor:</strong> Hispanic Studies</p>
      <p class="project-desc"><strong>GPA:</strong> 3.82</p>

      <p class="subsection-title">Courses</p>
      <p class="project-desc"> Intro to Computer Programming in Java, Foundations of Data Science, Intro to Electrical Engineering, 
Computer Graphics & Design, Control Systems, Human Centered Design, Robotics Studio</p>
    </div>
  </div>

  <!-- ── Entry 2: University of Washington ── -->
  <div class="education-entry">
    <div class="education-details">
      <p class="school-name">University of Washington</p>
      <p class="degree-title">M.S. in Computer Science</p>
      <p class="degree-dates">2027 (Expected)</p>
      <p class="project-desc"><strong>GPA:</strong> 3.9</p>

      <p class="subsection-title">Courses</p>
      <p class="project-desc">Evaluating Software Design, Network Systems,  Computer-Aided Reasoning for Software</p>
    </div>
  </div>

</div>
