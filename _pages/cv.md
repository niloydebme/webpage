---
layout: archive
title: "Resume"
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
        <strong>Summary:</strong> An aspiring mechanical engineering graduate focused on data-driven science, scientific machine learning (SciML), statistical inference, computational methods, and applied mathematics. Research interests include chaotic dynamical systems, turbulence, fluid flow through porous and subsurface media, and fluid flow in multiphysics environments.
      </p>
    </div>
    <div class="contact" style="width:32%;">
      <div style="font-weight:600;margin-bottom:6px;">Contact</div>
      <div>niloydeb@pmre.buet.ac.bd</div>
      <div style="margin-top:6px;">
        <a href="LINKEDIN_URL" target="_blank">LinkedIn</a> · <a href="https://orcid.org/0009-0006-4542-0895" target="_blank">ORCID</a>
      </div>
      <div style="margin-top:8px;">
        <a class="btn" href="link-to-cv.pdf" style="background:var(--accent); color:#fff; padding:6px 10px; border-radius:6px; text-decoration:none; font-size:13px;">📄 Download PDF</a>
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
          <strong>Cumulative GPA:</strong> 3.94 / 4.00 · <strong>Rank:</strong> 6 / 188 (Top 3% of the class)<br>
          <strong>Thesis:</strong> Numerical Study of Natural and Mixed Convection in Enclosures with Porous Media of Varying Geometries. <br>
          <strong>Supervisor:</strong> Dr. Sumon Saha, Professor, Department of Mechanical Engineering, BUET
        </p>
      </div>
      <div class="entry-right">
        March 2018 – May 2023
        <span class="location">Dhaka, Bangladesh</span>
      </div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="institution">
          <img src="{{ site.baseurl }}/images/dhakacollege.png" alt="Dhaka College logo" class="institution-logo">
          <div>
            <div class="inst-name">Dhaka College, Dhaka</div>
            <div class="inst-sub">Higher Secondary Certificate (HSC) - Science </div>
          </div>
        </div>
        <p class="entry-desc">
          <strong>GPA:</strong> 5:00 / 5.00 (92% aggregate in Physics, Chemistry, and Higher Mathematics)
        </p>
      </div>
      <div class="entry-right">
        June 2015 - August 2017
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
      <span class="chip">Data-Driven Science</span>
      <span class="chip">Statistical Modeling and Inference</span>
      <span class="chip">Complex Systems Optimization</span>
      <span class="chip">Mathematical and Computational Modeling of Real-World Systems</span>
      <span class="chip">Scientific Machine Learning (SciML)</span> 
      <span class="chip">Numerical Methods - LBM, FEM, FDM, FVM, SEM</span>
      <span class="chip">Computational Fluid Dynamics (CFD) and Heat Transfer</span>
      <span class="chip">Physics of Turbulence and Convection</span>
      <span class="chip">Chaotic Dynamical System and Control</span>
      <span class="chip">Multiphysics Fluid Flow</span>
      <span class="chip">Fluid Flow Through Porous and Subsurface Media</span>
    </div>
  </section>

<section class="section" id="professional">
 <h2>
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
    <rect x="2" y="3" width="20" height="14" rx="2" ry="2"></rect>
    <line x1="8" y1="21" x2="16" y2="21"></line>
    <line x1="12" y1="17" x2="12" y2="21"></line>
  </svg>
  Research Experience
</h2>

  <div class="entry" style="margin-top:8px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/cfdht.png" alt="Group logo" class="institution-logo">
        <div>
          <div class="inst-name">Research Assistant, Computational Fluid Dynamics and Heat Transfer (CFDHT) Research Group</div>
          <div class="inst-sub"> Department of Mechanical Engineering, BUET. <span style="text-decoration: underline;">Mentor: Dr. Sumon Saha</span></div>
        </div>
      </div>
      
