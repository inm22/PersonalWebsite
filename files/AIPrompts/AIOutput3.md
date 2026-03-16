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
    margin-bottom: 3rem;
    padding-bottom: 3rem;
    border-bottom: 1px solid #e5e5e5;
  }

  .education-entry:last-child {
    border-bottom: none;
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

  .course-list {
    font-size: 0.9rem;
    color: #333;
    line-height: 1.8;
    padding-left: 1rem;
    margin: 0 0 1rem;
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
      <p class="degree-title">B.S. in Engineering</p>
      <p class="degree-dates">2020</p>

      <p class="subsection-title">Courses</p>
      <ul class="course-list">
        <li>CSE 101 — Introduction to Computer Science</li>
        <li>CSE 201 — Data Structures</li>
        <li>MATH 301 — Linear Algebra</li>
      </ul>

      <p class="subsection-title">Projects</p>
      <div class="project-entry">
        <p class="project-name">Project Name</p>
        <p class="project-tech">Technologies used: Python, JavaScript, etc.</p>
        <p class="project-desc">Brief description of what the project does and what you learned from it.</p>
      </div>

    </div>
  </div>

  <!-- ── Entry 2: University of Washington ── -->
  <div class="education-entry">
    <img class="school-logo"
         src="/assets/images/uw-logo.png"
         alt="University of Washington" />
    <div class="education-details">
      <p class="school-name">University of Washington</p>
      <p class="degree-title">M.S. in Computer Science</p>
      <p class="degree-dates">2025</p>

      <p class="subsection-title">Courses</p>
      <table class="courses-table">
        <thead>
          <tr>
            <th>Course</th>
            <th>Title</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>CSE 101</td><td>Introduction to Computer Science</td></tr>
          <tr><td>CSE 201</td><td>Data Structures</td></tr>
          <tr><td>MATH 301</td><td>Linear Algebra</td></tr>
        </tbody>
      </table>

      <p class="subsection-title">Projects</p>
      <div class="project-entry">
        <p class="project-name">Project Name</p>
        <p class="project-tech">Technologies used: Python, JavaScript, etc.</p>
        <p class="project-desc">Brief description of what the project does and what you learned from it.</p>
      </div>

    </div>
  </div>

</div>
