---
title: "Projects"
description: "Research and development projects by Scott P. McGrath, PhD"
---

<style>
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.project-card {
  background: var(--entry);
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(8, 145, 178, 0.15);
}

.project-header {
  background: linear-gradient(135deg, #0891b2 0%, #0e7490 100%);
  color: white;
  padding: 1.5rem;
}

.project-header h3 {
  margin: 0;
  font-size: 1.25rem;
  color: white;
}

.project-header .subtitle {
  font-size: 0.85rem;
  opacity: 0.9;
  margin-top: 0.3rem;
}

.project-body {
  padding: 1.25rem;
}

.project-body p {
  font-size: 0.95rem;
  line-height: 1.6;
  margin: 0 0 1rem 0;
  color: var(--secondary);
}

.project-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-top: 1rem;
}

.project-link {
  display: inline-flex;
  align-items: center;
  padding: 0.4rem 0.8rem;
  background: rgba(8, 145, 178, 0.1);
  color: var(--primary);
  border-radius: 6px;
  font-size: 0.85rem;
  text-decoration: none;
  transition: background 0.2s ease;
}

.project-link:hover {
  background: rgba(8, 145, 178, 0.2);
  text-decoration: none;
}

.project-link svg {
  width: 16px;
  height: 16px;
  margin-right: 0.4rem;
}

.publications-list {
  margin-top: 1rem;
  padding-top: 1rem;
  border-top: 1px solid var(--border);
}

.publications-list h4 {
  font-size: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  color: var(--secondary);
  margin: 0 0 0.5rem 0;
}

.publications-list ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.publications-list li {
  font-size: 0.85rem;
  margin-bottom: 0.4rem;
}

.publications-list a {
  color: var(--primary);
}

.video-container {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  margin: 1.5rem 0;
}

.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
}

.featured-project {
  background: var(--entry);
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  margin-bottom: 2rem;
}

.featured-header {
  background: linear-gradient(135deg, #0891b2 0%, #0e7490 100%);
  color: white;
  padding: 1.5rem;
}

.featured-header h3 {
  margin: 0;
  font-size: 1.25rem;
  color: white;
}

.featured-body {
  padding: 1.5rem;
}

.cta-section {
  text-align: center;
  padding: 2rem;
  margin-top: 2rem;
  background: rgba(8, 145, 178, 0.05);
  border-radius: 12px;
}

.cta-section h3 {
  margin-top: 0;
}
</style>

A selection of projects I've led or contributed to, spanning digital health, research tools, and science communication.

---

<div class="projects-grid">
<div class="project-card">
<div class="project-header">
<h3>ACTIVATE / Health Tequity</h3>
<div class="subtitle">Digital Health · Remote Patient Monitoring</div>
</div>
<div class="project-body">
<p>A digital health program bringing remote patient monitoring and care coordination to FQHCs serving rural and agricultural communities. Demonstrated improved diabetes and hypertension outcomes in underserved populations.</p>
<p><strong>Role:</strong> Program Manager, CITRIS Health (2021–2024)</p>
<div class="project-links">
<a href="https://www.healthtequity.net/#activate" target="_blank" class="project-link">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg>
Health Tequity
</a>
</div>
<div class="publications-list">
<h4>Related Publications</h4>
<ul>
<li><a href="https://www.thieme-connect.com/products/ejournals/html/10.1055/a-2096-0326" target="_blank">ACTIVATE Digital Health Pilot Program</a> — Applied Clinical Informatics, 2023</li>
<li><a href="https://arxiv.org/abs/2508.19378" target="_blank">Digital Care Coordination in Rural Health</a> — arXiv preprint</li>
</ul>
</div>
</div>
</div>
<div class="project-card">
<div class="project-header">
<h3>ATConnect</h3>
<div class="subtitle">mHealth · Telehealth · Sports Medicine</div>
</div>
<div class="project-body">
<p>A mobile health application designed to support Certified Athletic Trainers in conducting concussion assessments. Extended evaluation capabilities beyond the sideline through remote consultation.</p>
<p><strong>Award:</strong> Best Student Paper, AMIA Consumer Health WG (2017)</p>
<div class="project-links">
<a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC5977696/" target="_blank" class="project-link">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path><polyline points="14 2 14 8 20 8"></polyline><line x1="16" y1="13" x2="8" y2="13"></line><line x1="16" y1="17" x2="8" y2="17"></line></svg>
Read Paper
</a>
</div>
</div>
</div>
<div class="project-card">
<div class="project-header">
<h3>SciENcv Migration Tool</h3>
<div class="subtitle">Research Tools · Open Source</div>
</div>
<div class="project-body">
<p>An open-source tool to help researchers convert existing biosketches to the NIH SciENcv format. Built to address a significant pain point where manual data entry was taking researchers 4+ hours.</p>
<div class="project-links">
<a href="https://github.com/smcgrath-coder/sciencv-migration-tool" target="_blank" class="project-link">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
GitHub Repo
</a>
</div>
</div>
</div>
</div>

---

## C19 Weekly

<div class="featured-project">
<div class="featured-header">
<h3>COVID-19 Research Vidcast</h3>
</div>
<div class="featured-body">
<p>A YouTube channel I created and produced covering the latest COVID-19 research during the pandemic. Each week highlighted breaking research papers featuring informatics and data science contributions, translated into accessible summaries for a general audience. Built a community of <strong>1,200+ subscribers</strong>.</p>
<div class="video-container">
<iframe src="https://www.youtube.com/embed/H51LcH8gCDI?si=qsVLVS4sbr3MtnDM" title="C19 Weekly - First Episode" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<div class="project-links">
<a href="https://www.youtube.com/@TheC19Weekly" target="_blank" class="project-link">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.25 29 29 0 0 0-.46-5.33z"></path><polygon points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02"></polygon></svg>
Watch on YouTube
</a>
</div>
</div>
</div>

---

<div class="cta-section">
<h3>Interested in Collaborating?</h3>
<p>I'm always open to discussing new projects in digital health, medical education, or health informatics.</p>
<a href="/contact/" class="project-link" style="display: inline-flex;">Get in Touch</a>
</div>