</div>
    <div class="entry-right">Jun 2023 – Dec 2023 <span class="location">Dhaka, Bangladesh</span></div>
  </div>
 <div class="entry-desc" style="margin-top:8px; font-size: 12.5px;">
    <p style="margin-bottom: 5px;">  I was actively involved in several <span style="text-decoration: underline;">numerical modeling and simulation </span> studies. Some of my contribution to the group include:</p>
    <ul style="list-style-type: none; padding-left: 20px;">
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
        Studied the robustness of linear controllers (P, PI, PID) in mixed convection cases from a <span style="text-decoration: underline;">CFD perspective</span>.
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
         Revisited the formulation and numerical calculations of the <span style="text-decoration: underline;">Nusselt Number (Nu)</span> subject to various thermal boundary conditions.
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
        Worked on numerical solutions of natural and mixed convection heat transfer involving <span style="text-decoration: underline;">porous media</span>, including the effects of <span style="text-decoration: underline;">magnetohydrodynamics, Joule heating, and internal heat generation</span>.
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
        Validated several benchmark simulations, including <span style="text-decoration: underline;">RANS turbulence, multiphase flow, and phase transition analyses</span>.
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
        Published multiple papers as the lead author in international peer-reviewed journals.
              </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
        <span style="text-decoration: underline;">Presented group work as the lead author at an international conference </span> (14th International Conference on Mechanical Engineering) hosted by the Department of Mechanical Engineering, BUET, Dhaka, Bangladesh.
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
        <span style="text-decoration: underline;">I was also the lead author </span> of another paper presented at the 17th Asian Congress of Fluid Mechanics in Beijing, China.
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
       <span style="text-decoration: underline;"> Mentored undergraduate students </span> in their CFD and heat transfer-related theses.
      </li>
    </ul>
  </div>

  <div class="entry" style="margin-top:12px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/cfdht.png" alt="Group logo" class="institution-logo">
        <div>
          <div class="inst-name">Undergraduate Researcher, Computational Fluid Dynamics and Heat Transfer (CFDHT) Research Group</div>
          <div class="inst-sub"> Department of Mechanical Engineering, BUET. <span style="text-decoration: underline;">Mentor: Dr. Sumon Saha</span></div>
        </div>
      </div>
      
</div>
    <div class="entry-right">April 2021 – May 2023 <span class="location">Dhaka, Bangladesh</span></div>
  </div>

  <div class="entry-desc" style="margin-top:8px; font-size: 12.5px;">
    <p style="margin-bottom: 5px;"> I worked in that role during my junior and senior years of undergraduate study.</p>
    <ul style="list-style-type: none; padding-left: 20px;">
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
        First acquaintance with the workflow of CFD modeling –  <span style="text-decoration: underline;">pre-processing, solver, and post-processing</span>.
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span> Modeled several thermofluidic problems using a FEM-based commercial CFD tool – 
          <span style="text-decoration: underline;">COMSOL Multiphysics.</span> 
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span> Began working on my undergraduate thesis:
          <span style="text-decoration: underline;">Numerical Study of Natural and Mixed Convection in Enclosures with Porous Media of Varying Geometries.</span> 
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span> Was fortunate to draft my first publication-worthy manuscript titled <span style="text-decoration: underline;">“Natural convection and entropy generation inside a square chamber divided by a corrugated porous partition”</span>, and later  
          <span style="text-decoration: underline;">“Convective flow optimization inside a lid-driven chamber with a rotating porous cylinder using Darcy–Brinkman–Forchheimer model”</span> during my final year.
      </li>
      <li style="position: relative; margin-bottom: 5px;">
        <span style="position: absolute; left: -15px; font-size: 1em;">►</span> Had the privilege of being mentored by 
          <span style="text-decoration: underline;">Dr. Prodip K. Das, Associate Professor in Hydrogen Energy Systems, University of Edinburgh, UK.</span> 
      </li>
    </ul>
  </div>

</section>

