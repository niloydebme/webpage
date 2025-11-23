---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

{% include base_path %}

<style>
  :root {
    --body-font-size: 14px;
    --heading-font-size: 16px;
    --muted: #444; /* Darker gray for better contrast */
    --accent: #0b66c3;
    --chip-bg: #f3f6fb;
    --line: #e6e6e6;
    --max-width: 920px;
  }

  .cv {
    max-width: var(--max-width);
    margin: 18px auto;
    font-family: "Helvetica Neue", Arial, sans-serif;
    color: #111;
    font-size: var(--body-font-size);
    line-height: 1.45;
    padding: 18px;
  }

  /* Header */
  .header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 12px;
    margin-bottom: 6px;
  }

  .name {
    font-size: 18px;
    font-weight: 700;
    margin: 0;
    color: #000; /* Ensure name is black for prominence */
  }

  .title {
    font-size: 13px;
    color: var(--muted);
    margin-top: 4px;
    font-style: italic;
  }

  .contact {
    text-align: right;
    font-size: 13px;
    color: var(--muted);
  }

  .contact a {
    color: var(--accent);
    text-decoration: none;
  }

  /* Section */
  .section {
    margin-top: 14px;
    padding-bottom: 14px;
    border-bottom: 1px solid var(--line);
  }

  .section h2 {
    display: flex;
    align-items: center;
    gap: 8px;
    font-size: var(--heading-font-size);
    margin: 0 0 10px 0;
  }

  .section h2 svg {
    width: 18px;
    height: 18px;
    opacity: 0.95;
  }

  /* Left / right entry */
  .entry {
    display: flex;
    justify-content: space-between;
    gap: 12px;
    align-items: flex-start;
    margin: 8px 0;
    margin-bottom: 5px;
  }

  .entry-left {
    width: 75%;
  }

  .entry-right {
    width: 25%;
    text-align: right;
    color: var(--muted);
    font-size: 13px;
  }

  .entry-right .location {
    display: block;
    margin-top: 6px;
    font-style: italic;
    font-size: 12.5px;
  }

  .institution {
    display: flex;
    gap: 8px;
    align-items: center;
  }

  .institution-logo {
    height: 28px;
    width: auto;
    display: inline-block;
    vertical-align: top;
  }

  .institution .inst-name {
    font-weight: 700;
    font-size: 14px;
    color: #000; /* Ensure institution name is black */
  }

  .institution .inst-sub {
    color: var(--accent);
    /* font-style: italic; */
    font-size: 13.2px;
    margin-top: 2px;
  }

  .entry-desc {
    margin-top: 6px;
    font-size: 13.4px;
    color: #111;
    margin-bottom: 25px;
  }

  /* chips */
  .chips {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 8px;
  }

  .chip {
    background: var(--chip-bg);
    padding: 6px 10px;
    border-radius: 14px;
    font-size: 13px;
    color: #333; /* Darken chip text for contrast */
  }

  /* inline dot lists */
  .inline-par {
    margin-top: 6px;
    font-size: 13.4px;
    color: #111;
  }

  .inline-par a {
    color: var(--accent);
    text-decoration: none;
  }

  .dot {
     font-size: 1.3em;   /* make it larger than surrounding text */
    font-weight: bold;  /* make it thicker */
    margin: 0 6px;      /* spacing before and after */
    line-height: 1;     /* keeps it aligned vertically */
    color: var(--muted);
  }


  /* compact lists */
  .compact-list {
    margin: 8px 0 0 0;
    padding-left: 14px;
  }

  .compact-list li {
    margin: 6px 0;
    font-size: 13.4px;
  }

  /* responsive */
  @media (max-width: 720px) {
    .entry {
      flex-direction: column;
    }

    .entry-left,
    .entry-right {
      width: 100%;
      text-align: left;
    }

    .entry-right {
      margin-top: 6px;
    }

    .contact {
      text-align: left;
      margin-top: 6px;
    }
  }

  @media print {
    .cv {
      padding: 0;
      margin: 0;
    }
  }

  /* small helper styles */
  .muted {
    color: var(--muted);
    font-size: 13px;
  }
