---
layout: page
permalink: /experience/
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600&family=DM+Sans:wght@300;400;500&display=swap');

  body {
    font-family: 'DM Sans', sans-serif;
    color: #1a1a2e;
    background: #fdfdfc;
  }

    .experience-container {
    margin-top: 0;
    padding-top: 0;
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
        <li>Utilize Python to create assitive software tools for design and analysis engineers, saving thousands of manual labor hours</li>
        <li>Received a Boeing Meritorious Invention Disclosure Award for Generative Design Approach Patent</li>
        <li>Lead team code review meetings, inviting subject matter experts to enhance code quality and share common practices</li>
        <li>Create a library of modular functions to be utilized for design software tools in CATIA and 3DExperience </li>
        <li>Mentor colleagues in programmatic design, providing instruction on essential APIs and libraries to improve their efficiency</li>
        <li>Create software tools with intuitive graphic user interfaces (GUIs) for a customer focused end-product</li>
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
      <p class="job-dates">June - August 2022</p>
      <ul class="job-details">
        <li>Implemented new practices to reduce construction waste and pollution as the LEED Green Associate on the team </li>
        <li>Designed engineering and structural drawings and tracked construction progress with Bluebeam Revu</li>
      </ul>
    </div>
  </div>

  <!-- ── Entry 3 — duplicate and fill in for each additional company ── -->
  <div class="experience-entry">
    <img class="company-logo"
         src="/files/CU.jpg"
         alt="Columbia University" />
    <div class="experience-details">
      <p class="company-name">Columbia University</p>
      <p class="job-title">Research Assistant</p>
      <p class="job-dates">May - September 2021</p>
      <ul class="job-details">
        <li>Developed Python code to track a tennis ball in match play through video and sound</li>
        <li>Performed over 10,000 trials of tennis ball bounces and coded a Python algorithm to sort the data</li>
        <li>Programmed a camera to follow and track a moving tennis ball utilizing Raspberry Pi and OpenCV Library</li>
      </ul>
    </div>
  </div>

</div>