<section class="section" id="professional">
  <h2>
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
          <div class="inst-name">Lecturer, Dept. of Petroleum and Mineral Resources Engineering</div>
          <div class="inst-sub">Bangladesh University of Engineering and Technology</div>
        </div>
      </div>
      <p class="entry-desc">
        <strong> Academic research </strong> on · Energy Resources Engineering · Hydrocarbon Reservoir Engineering · Advanced Well Testing and Interpretation · Advanced Reservoir Simulation .<br>
        <strong> Taught (Undergraduate Courses):</strong> PMRE 411 · Reservoir Engineering · PMRE 413 · Natural Gas Engineering (≈50 students each)
      </p>
    </div>
    <div class="entry-right">
      Dec 2023 – Present
      <span class="location">Dhaka, Bangladesh</span>
    </div>
  </div>

  <div class="entry" style="margin-top:12px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/buet.png" alt="BUET logo" class="institution-logo">
        <div>
          <div class="inst-name"> Co-instructor, Short Course </div>
          <div class="inst-sub">Directorate of Continuing Education, BUET</div>
        </div>
      </div>
      <div class="entry-desc">Short course: COMSOL Multiphysics Simulation of Thermo-fluidic Problems (Basic Level) · 2-day (12 hours) workshop · Instructor: Dr. Sumon Saha</div>
    </div>
    <div class="entry-right">Dec 2023 <span class="location">Dhaka, Bangladesh</span></div>
  </div>

  <div class="entry" style="margin-top:12px;">
    <div class="entry-left">
      <div class="institution">
        <img src="{{ site.baseurl }}/images/powertek.jpeg" alt="Powertek logo" class="institution-logo">
        <div>
          <div class="inst-name">Industrial Trainee</div>
          <div class="inst-sub"> Haripur 360 MW Combined Cycle Power Plant </div>
        </div>
      </div>
      <div class="entry-desc">An internship program organized by the dept. of Mechanical Engineering, BUET <br>
      Hands-on exposure to power generation, Plant unit operations (FGC, HRSG, ST, GT, WT), maintenance, and process control.</div>
    </div>
    <div class="entry-right">Nov-Dec 2022 (3 weeks) <span class="location">Dhaka, Bangladesh</span></div>
  </div>
</section>

  <section class="section" id="research">
    <h2>
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
        <path d="M3 7h18"></path>
        <path d="M12 3v18"></path>
      </svg>
      Research Projects
    </h2>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Thermal Management and Robustness of Linear Controllers (P, PI, PID) in Mixed Convection Modeling - A CFD Approach</div>
        <div class="entry-desc">Supervisor: Dr. Sumon Saha</div>
      </div>
      <div class="entry-right">June 2023</div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Revisiting the Numerical Calculation of Nusselt Number (Nu) for Different Thermal Boundary Conditions</div>
        <div class="entry-desc">Supervisor: Dr. Sumon Saha</div>
      </div>
      <div class="entry-right">Aug 2023</div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Natural and Mixed Convection Heat Transfer in the Presence of Porous Medium with Magnetohydrodynamics, Joule Heating, and Internal Heat Generation</div>
        <div class="entry-desc">Supervisor: Dr. Sumon Saha</div>
      </div>
      <div class="entry-right">Aug 2023</div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Subsurface Fluid Properties and Phase Behavior — A Case Study of the Titas Gas Field in Bangladesh: Changes in Natural Gas Phase Behavior Across Spatial and Temporal Dimensions. </div>
        <div class="entry-desc">Funded Project by 'Hydrocarbon Unit Research Program 2023–24' · Supervisor / PI: Dr. Mohammed Mahbubur Rahman</div>
      </div>
      <div class="entry-right">May 2024</div>
    </div>
    <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name"> Thermodynamic Optimization of a Novel Three-Stage Direct Expansion Cycle for LNG Cold Energy Recovery</div>
        <div class="entry-desc"> PI: Shaumik Rahman Ayon</div>
      </div>
      <div class="entry-right">May 2024</div>
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

    <ul style="margin:6px 0 0 14px;">
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
      Academic Projects
    </h2>

   <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Design of a Counter-Flow Shell & Helical Coil Tube Heat Exchanger (SHCTHX)</div>
        <div class="inst-sub">ME-310: Thermo-fluid System Design & Practice</div>
        <div class="entry-desc">CAD design · Thermo-hydraulic calculations · Prototype design and CFD simulation for flow & thermal visualization.</div>
      </div>
      <div class="entry-right">Feb 2022</div>
    </div>

  <div class="entry" style="margin-top:6px;">
      <div class="entry-left">
        <div class="inst-name">Self-Stabilizing, Computer-Controlled Laser Turret</div>
        <div class="inst-sub">ME-366: Electromechanical System Design & Practice</div>
        <div class="entry-desc">CAD · Arduino programming · sensor integration & feedback control · hardware-software integration for stabilization and precision.</div>
      </div>
      <div class="entry-right">Jul 2021</div>
    </div>
  </section>



  <section class="section" id="skills">
       <h2>
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
    <circle cx="12" cy="12" r="3"></circle>
    <path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 1 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V22a2 2 0 1 1-4 0v-.09a1.65 1.65 0 0 0-1-1.51 1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 1 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H2a2 2 0 1 1 0-4h.09a1.65 1.65 0 0 0 1.51-1 1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06c.48.48 1.17.64 1.82.33H8a1.65 1.65 0 0 0 1-1.51V2a2 2 0 1 1 4 0v.09c0 .66.37 1.26 1 1.51.65.31 1.34.15 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9c0 .66.37 1.26 1 1.51.65.31 1.34.15 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06c-.48.48-.64 1.17-.33 1.82V15z"></path>
  </svg>
  Technical Skills