</style>


<div class="cv">

  <div class="header">
    <div style="width:68%;">
      <p class="name">Niloy Deb</p>
      <p class="title">Mechanical Engineering Graduate</p>
      <p class="entry-desc" style="margin-top:8px;">
        <strong>Summary:</strong> My research interests lie at the intersection of fluid physics, computational methods, and data-driven science. Currently, I am focusing on integrating numerical methods and high-fidelity CFD with data-driven surrogates and differentiable physics to improve computational efficiency. 
      </p>
    </div>
    <div class="contact" style="width:32%;">
      <div style="font-weight:600;margin-bottom:6px;">Contact</div>
      <div>niloydeb@pmre.buet.ac.bd</div>
      <div style="margin-top:6px;">
        <a href="LINKEDIN_URL" target="_blank">LinkedIn</a> · <a href="https://orcid.org/0009-0006-4542-0895" target="_blank">ORCID</a>
      </div>
      <div style="margin-top:8px;">
        <a class="btn" href="https://www.dropbox.com/scl/fi/gyp2wdqfe81xtfvwh1cz9/Niloy_Deb_Curriculum_Vitae.pdf?rlkey=ts8ul83vt8lvj5c5tat3lb11x&st=drw83r12&dl=0" style="background:var(--accent); color:#fff; padding:6px 10px; border-radius:6px; text-decoration:none; font-size:13px;">📄 PDF</a>
      </div>
    </div>
  </div>

  <section class="section" id="education">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
        <path d="M3 7l9-4 9 4-9 4-9-4z"></path>
        <path d="M3 7v7a9 9 0 0 0 9 5 9 9 0 0 0 9-5V7"></path>
      </svg>
      Education
    </h2>
    <div class="entry">
      <div class="entry-left">
        <div class="institution">
          <img src="{{ site.baseurl }}/images/buet.png" alt="BUET logo" class="institution-logo">
          <div>
            <div class="inst-name">Bangladesh University of Engineering and Technology (BUET)</div>
            <div class="inst-sub">Bachelor of Science (B.Sc.) in Mechanical Engineering</div>
          </div>
        </div>
        <p class="entry-desc">
          <strong>Cumulative GPA: 3.94 / 4.00 </strong> · <strong>Rank: 6th out of 188 students (Top 3.2%)</strong><br>
          <!-- <strong>Thesis:</strong> Numerical Study of Natural and Mixed Convection in Enclosures with Porous Media of Varying Geometries. <br>
          <strong>Supervisor:</strong> Dr. Sumon Saha, Professor, Department of Mechanical Engineering, BUET -->
        </p>
      </div>
      <div class="entry-right">
        Mar 2018 – May 2023
        <span class="location">Dhaka, Bangladesh</span>
      </div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="institution">
          <img src="{{ site.baseurl }}/images/dhakacollege.png" alt="Dhaka College logo" class="institution-logo">
          <div>
            <div class="inst-name">Dhaka College</div>
            <div class="inst-sub">Higher Secondary Certificate (HSC) - Science </div>
          </div>
        </div>
        <p class="entry-desc">
          <strong>GPA: 5:00 / 5.00 (92% aggregate in Physics, Chemistry, and Higher Mathematics) </strong> 
        </p>
      </div>
      <div class="entry-right">
        Jun 2015 - Aug 2017
        <span class="location">Dhaka, Bangladesh</span>
      </div>
    </div>
  </section>

  <section class="section" id="interests">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round">
        <circle cx="12" cy="12" r="10"></circle>
        <path d="M12 6v6l4 2"></path>
      </svg>
      Interests
    </h2>
    <div class="chips" role="list">
      <span class="chip">Scientific Machine Learning (SciML)</span> 
      <span class="chip">Differentiable Physics</span>
      <span class="chip">Statistical Inference and Uncertainty Quantification</span>
      <span class="chip">Complex Systems Optimization</span>
      <span class="chip">Mathematical and Computational Modeling of Real-World Systems</span>
      <span class="chip">Numerical Methods (LBM, FEM, FDM, FVM, SEM) </span>
      <span class="chip">Computational Fluid Dynamics (CFD)</span>
      <span class="chip">Physics of Turbulence and Convection</span>
      <span class="chip">Chaotic Dynamical System and Control</span>
      <span class="chip">Multiphysics Fluid Flow</span>
      <span class="chip">Fluid Flow Through Porous and Subsurface Media</span>
    </div>
  </section>

