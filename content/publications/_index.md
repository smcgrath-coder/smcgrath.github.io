---
title: "Publications"
description: "Research publications by Scott P. McGrath, PhD"
---

<style>
.metrics-summary {
  background: rgba(8, 145, 178, 0.08);
  border-radius: 8px;
  padding: 1.5rem;
  margin-bottom: 2rem;
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  align-items: center;
}

.metric-box {
  text-align: center;
}

.metric-value {
  font-size: 2rem;
  font-weight: 700;
  color: var(--primary);
  line-height: 1;
}

.metric-label {
  font-size: 0.85rem;
  color: var(--secondary);
  margin-top: 0.3rem;
}

.metrics-note {
  font-size: 0.8rem;
  color: var(--secondary);
  margin-left: auto;
}

.metrics-note a {
  color: var(--primary);
}

.filter-container {
  margin-bottom: 2rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.filter-btn {
  padding: 0.4rem 0.8rem;
  border: 1px solid var(--primary);
  background: transparent;
  color: var(--primary);
  border-radius: 4px;
  cursor: pointer;
  font-size: 0.85rem;
  transition: all 0.2s ease;
}

.filter-btn:hover, .filter-btn.active {
  background: var(--primary);
  color: white;
}

.filter-section {
  margin-bottom: 1rem;
}

.filter-label {
  font-weight: 600;
  margin-bottom: 0.5rem;
  font-size: 0.9rem;
  color: var(--secondary);
}

.pub-item {
  padding: 1rem 0;
  border-bottom: 1px solid var(--border);
  transition: opacity 0.3s ease;
}

.pub-item.hidden {
  display: none;
}

.pub-title {
  font-weight: 600;
  color: var(--primary);
  margin-bottom: 0.3rem;
}

.pub-title a {
  color: inherit;
  text-decoration: none;
}

.pub-title a:hover {
  text-decoration: underline;
}

.pub-authors {
  font-size: 0.9rem;
  color: var(--secondary);
  margin-bottom: 0.3rem;
}

.pub-venue {
  font-size: 0.85rem;
  font-style: italic;
  color: var(--secondary);
}

.pub-meta {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-top: 0.5rem;
  flex-wrap: wrap;
}

.pub-tags {
  display: flex;
  gap: 0.3rem;
  flex-wrap: wrap;
}

.pub-tag {
  display: inline-block;
  padding: 0.15rem 0.5rem;
  background: rgba(8, 145, 178, 0.1);
  color: var(--primary);
  border-radius: 3px;
  font-size: 0.75rem;
}

.pub-citations {
  font-size: 0.8rem;
  color: var(--secondary);
  background: rgba(0,0,0,0.05);
  padding: 0.2rem 0.5rem;
  border-radius: 3px;
}

.pub-citations.loading {
  opacity: 0.5;
}

.pub-links {
  font-size: 0.85rem;
}

.pub-links a {
  margin-right: 1rem;
}

.pub-year {
  font-size: 0.8rem;
  color: var(--secondary);
  float: right;
}

.section-header {
  margin-top: 2rem;
  margin-bottom: 1rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid var(--primary);
}

.no-results {
  padding: 2rem;
  text-align: center;
  color: var(--secondary);
  display: none;
}

.results-count {
  font-size: 0.9rem;
  color: var(--secondary);
  margin-bottom: 1rem;
}

@media (max-width: 600px) {
  .metrics-summary {
    justify-content: space-around;
  }
  .metrics-note {
    width: 100%;
    text-align: center;
    margin-left: 0;
    margin-top: 1rem;
  }
}
</style>

<div class="metrics-summary">
  <div class="metric-box">
    <div class="metric-value" id="total-citations">—</div>
    <div class="metric-label">Citations</div>
  </div>
  <div class="metric-box">
    <div class="metric-value" id="h-index">—</div>
    <div class="metric-label">h-index</div>
  </div>
  <div class="metric-box">
    <div class="metric-value" id="pub-count">31</div>
    <div class="metric-label">Publications</div>
  </div>
  <div class="metrics-note">
    Data from <a href="https://scholar.google.com/citations?user=bQkPd4sAAAAJ&hl=en" target="_blank">Google Scholar</a>
  </div>
</div>

<div class="filter-section">
  <div class="filter-label">Filter by Topic:</div>
  <div class="filter-container" id="topic-filters">
    <button class="filter-btn active" data-filter="all">All Topics</button>
    <button class="filter-btn" data-filter="ai">AI & Machine Learning</button>
    <button class="filter-btn" data-filter="genomics">Precision Medicine & Genomics</button>
    <button class="filter-btn" data-filter="digital-health">Digital Health & Telehealth</button>
    <button class="filter-btn" data-filter="education">Medical Education</button>
    <button class="filter-btn" data-filter="dtc">Consumer Genomics</button>
  </div>
</div>

<div class="filter-section">
  <div class="filter-label">Filter by Type:</div>
  <div class="filter-container" id="type-filters">
    <button class="filter-btn active" data-type="all">All Types</button>
    <button class="filter-btn" data-type="journal">Journal Articles</button>
    <button class="filter-btn" data-type="conference">Conference Papers</button>
    <button class="filter-btn" data-type="chapter">Book Chapters</button>
    <button class="filter-btn" data-type="other">Invited & Other</button>
  </div>
</div>

<div class="results-count" id="results-count"></div>

<div class="no-results" id="no-results">No publications match your filters.</div>

<div id="publications-list">

<!-- JOURNAL ARTICLES -->

<div class="pub-item" data-topics="ai genomics" data-type="journal">
  <span class="pub-year">2025</span>
  <div class="pub-title">2025 Bioinformatics and Translational Informatics Best Papers</div>
  <div class="pub-authors">McGrath, S. · Benton, M.L.</div>
  <div class="pub-venue">IMIA Yearbook of Medical Informatics (In Review)</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">AI</span>
      <span class="pub-tag">Genomics</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="digital-health" data-type="journal">
  <span class="pub-year">2025</span>
  <div class="pub-title">Improving Hypertension and Diabetes Outcomes with Digital Care Coordination and Remote Monitoring in Rural Health</div>
  <div class="pub-authors">Kim, K. · Dawes, D. · Lindeman, D. · McGrath, S. · Pai, V.</div>
  <div class="pub-venue">npj Cardiovascular Health (In Review)</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Digital Health</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="ai genomics" data-type="journal" data-doi="10.1055/s-0044-1800755">
  <span class="pub-year">2024</span>
  <div class="pub-title"><a href="https://doi.org/10.1055/s-0044-1800755" target="_blank">Advancements in Precision Prevention: Top Bioinformatics and Translational Informatics Papers of 2023</a></div>
  <div class="pub-authors">McGrath, S. · Benton, M.L.</div>
  <div class="pub-venue">IMIA Yearbook of Medical Informatics</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1055/s-0044-1800755">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="ai genomics" data-type="journal" data-doi="10.1093/jamia/ocae128">
  <span class="pub-year">2024</span>
  <div class="pub-title"><a href="https://doi.org/10.1093/jamia/ocae128" target="_blank">A Comparative Evaluation of ChatGPT 3.5 and ChatGPT 4 in Responses to Selected Genetics Questions</a></div>
  <div class="pub-authors">McGrath, S. · Kozel, B. · Gracefo, S. · Sutherland, N. · Danford, C. · Walton, N.</div>
  <div class="pub-venue">Journal of the American Medical Informatics Association (JAMIA)</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">AI</span>
      <span class="pub-tag">Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1093/jamia/ocae128">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="ai genomics" data-type="journal" data-doi="10.1093/jamia/ocad211">
  <span class="pub-year">2024</span>
  <div class="pub-title"><a href="https://doi.org/10.1093/jamia/ocad211" target="_blank">Enabling the Clinical Application of Artificial Intelligence in Genomics: A Perspective of the AMIA Genomics and Translational Bioinformatics Workgroup</a></div>
  <div class="pub-authors">Walton, N. · McGrath, S. · et al.</div>
  <div class="pub-venue">Journal of the American Medical Informatics Association (JAMIA)</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">AI</span>
      <span class="pub-tag">Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1093/jamia/ocad211">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="ai genomics education" data-type="journal" data-doi="10.1101/2023.10.26.564260">
  <span class="pub-year">2023</span>
  <div class="pub-title"><a href="https://doi.org/10.1101/2023.10.26.564260" target="_blank">Evaluating ChatGPT as an Agent for Providing Genetic Education</a></div>
  <div class="pub-authors">Walton, N. · Kozel, B. · Gracefo, S. · Sutherland, N. · Danford, C. · McGrath, S.</div>
  <div class="pub-venue">BioRxiv (Preprint)</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">AI</span>
      <span class="pub-tag">Genomics</span>
      <span class="pub-tag">Education</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1101/2023.10.26.564260">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="digital-health" data-type="journal" data-doi="10.1055/a-2110-4722">
  <span class="pub-year">2023</span>
  <div class="pub-title"><a href="https://doi.org/10.1055/a-2110-4722" target="_blank">The ACTIVATE Digital Health Pilot Program for Diabetes and Hypertension in an Underserved and Rural Community</a></div>
  <div class="pub-authors">Kim, K.K. · McGrath, S. · Solorza, J.L. · Lindeman, D.</div>
  <div class="pub-venue">Applied Clinical Informatics</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Digital Health</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1055/a-2110-4722">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="genomics" data-type="journal" data-doi="10.1055/s-0043-1768726">
  <span class="pub-year">2023</span>
  <div class="pub-title"><a href="https://doi.org/10.1055/s-0043-1768726" target="_blank">Intersecting Pathways in Bioinformatics and Translational Informatics: A One Health Perspective on Key Contributions and Future Directions</a></div>
  <div class="pub-authors">Benton, M.L. · McGrath, S.</div>
  <div class="pub-venue">IMIA Yearbook of Medical Informatics</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1055/s-0043-1768726">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="genomics" data-type="journal" data-doi="10.1055/s-0042-1742514">
  <span class="pub-year">2022</span>
  <div class="pub-title"><a href="https://doi.org/10.1055/s-0042-1742514" target="_blank">2021 Bioinformatics and Translational Informatics Best Papers</a></div>
  <div class="pub-authors">Benton, M.L. · McGrath, S.</div>
  <div class="pub-venue">IMIA Yearbook of Medical Informatics</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1055/s-0042-1742514">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="genomics" data-type="journal" data-doi="10.1055/s-0041-1726528">
  <span class="pub-year">2021</span>
  <div class="pub-title"><a href="https://doi.org/10.1055/s-0041-1726528" target="_blank">Predictions, Pivots, and a Pandemic: A Review of 2020's Top Translational Bioinformatics Publications</a></div>
  <div class="pub-authors">McGrath, S. · Benton, M.L. · Tavakoli, M. · Tatonetti, N.P.</div>
  <div class="pub-venue">IMIA Yearbook of Medical Informatics</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1055/s-0041-1726528">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="genomics" data-type="journal" data-doi="10.3389/fmed.2021.663014">
  <span class="pub-year">2021</span>
  <div class="pub-title"><a href="https://doi.org/10.3389/fmed.2021.663014" target="_blank">Legal Challenges in Precision Medicine: What Duties Arising from Genetic and Genomic Testing Does a Physician Owe to Patients?</a></div>
  <div class="pub-authors">McGrath, S. · Peabody, A. · Walton, D. · Walton, N.</div>
  <div class="pub-venue">Frontiers in Medicine</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.3389/fmed.2021.663014">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="education" data-type="journal" data-doi="10.5210/ojphi.v12i1.10696">
  <span class="pub-year">2020</span>
  <div class="pub-title"><a href="https://doi.org/10.5210/ojphi.v12i1.10696" target="_blank">Current Approaches and Trends in Public Health Informatics Education</a></div>
  <div class="pub-authors">Schwartz, D. · McGrath, S. · Monsen, K. · Dixon, B.</div>
  <div class="pub-venue">Online Journal of Public Health Informatics</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Education</span>
    </div>
    <span class="pub-citations loading" data-doi="10.5210/ojphi.v12i1.10696">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="genomics dtc" data-type="journal" data-doi="10.1186/s12913-019-4679-8">
  <span class="pub-year">2019</span>
  <div class="pub-title"><a href="https://doi.org/10.1186/s12913-019-4679-8" target="_blank">Are Providers Prepared for Genomic Medicine: Interpretation of Direct-to-Consumer Genetic Testing (DTC-GT) Results and Genetic Self-Efficacy by Medical Professionals</a></div>
  <div class="pub-authors">McGrath, S. · Walton, N. · Williams, M.S. · Kim, K.K. · Bastola, K.</div>
  <div class="pub-venue">BMC Health Services Research</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
      <span class="pub-tag">Consumer Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1186/s12913-019-4679-8">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="genomics" data-type="journal">
  <span class="pub-year">2018</span>
  <div class="pub-title">The Influence of 'Omics' in Shaping Precision Medicine</div>
  <div class="pub-authors">McGrath, S.</div>
  <div class="pub-venue">European Medical Journal Innovations</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="genomics education" data-type="journal" data-doi="10.1186/s12920-016-0183-8">
  <span class="pub-year">2016</span>
  <div class="pub-title"><a href="https://doi.org/10.1186/s12920-016-0183-8" target="_blank">Building Towards Precision Medicine: Empowering Medical Professionals for the Next Revolution</a></div>
  <div class="pub-authors">McGrath, S. · Ghersi, D.</div>
  <div class="pub-venue">BMC Medical Genomics</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
      <span class="pub-tag">Education</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1186/s12920-016-0183-8">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="dtc genomics" data-type="journal" data-doi="10.1159/000444477">
  <span class="pub-year">2016</span>
  <div class="pub-title"><a href="https://doi.org/10.1159/000444477" target="_blank">Comprehension and Data-Sharing Behavior of Direct-to-Consumer Genetic Test Customers</a></div>
  <div class="pub-authors">McGrath, S.P. · Coleman, J. · Najjar, L. · Fruhling, A. · Bastola, D.R.</div>
  <div class="pub-venue">Public Health Genomics</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Consumer Genomics</span>
      <span class="pub-tag">Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1159/000444477">Loading...</span>
  </div>
</div>

<!-- CONFERENCE PAPERS -->

<div class="pub-item" data-topics="digital-health" data-type="conference">
  <span class="pub-year">2022</span>
  <div class="pub-title">ACTIVATE: Results of a Digital Health Pilot Program for Diabetes and Hypertension in an Underserved and Rural Community</div>
  <div class="pub-authors">Kim, K.K. · McGrath, S. · Solorza, J.L. · Lindeman, D.</div>
  <div class="pub-venue">AMIA Clinical Informatics Conference</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Digital Health</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="digital-health" data-type="conference">
  <span class="pub-year">2021</span>
  <div class="pub-title">Design and Feasibility of ACTIVATE, a Digital Health Platform for Community Health Centers in Response to COVID-19</div>
  <div class="pub-authors">McGrath, S. · Matsumoto, C.G. · Lindeman, D. · Kim, K.K.</div>
  <div class="pub-venue">AMIA Annual Symposium</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Digital Health</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="genomics" data-type="conference">
  <span class="pub-year">2019</span>
  <div class="pub-title">Improving the Odds of Success for Precision Medicine Using the Social Ecological Model</div>
  <div class="pub-authors">McGrath, S.</div>
  <div class="pub-venue">AMIA Annual Symposium</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="genomics dtc" data-type="conference">
  <span class="pub-year">2019</span>
  <div class="pub-title">Interpretation and Self-Efficacy of DTC Genetic Tests by Medical Professionals</div>
  <div class="pub-authors">McGrath, S. · Walton, N. · Williams, M.S. · Kim, K. · Bastola, K.</div>
  <div class="pub-venue">AMIA Informatics Summit</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
      <span class="pub-tag">Consumer Genomics</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="genomics" data-type="conference">
  <span class="pub-year">2019</span>
  <div class="pub-title">A Decade of Translational Bioinformatics "Year-in-Review" Presentations: An 11-Year Retrospective Analysis</div>
  <div class="pub-authors">Romano, J.D. · Bernauer, M. · McGrath, S. · Nagar, S.D. · Freimuth, R.R.</div>
  <div class="pub-venue">AMIA Informatics Summit</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="digital-health" data-type="conference">
  <span class="pub-year">2017</span>
  <div class="pub-title">Developing a Concussion Assessment mHealth App for Certified Athletic Trainers</div>
  <div class="pub-authors">McGrath, S. · McGrath, M. · Bastola, D.R.</div>
  <div class="pub-venue">AMIA Annual Symposium — Best Student Paper, Consumer Health WG</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Digital Health</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="digital-health" data-type="conference" data-doi="10.1007/978-3-319-23344-4_36">
  <span class="pub-year">2015</span>
  <div class="pub-title"><a href="https://doi.org/10.1007/978-3-319-23344-4_36" target="_blank">Extending Concussion Evaluations with Telemedicine for Certified Athletic Trainers</a></div>
  <div class="pub-authors">McGrath, S. · Bastola, D.K.</div>
  <div class="pub-venue">International Conference on Brain Informatics & Health</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Digital Health</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1007/978-3-319-23344-4_36">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="dtc genomics" data-type="conference" data-doi="10.1145/2649387.2660831">
  <span class="pub-year">2014</span>
  <div class="pub-title"><a href="https://doi.org/10.1145/2649387.2660831" target="_blank">DTC Genetic Testing and Consumer Comprehension</a></div>
  <div class="pub-authors">McGrath, S. · Bastola, D.K.</div>
  <div class="pub-venue">ACM Conference on Bioinformatics, Computational Biology, and Health Informatics</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Consumer Genomics</span>
      <span class="pub-tag">Genomics</span>
    </div>
    <span class="pub-citations loading" data-doi="10.1145/2649387.2660831">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="" data-type="conference" data-doi="10.1109/DAPSE.2013.6628080">
  <span class="pub-year">2013</span>
  <div class="pub-title"><a href="https://doi.org/10.1109/DAPSE.2013.6628080" target="_blank">Concept to Commit: A Pattern Designed to Trace Code Changes from User Requests to Change Implementation</a></div>
  <div class="pub-authors">McGrath, S. · Bastola, D.K. · Siy, H.</div>
  <div class="pub-venue">IEEE Data Analysis Patterns in Software Engineering (DAPSE)</div>
  <div class="pub-meta">
    <span class="pub-citations loading" data-doi="10.1109/DAPSE.2013.6628080">Loading...</span>
  </div>
</div>

<div class="pub-item" data-topics="" data-type="conference">
  <span class="pub-year">2012</span>
  <div class="pub-title">A Comparison of Computational Approaches in the Molecular Identification of Pathogenic Organisms</div>
  <div class="pub-authors">Bastola, D.K. · McGrath, S. · Bhowmick, S. · Thapa, I.</div>
  <div class="pub-venue">IEEE Healthcare Informatics, Imaging and Systems Biology (HISB)</div>
  <div class="pub-meta">
  </div>
</div>

<!-- BOOK CHAPTERS -->

<div class="pub-item" data-topics="digital-health" data-type="chapter">
  <span class="pub-year">2015</span>
  <div class="pub-title">Mobile Healthcare User Interface Design Application Strategies</div>
  <div class="pub-authors">Fruhling, A. · Raman, S. · McGrath, S.</div>
  <div class="pub-venue">CRC Press: E-Medicine, E-Health, M-Health, Telemedicine, and Telehealth Handbook (Chapter 17)</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Digital Health</span>
    </div>
  </div>
</div>

<!-- INVITED & OTHER -->

<div class="pub-item" data-topics="genomics" data-type="other">
  <span class="pub-year">2016</span>
  <div class="pub-title">The Declining Cost of Genetic Sequencing is Opening the Door for Precision Medicine</div>
  <div class="pub-authors">McGrath, S.</div>
  <div class="pub-venue">Atlas of Science (Invited)</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="genomics" data-type="other">
  <span class="pub-year">2016</span>
  <div class="pub-title">Precision Medicine: How to Get the Hope Without the Hype</div>
  <div class="pub-authors">McGrath, S.</div>
  <div class="pub-venue">BMC Series Blog (Invited)</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="genomics" data-type="other">
  <span class="pub-year">2019</span>
  <div class="pub-title">The Revolution Will Be Sequenced: Anticipating the Knowledge Gap Within the Genomic Pillar of Precision Medicine</div>
  <div class="pub-authors">McGrath, S.</div>
  <div class="pub-venue">PhD Dissertation, University of Nebraska at Omaha</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Genomics</span>
    </div>
  </div>
</div>

<div class="pub-item" data-topics="dtc genomics" data-type="other">
  <span class="pub-year">2013</span>
  <div class="pub-title">How Personal Should Personal Genomics Be? A Study of the Direct to Consumer Market for Genetic Testing and the Need for an Honest Broker</div>
  <div class="pub-authors">McGrath, S.</div>
  <div class="pub-venue">MS Thesis, University of Nebraska at Omaha</div>
  <div class="pub-meta">
    <div class="pub-tags">
      <span class="pub-tag">Consumer Genomics</span>
      <span class="pub-tag">Genomics</span>
    </div>
  </div>
</div>

</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  // Filter functionality
  const topicBtns = document.querySelectorAll('#topic-filters .filter-btn');
  const typeBtns = document.querySelectorAll('#type-filters .filter-btn');
  const pubItems = document.querySelectorAll('.pub-item');
  const noResults = document.getElementById('no-results');
  const resultsCount = document.getElementById('results-count');
  
  let currentTopic = 'all';
  let currentType = 'all';
  
  function updateFilters() {
    let visibleCount = 0;
    
    pubItems.forEach(item => {
      const topics = item.dataset.topics || '';
      const type = item.dataset.type || '';
      
      const topicMatch = currentTopic === 'all' || topics.includes(currentTopic);
      const typeMatch = currentType === 'all' || type === currentType;
      
      if (topicMatch && typeMatch) {
        item.classList.remove('hidden');
        visibleCount++;
      } else {
        item.classList.add('hidden');
      }
    });
    
    noResults.style.display = visibleCount === 0 ? 'block' : 'none';
    resultsCount.textContent = `Showing ${visibleCount} publication${visibleCount !== 1 ? 's' : ''}`;
  }
  
  topicBtns.forEach(btn => {
    btn.addEventListener('click', function() {
      topicBtns.forEach(b => b.classList.remove('active'));
      this.classList.add('active');
      currentTopic = this.dataset.filter;
      updateFilters();
    });
  });
  
  typeBtns.forEach(btn => {
    btn.addEventListener('click', function() {
      typeBtns.forEach(b => b.classList.remove('active'));
      this.classList.add('active');
      currentType = this.dataset.type;
      updateFilters();
    });
  });
  
  updateFilters();

  // Semantic Scholar API integration
  const citationElements = document.querySelectorAll('.pub-citations[data-doi]');
  let allCitations = [];
  let fetchedCount = 0;
  const totalToFetch = citationElements.length;
  
  async function fetchCitations(doi) {
    try {
      const response = await fetch(`https://api.semanticscholar.org/graph/v1/paper/DOI:${doi}?fields=citationCount`);
      if (response.ok) {
        const data = await response.json();
        return data.citationCount || 0;
      }
    } catch (e) {
      console.log(`Could not fetch citations for ${doi}`);
    }
    return null;
  }
  
  async function updateCitations() {
    for (const el of citationElements) {
      const doi = el.dataset.doi;
      // Add small delay to avoid rate limiting
      await new Promise(resolve => setTimeout(resolve, 150));
      
      const count = await fetchCitations(doi);
      
      if (count !== null) {
        el.textContent = `${count} citation${count !== 1 ? 's' : ''}`;
        el.classList.remove('loading');
        allCitations.push(count);
      } else {
        el.textContent = '';
        el.style.display = 'none';
      }
      
      fetchedCount++;
      
      // Update summary once we have some data
      if (fetchedCount === totalToFetch) {
        updateSummary();
      }
    }
  }
  
  function updateSummary() {
    if (allCitations.length > 0) {
      const total = allCitations.reduce((a, b) => a + b, 0);
      document.getElementById('total-citations').textContent = total;
      
      // Calculate h-index
      const sorted = [...allCitations].sort((a, b) => b - a);
      let h = 0;
      for (let i = 0; i < sorted.length; i++) {
        if (sorted[i] >= i + 1) {
          h = i + 1;
        } else {
          break;
        }
      }
      document.getElementById('h-index').textContent = h;
    }
  }
  
  // Start fetching citations
  updateCitations();
});
</script>