</h2>
      <div class="entry-desc" style="margin-bottom:6px;">
    <strong>Highlights:</strong> Scientific Writing · Exploratory Data Analysis · Quantitative Research
  </div>

  <ul style="list-style-type: none; padding-left: 20px; font-size: 13.4px;">
    <li style="position: relative; margin-bottom: 6px;">
      <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
      <strong>Programming Languages:</strong> Python, MATLAB, C
    </li>
    <li style="position: relative; margin-bottom: 6px;">
      <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
      <strong>Documentation/Scripting:</strong> LaTeX, MS Office, Jupyter Notebook Markdown
    </li>
    <li style="position: relative; margin-bottom: 6px;">
      <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
      <strong>Visualization:</strong> Tecplot 360, WebPlotDigitizer, Desmos, Python - Matplotlib, Plotly, Seaborn
    </li>
    <li style="position: relative; margin-bottom: 6px;">
      <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
      <strong>Design, CAD, & Drawing:</strong> AutoCAD, SolidWorks, Proteus, Draw.io, Canva, Illustrator, Photoshop, LaTeX-TikZ, Python - OpenCV, Pillow, scikit-image
    </li>
    <li style="position: relative; margin-bottom: 6px;">
      <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
      <strong>FEM Modeling:</strong> COMSOL Multiphysics
    </li>
    <li style="position: relative; margin-bottom: 6px;">
      <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
      <strong>Reservoir Simulation:</strong> Kappa Workstation (Rubis, Saphir)
    </li>
    <li style="position: relative; margin-bottom: 6px;">
      <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
      <strong>ML/DL/Stats:</strong> Python - scikit-learn, TensorFlow, PyTorch, JAX, SciPy, PyMC3/4
    </li>
    <li style="position: relative; margin-bottom: 6px;">
      <span style="position: absolute; left: -15px; font-size: 1em;">►</span>
      <strong>Exploratory Data Analysis:</strong> Python - Pandas, NumPy, SciPy, Matplotlib, Plotly, Seaborn
    </li>
  </ul>
  </section>

  <section class="section" id="awards">
    <h2>
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
    <path d="M8 21h8"></path>
    <path d="M12 17v4"></path>
    <path d="M7 4h10v4a5 5 0 0 1-10 0V4z"></path>
    <path d="M5 4h2v4a7 7 0 0 0 14 0V4h2"></path>
  </svg>
  Achievements