<section class="section" id="professional">
 <h2 style="margin-bottom: 30px;">
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
    <rect x="2" y="3" width="20" height="14" rx="2" ry="2"></rect>
    <line x1="8" y1="21" x2="16" y2="21"></line>
    <line x1="12" y1="17" x2="12" y2="21"></line>
  </svg>
  Research Experience
</h2>

 <!-- Research Collaboration -->
  <div class="entry">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/ensym.png" alt="EnSyM logo" class="institution-logo" style="width:35px; height:29px;">
        <div>
          <div class="inst-name">Research Collaboration</div>
          <div class="inst-sub">Energy Systems and Modeling (EnSyM) Research Group</div>
        </div>
      </div>
    </div>
    <div class="entry-right">Jun 2025 – Present <span class="location">Dhaka, Bangladesh</span></div>
  </div>

  <div class="entry-desc" style="margin-top:8px; font-size: 12.5px;">
    <strong>Principal Investigator</strong>: Shaumik Rahman Ayon, Assistant Professor, Department of PMRE, BUET.  <br> <br>
    <strong>Topic: </strong>Thermodynamic optimization of a novel multistage direct expansion cycle for LNG cold energy recovery <br>
    <span style="display:block; margin-left:10px; text-indent:0;">
      &bull; Modeling and Optimization &nbsp;
      &bull; Differential Evolution (DE) Optimization &nbsp;
      &bull; LNG Cold Energy Recovery &nbsp;
      &bull; Thermodynamic Conversion Cycle &nbsp;
      &bull; Direct Expansion Cycle (DEC) &#9656; &#9656; <span style="color:blue;">[Manuscript in Preparation]</span>
    </span>
  </div>

  <!-- Research Associate -->
  <div class="entry" style="margin-top:12px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/hydrocarbon1.png" alt="Hydrocarbon Unit logo" class="institution-logo" >
        <div>
          <div class="inst-name">Research Associate</div>
          <div class="inst-sub">Funded Project, Hydrocarbon Unit Research Program 2023-24</div>
        </div>
      </div>
    </div>
    <div class="entry-right">Jan 2024 – Apr 2024 <span class="location">Bangladesh</span></div>
  </div>

  <div class="entry-desc" style="margin-top:8px; font-size: 12.5px;">
    <strong>Funding Agency</strong>: Bangladesh Hydrocarbon Unit, Ministry of Power, Energy and Mineral Resources, Bangladesh. <br>
    <strong>Principal Investigator</strong>: Dr. Mohammed Mahbubur Rahman, Professor, Department of PMRE, BUET. <br> <br>
    <strong>Theme: </strong> A Study of the Reservoir Fluid Properties and Phase Behavior of Titas Gas Field, Bangladesh <br>
    <span style="display:block; margin-left:10px; text-indent:0;">
      &bull; Reservoir Fluid Properties &nbsp;
      &bull; Reservoir Fluid Phase Behavior &nbsp;
      &bull; Spatio-temporal Analysis &nbsp;
      &bull; Reserve Estimation &nbsp;
      &bull; Field production history &#9656; &#9656; <span style="color:blue;">[Completed: Project report and presentation; Paper preprint available]</span>
    </span>
  </div>

  <!-- Undergraduate Thesis -->
  <div class="entry" style="margin-top:12px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/buet.png" alt="BUET logo" class="institution-logo">
        <div>
          <div class="inst-name">Undergraduate Thesis</div>
          <div class="inst-sub">Department of Mechanical Engineering, BUET</div>
        </div>
      </div>
    </div>
    <div class="entry-right">May 2022 – May 2023 <span class="location">Dhaka, Bangladesh</span></div>
  </div>

  <div class="entry-desc" style="margin-top:8px; font-size: 12.5px;">
    <strong>Topic</strong>: Numerical Study of Natural and Mixed Convection in Enclosures with Porous Media of Varying Geometries. <br>
    <strong>Supervisor</strong>: Dr. Sumon Saha, Professor, Department of Mechanical Engineering, BUET. <br>
    <span style="display:block; margin-left:10px; text-indent:0;">
      &bull; Computational Methods &nbsp;
      &bull; FEM Modeling &nbsp;
      &bull; Convection Heat Transfer &nbsp;
      &bull; Porous Media Flow &nbsp;
      &bull; Solution of Benchmark CFD Problems   &#9656; &#9656; <span style="color:blue;">[Thesis Book; Publications]</span>
    </span>
  </div>