</h2>
    <ul class="compact-list">
      <li><strong>Dr. Muhammad Harunur Rashid Award (ICME 2023):</strong> Best paper — 14th International Conference on Mechanical Engineering, Dept. of Mechanical Engineering, BUET</li>
      <li><strong>University Merit Scholarship (2018–2023):</strong> Awarded for consecutive terms, BUET</li>
      <li><strong>Dean’s List Award (2018–2023):</strong> Awarded for consecutive terms, Dept. of ME, BUET</li>
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
      Advanced Numerical Analysis (Dept. of ME, BUET) <strong>  ·  </strong>  Advanced Thermodynamics (classical and statistical) (Dept. of ME, BUET) <strong>  ·  </strong> Boiling & Condensation Heat Transfer (Dept. of ME, BUET) <strong> · </strong> Reservoir Engineering (Dept. of PMRE, BUET) <strong> · </strong> Well Testing Analysis (Dept. of PMRE, BUET)<strong>  ·  </strong> Non-linear Dynamics & Chaos (S. Strogatz, Online) <strong>  ·  </strong>Non-linear Systems (J. Slotine, MOCW) <strong>  ·  </strong> Control Bootcamp (S. L. Brunton, Online) <strong>  ·  </strong> Global Warming - Science & Modeling (D. Archer, edX) <strong>  ·  </strong> Understanding Rheology (F. Morrison, Online) <strong>  ·  </strong> Flow in Porous Media (M. Blunt, Online) <strong>  ·  </strong> Physics of Turbulence (M. K. Verma, IITK-NPTEL) <strong>  ·  </strong> Advanced Fluid Mechanics (S. Chakraborty, IITKGP-NPTEL) <strong>  ·  </strong> AI Principles & Techniques (Stanford Online) <strong>  ·  </strong> Deep Learning in Scientific Computing (ETH Zurich) <strong>  ·  </strong> Data Analytics and Geostatistics (M. J. Pyrcz, Online) <strong>  ·  </strong> Matrix Calculus for Machine Learning and Beyond (A. Edelman & S. G. Johnson, MOCW) <strong>  ·  </strong> Matrix, Numerical and Optimization Methods in Science and Engineering (K. Cassel, Online) <strong>  ·  </strong> Applied Time Series Analysis (A. K. Tangirala, IITM-NPTEL) <strong>  ·  </strong> Probabilistic System Analysis and Applied Probability (J. Tsitsiklis, MOCW) <strong>  ·  </strong> Data-Driven Science and Engineering (S. L. Brunton, Online) <strong>  ·  </strong> Random Physics Lectures (classical, Statistical, Quantum Mechanics, Modern Physics - Special and General Relativity by L. Susskind, Online )- did just for fun.  
    </div>

  <div class="inline-par" style="margin-top:8px;">
      <strong>Undergraduate / Core:</strong>
      Instrumentation and Measurement <strong>  ·  </strong> Electro-Mechanical System Design (Project) <strong>  ·  </strong> Noise & Vibration <strong>  ·  </strong> Control Engineering <strong>  ·  </strong> Engineering Mechanics (I & II) <strong>  ·  </strong> Mechanics of Solids <strong>  ·  </strong> Thermodynamics (Basic) <strong>  ·  </strong> Advanced Thermodynamics (Classical and Statistical) <strong>  ·  </strong> Fluid Mechanics (I & II) <strong>  ·  </strong> Heat Transfer <strong>  ·  </strong> Heat Transfer Equipment Design <strong>  ·  </strong> Thermo Fluid System Design (Project) <strong>  ·  </strong> Combustion <strong>  ·  </strong> Refrigeration and Building Mechanical System <strong>  ·  </strong> Numerical Analysis <strong>  ·  </strong> Computer Programming 
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