</section>

<section class="section" id="professional" >
  <h2 style="margin-bottom: 30px;">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
      <rect x="2" y="7" width="20" height="14" rx="2"></rect>
      <path d="M16 3h0a2 2 0 0 1 2 2v2H6V5a2 2 0 0 1 2-2h0"></path>
    </svg>
    Professional Experience
  </h2>

  <div class="entry">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/buet.png" alt="BUET logo" class="institution-logo">
        <div>
          <div class="inst-name">Lecturer, <span style="font-weight: normal;">Dept. of Petroleum and Mineral Resources Engineering </span></div>
          <div class="inst-sub">Bangladesh University of Engineering and Technology</div>
        </div>
      </div>
    </div>
    <div class="entry-right">
      Dec 2023 – Present
      <span class="location">Dhaka, Bangladesh</span>
    </div>
    
  </div>

 <div class="entry-desc" style="margin-top:8px; font-size: 12.5px;">
  <p style="margin-bottom: 5px;">
        <strong> Instructed Undergraduate Courses:</strong> &#9656; PMRE 411 · Reservoir Engineering [July 2025 Semester] &#9656; PMRE 413 · Natural Gas Engineering [July 2023 Semester] (≈50 students each)
      </p>
 </div>


  <div class="entry" style="margin-top:8px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/cfdht.png" alt="Group logo" class="institution-logo" style="width:30px; height:22px;">
        <div>
          <div class="inst-name">Research Assistant</div>
          <div class="inst-sub"> Computational Fluid Dynamics and Heat Transfer (CFDHT) Research Group </div>
        </div>
      </div>
      
</div>
    <div class="entry-right">Jun 2023 – Dec 2023 <span class="location">Dhaka, Bangladesh</span></div>
  </div>

   <div class="entry-desc" style="margin-top:8px; font-size: 12.5px;"> 
    <strong>Principal Investigator</strong>: Dr. Sumon Saha , Professor, Department of Mechanical Engineering, BUET.
    <ul style="list-style-type: none; padding-left: 0px;">
      <li style="position: relative; margin-bottom: 2px;">
        Research includes: Numerical Methods, Turbulence Modeling, CFD-based Control of Convection, Multiphysics Flow,
Multiphase Flow, and Flow Through Porous Media
      </li>
      <li style="position: relative; margin-bottom: 2px;">
        <span style="text-decoration: underline;">Drafted a proposal </span> for the Research Innovation Center for Science and Engineering (RISE) <span style="text-decoration: underline;">internal research grant </span>, BUET. <br>
<strong>Theme </strong>: Visualization, Optimization, and Performance Analysis of Two-Phase Fluid Flow in a Plate-Fin Compact Heat
Exchanger.
      </li>
    </ul>
 
 </div>



  <!-- <div class="entry" style="margin-top:12px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/buet.png" alt="BUET logo" class="institution-logo">
        <div>
          <div class="inst-name"> Co-instructor, <span style="font-weight: normal;">Short Course</span> </div>
          <div class="inst-sub">Directorate of Continuing Education, BUET</div>
        </div>
      </div>
      <div class="entry-desc">Short course: COMSOL Multiphysics Simulation of Thermo-fluidic Problems (Basic Level) · 2-day (12 hours) workshop · Instructor: Dr. Sumon Saha</div>
    </div>
    <div class="entry-right">Dec 2023 <span class="location">Dhaka, Bangladesh</span></div>
  </div> -->


  <div class="entry" style="margin-top:12px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/powertek.jpeg" alt="Powertek logo" class="institution-logo">
        <div>
          <div class="inst-name">Industrial Trainee</div>
          <div class="inst-sub"> Haripur 360 MW Combined Cycle Power Plant (CCPP) </div>
        </div>
      </div>
    </div>
    <div class="entry-right">Nov - Dec 2022 (3 weeks) <span class="location">Dhaka, Bangladesh</span></div>
  </div>
  <div class="entry-desc">
      Hands-on exposure to power generation in a CCPP, plant unit operations (fuel gas compressor, heat recovery steam
generator, steam turbine, gas turbine, water treatments), plant maintenance, and process control.
</div>
</section>

  <section class="section" id="publications">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round">
        <path d="M19 21H5a2 2 0 0 1-2-2V7"></path>
        <path d="M17 3H7a2 2 0 0 0-2 2v12"></path>
      </svg>
      Publications
    </h2>

    <ul style="margin:2px 0 0 2px;">
      {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
      {% endfor %}
    </ul>
  </section>



  <section class="section" id="projects">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round">
        <path d="M3 7h18"></path>
        <path d="M3 11h18"></path>
        <path d="M3 15h18"></path>
      </svg>
      Technical Projects
    </h2>

   <div class="entry" style="margin-top:6px; margin-left:15px;">
      <div class="entry-left">
        <div class="inst-name"> &#9656; Design of a Counter-Flow Shell & Helical Coil Tube Heat Exchanger (SHCTHX)</div>
        <div class="inst-sub" style="font-size: 13px;"><span style = "color: var(--accent);"> ME-310: Thermo-fluid System Design & Practice<br>
         Supervisor: Dr. AKM Monjur Morshed, Professor, Dept. of ME, BUET  </span> </div>
        <div class="entry-desc">CAD design · Thermo-hydraulic calculations · CFD simulation with flow & thermal field visualization · Structural integrity test ·  Prototype design. <a href="https://www.researchgate.net/publication/373337988_Design_of_a_counter-flow_shell_and_helical_coil_tube_heat_exchanger_SHCTHX">[Project Report]</a></div> 
      </div>
      <div class="entry-right">Jan - Feb 2022</div>
    </div>

  <div class="entry" style="margin-top:6px; margin-left:15px;">
      <div class="entry-left">
        <div class="inst-name">&#9656; Self-Stabilizing, Computer-Controlled Laser Turret</div>
        <div class="inst-sub" style="font-size: 13px;"><span style = "color: var(--accent);"> ME-366: Electromechanical System Design & Practice<br>
         Supervisor: Dr. Aman Uddin, Associate Professor, Dept. of ME, BUET </span></div>
        <div class="entry-desc">CAD design · Arduino programming · sensor integration & feedback control · hardware-software integration for stabilization and precision. <a href="https://www.researchgate.net/publication/373336950_Project_report_titled_'Self-stabilizing_computer-controlled_laser_turret'_for_Electromechanical_System_Design_and_Practice">[Project Report]</a></div> 
      </div>
      <div class="entry-right">Apr - Jun 2021</div>
    </div>
  </section>

  <section class="section" id="research">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
        <path d="M3 7h18"></path>
        <path d="M12 3v18"></path>
      </svg>
      Presentations and Talks
    </h2>

<ul style="list-style-type: disc; padding-left: 20px; margin: 0; font-size: 13px;">
  <li style="position: relative; padding-right: 100px;">
    MHD Natural Convective Flow with Internal Heat Generation and Joule Heating inside a Two Layer Discretely Heated Chamber Partially Filled with Porous Medium [Technical session] — 
    <i>presented at the 14th International Conference on Mechanical Engineering (ICME 2023), Dhaka, Bangladesh</i>
    <span style="position: absolute; right: 0;">[Dec 2023]</span>
  </li>

  <li style="position: relative; padding-right: 100px;">
    How to Review Literature [Workshop] — 
    <i>Technical writing session organized by the Computational Fluid Dynamics and Heat Transfer (CFDHT) Research Group</i>
    <span style="position: absolute; right: 0;">[Aug 2023]</span>
  </li>

  <li style="position: relative; padding-right: 100px;">
    Introduction to Porous Media and Related Mathematical Modeling for Fluid Flow and Heat Transfer [Workshop] — 
    <i>Computational Fluid Dynamics simulation using COMSOL Multiphysics software, workshop organized by REVA University, Bengaluru, India</i>
    <span style="position: absolute; right: 0;">[Sep 2023]</span>
  </li>

  <li style="position: relative; padding-right: 100px;">
    Multi-segment Numerical Integration Method for Solution of Boundary Value Problems (Linear and Non-linear ODEs) [Tutorial] — 
    <i>Tutorial session on non-conventional numerical techniques for solving boundary value problems</i>
    <span style="position: absolute; right: 0;">[May 2024]</span>
  </li>
</ul>




 

  </section>

  <section class="section" id="skills">
       <h2>
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="12" cy="12" r="3"></circle>
    <path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 1 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V22a2 2 0 1 1-4 0v-.09a1.65 1.65 0 0 0-1-1.51 1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 1 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H2a2 2 0 1 1 0-4h.09a1.65 1.65 0 0 0 1.51-1 1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06c.48.48 1.17.64 1.82.33H8a1.65 1.65 0 0 0 1-1.51V2a2 2 0 1 1 4 0v.09c0 .66.37 1.26 1 1.51.65.31 1.34.15 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9c0 .66.37 1.26 1 1.51.65.31 1.34.15 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06c-.48.48-.64 1.17-.33 1.82V15z"></path>
  </svg>
  Technical Skills
</h2>
      <div class="entry-desc" style="margin-bottom:6px; color: var(--accent);">
    <strong>Highlights:</strong> Scientific Writing · Exploratory Data Analysis · Quantitative Research
  </div>
<div class="entry-desc" style="margin-top:8px; font-size: 12.5px;">
  <ul class="compact-list" style="margin:0; padding-left:20px; line-height:1.1; list-style-position:outside;">
    <li><strong>Programming Languages:</strong> Python, MATLAB, C</li>
    <li><strong>Documentation / Scripting:</strong> LaTeX, MS Office, Markdown, HTML</li>
    <li><strong>Visualization:</strong> Tecplot 360, WebPlotDigitizer, Desmos, Python (Matplotlib, Plotly, Seaborn)</li>
    <li><strong>CAD / Drawing:</strong> AutoCAD, SolidWorks, Proteus, Draw.io, Canva, Illustrator, Photoshop, LaTeX-TikZ, Python (OpenCV, Pillow, scikit-image)</li>
    <li><strong>CFD Tools:</strong> COMSOL Multiphysics, Ansys Fluent</li>
    <li><strong>Reservoir Simulation:</strong> Kappa Workstation (Rubis, Saphir)</li>
    <li><strong>ML / DL / Statistics:</strong> Python (scikit-learn, TensorFlow, PyTorch, JAX, SciPy, PyMC3/4)</li>
    <li><strong>Exploratory Data Analysis:</strong> Python (Pandas, NumPy, SciPy, Matplotlib, Plotly, Seaborn)</li>
  </ul>
</div>
  </section>

  <section class="section" id="awards">
    <h2>
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
    <path d="M8 21h8"></path>
    <path d="M12 17v4"></path>
    <path d="M7 4h10v4a5 5 0 0 1-10 0V4z"></path>
    <path d="M5 4h2v4a7 7 0 0 0 14 0V4h2"></path>
  </svg>
  Awards and Honors
</h2>
<ul style="list-style-type: disc; padding-left: 20px; margin: 0; font-size: 12.5px;">
  <li style="position: relative; padding-right: 120px;">
    <strong>Dr. Muhammad Harunur Rashid Best Paper Award:</strong> Best Paper Award at the 14th International Conference on Mechanical Engineering, Dhaka, Bangladesh
    <span style="position: absolute; right: 0;">[ICME 2023]</span>
  </li>
  
  <li style="position: relative; padding-right: 120px;">
    <strong>University Merit Scholarship (BUET):</strong> Awarded for academic excellence in undergraduate studies
    <span style="position: absolute; right: 0;">[2018–2023]</span>
  </li>
  
  <li style="position: relative; padding-right: 120px;">
    <strong>Dean’s List Award (Department of Mechanical Engineering, BUET):</strong> Awarded for academic excellence in all academic levels (I–IV) of undergraduate studies
    <span style="position: absolute; right: 0;">[2018–2023]</span>
  </li>
</ul>
  </section>

<section class="section" id="involvements">
  <h2>
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
      <circle cx="12" cy="12" r="10"></circle>
      <path d="M10 8l4 4-4 4"></path>
    </svg>
    Involvements
  </h2>

 <ul style="list-style-type: disc; padding-left: 20px; margin: 0; font-size: 12.5px;">
  <li style="position: relative; padding-right: 120px;">
    <strong>Co-Instructor:</strong> Short Course on COMSOL Multiphysics Simulation of Thermo-fluidic Problems, Directorate of Continuing Education (DCE), Bangladesh University of Engineering and Technology (BUET), Dhaka, Bangladesh
    <span style="position: absolute; right: 0;">[Dec 2023]</span>
  </li>
  
  <li style="position: relative; padding-right: 120px;">
    <strong>Reviewer:</strong> <i>Scientific Reports</i>; <i>Numerical Heat Transfer, Part A: Applications</i>
    <span style="position: absolute; right: 0;">[2023 – Present]</span>
  </li>
  
  <li style="position: relative; padding-right: 120px;">
    <strong>Question Setter:</strong> Mechanical Olympiad organized by the Department of Mechanical Engineering, BUET
    <span style="position: absolute; right: 0;">[Mecha Fest 2023]</span>
  </li>
</ul>

</section>



  <section class="section" id="coursework">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
        <rect x="3" y="4" width="18" height="6" rx="2"></rect>
        <path d="M7 20h10"></path>
      </svg>
      Relevant Coursework
    </h2> 
    <div class="inline-par">
      <strong>Advanced / Graduate & Self-Learning:</strong> (listed partially)
      Advanced Numerical Analysis (Dept. of ME, BUET) <span class="dot">·</span>  Advanced Thermodynamics (classical and statistical) (Dept. of ME, BUET) <span class="dot">·</span> Boiling & Condensation Heat Transfer (Dept. of ME, BUET) <span class="dot">·</span> Reservoir Engineering (Dept. of PMRE, BUET) <span class="dot">·</span> Well Testing Analysis (Dept. of PMRE, BUET) <span class="dot">·</span> Non-linear Dynamics & Chaos (S. Strogatz, Online) <span class="dot">·</span> Non-linear Systems (J. Slotine, MOCW) <span class="dot">·</span> Control Bootcamp (S. L. Brunton, Online) <span class="dot">·</span> Global Warming - Science & Modeling (D. Archer, edX) <span class="dot">·</span> Understanding Rheology (F. Morrison, Online) <span class="dot">·</span> Flow in Porous Media (M. Blunt, Online) <span class="dot">·</span> Physics of Turbulence (M. K. Verma, IITK-NPTEL) <span class="dot">·</span> Advanced Fluid Mechanics (S. Chakraborty, IITKGP-NPTEL) <span class="dot">·</span> AI Principles & Techniques (Stanford Online) <span class="dot">·</span> Deep Learning in Scientific Computing (ETH Zurich) <span class="dot">·</span> Data Analytics and Geostatistics (M. J. Pyrcz, Online) <span class="dot">·</span> Matrix Calculus for Machine Learning and Beyond (A. Edelman & S. G. Johnson, MOCW) <span class="dot">·</span> Matrix, Numerical and Optimization Methods in Science and Engineering (K. Cassel, Online) <span class="dot">·</span> Applied Time Series Analysis (A. K. Tangirala, IITM-NPTEL) <span class="dot">·</span> Probabilistic System Analysis and Applied Probability (J. Tsitsiklis, MOCW) <span class="dot">·</span> Data-Driven Science and Engineering (S. L. Brunton, Online) <span class="dot">·</span> Random Physics Lectures (classical, Statistical, Quantum Mechanics, Modern Physics - Special and General Relativity by L. Susskind, Online )- did just for fun.  
    </div>

  <div class="inline-par" style="margin-top:8px;">
      <strong>Undergraduate / Core:</strong>
      Instrumentation and Measurement <span class="dot">·</span> Electro-Mechanical System Design (Project) <span class="dot">·</span> Noise & Vibration <span class="dot">·</span> Control Engineering <span class="dot">·</span> Engineering Mechanics (I & II) <span class="dot">·</span> Mechanics of Solids <span class="dot">·</span> Thermodynamics (Basic) <span class="dot">·</span> Advanced Thermodynamics (Classical and Statistical) <span class="dot">·</span> Fluid Mechanics (I & II) <span class="dot">·</span> Heat Transfer <span class="dot">·</span> Heat Transfer Equipment Design <span class="dot">·</span> Thermo Fluid System Design (Project) <span class="dot">·</span> Combustion <span class="dot">·</span> Refrigeration and Building Mechanical System <span class="dot">·</span> Numerical Analysis <span class="dot">·</span> Computer Programming 
    </div>
  </section>

  <section class="section" id="training">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round">
        <path d="M21 8V7a2 2 0 0 0-2-2h-3"></path>
        <path d="M3 8v9a2 2 0 0 0 2 2h3"></path>
      </svg>
      Training & MOOC Completion
    </h2>
    <p class="inline-par">
      Research Skill Development · DCE, BUET · <a href="https://buetedu-my.sharepoint.com/:b:/g/personal/niloydeb_pmre_buet_ac_bd/EXOfHmAlqktAtOIqCe3qqqwBMHvi-7VKch1JsfkeN4RUmw?e=1pHMCX">Certificate</a>
      <span class="dot">·</span>
      Quantitative Method · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/KUNNEK67EW6E">Certificate</a>
      <span class="dot">·</span>
      Evaluating Problems · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/QWF5B9NVSPDD">Certificate</a>
      <span class="dot">·</span>
      Welcome to Game Theory · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/3V72R3HBVLJS">Certificate</a>
      <span class="dot">·</span>
      Intro to Data Analysis using Excel · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/8SC5YX5ZGN9K">Certificate</a>
      <span class="dot">·</span>
      Introduction to Programming with MATLAB · Coursera · <a href="https://www.coursera.org/account/accomplishments/verify/TCQNM5G5Y7FP">Certificate</a>
      <span class="dot">·</span>
      Python for Everybody (Specialization) · Coursera · <a href="https://www.coursera.org/account/accomplishments/specialization/VPRVZ5MZ43HX">Certificate</a>
      <span class="dot">·</span>
      ELEN7070x: Research Methods · EdX · <a href="https://courses.edx.org/certificates/9abb933553e644ed9f41ff096fc60a72">Certificate</a>
      <span class="dot">·</span>
      16.00x: Introduction to Aerospace Engineering · EdX · <a href="https://courses.edx.org/certificates/ec2238cfcac64bbebddb7263c82ce30c">Certificate</a>
      <span class="dot">·</span>
      Image Processing Onramp · MathWorks · <a href="https://matlabacademy.mathworks.com/progress/share/certificate.html?id=6c90b29d-19c4-4b51-9069-fa743ed4b1f7&">Certificate</a>
      <span class="dot">·</span>
      Solving ODEs with MATLAB · MathWorks · <a href="https://matlabacademy.mathworks.com/progress/share/certificate.html?id=c390f6ca-c82a-4189-83ef-c67ccb7cc0dc&">Certificate</a>
    </p>
  </section>
</div>