---
layout: default
title: Publications
slug: /publications
---

<style>
  .pub-section {
    max-width: 720px;
    margin: 0 auto;
    padding-bottom: 60px;
  }

  .pub-intro {
    margin-bottom: 32px;
    color: #666;
    font-size: 0.95em;
    line-height: 1.6;
  }

  .pub-year-group {
    margin-bottom: 36px;
  }

  .pub-year {
    font-size: 0.75em;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #999;
    margin-bottom: 16px;
    padding-bottom: 6px;
    border-bottom: 1px solid #eee;
  }

  .pub-card {
    padding: 16px 0;
    border-bottom: 1px solid #f5f5f5;
    position: relative;
  }

  .pub-card:last-child {
    border-bottom: none;
  }

  .pub-card .pub-title {
    font-weight: 500;
    font-size: 0.95em;
    line-height: 1.45;
    margin-bottom: 4px;
    color: #222;
  }

  .pub-card .pub-authors {
    font-size: 0.85em;
    color: #888;
    margin-bottom: 8px;
    line-height: 1.5;
  }

  .pub-card .pub-authors .me {
    color: #333;
    font-weight: 600;
  }

  .pub-card .pub-authors .equal {
    font-size: 0.7em;
    vertical-align: super;
    color: #b45309;
  }

  .pub-meta-row {
    display: flex;
    align-items: center;
    gap: 10px;
    flex-wrap: wrap;
  }

  .pub-venue {
    font-size: 0.82em;
    font-style: italic;
    color: #999;
  }

  .pub-link {
    font-size: 0.8em;
    font-weight: 500;
    color: #333;
    text-decoration: none;
    border-bottom: 1px solid #ddd;
    transition: border-color 0.2s;
    margin-left: auto;
  }

  .pub-link:hover {
    border-color: #333;
  }

  .pub-card.first-author .pub-title::before {
    content: '';
    display: inline-block;
    width: 6px;
    height: 6px;
    background: #b45309;
    border-radius: 50%;
    margin-right: 8px;
    vertical-align: middle;
    position: relative;
    top: -1px;
  }

  .pub-legend {
    display: flex;
    align-items: center;
    gap: 6px;
    font-size: 0.75em;
    color: #999;
    margin-top: 40px;
  }

  .pub-legend-dot {
    width: 6px;
    height: 6px;
    background: #b45309;
    border-radius: 50%;
    display: inline-block;
  }

  @media (max-width: 600px) {
    .pub-link { margin-left: 0; margin-top: 4px; }
    .pub-meta-row { gap: 6px; }
  }
</style>

<div class="pub-section">

  <p class="pub-intro">
    Methodology, survival analysis, explainability &amp; clinical applications.
  </p>

  <!-- ═══ 2025 ═══ -->
  <div class="pub-year-group">
    <div class="pub-year">2025</div>

    <div class="pub-card first-author">
      <div class="pub-title">Random survival forests for the analysis of recurrent events for right-censored data, with or without a terminal event</div>
      <div class="pub-authors"><span class="me">Murris J</span>, Bouaziz O, Jakubczak M, Katsahian S, Lavenu A</div>
      <div class="pub-meta-row">
        <span class="pub-venue">BMC Medical Research Methodology</span>
        <a class="pub-link" href="https://bmcmedresmethodol.biomedcentral.com/articles/10.1186/s12874-025-02678-z" target="_blank">paper ↗</a>
      </div>
    </div>
    
    <div class="pub-card">
      <div class="pub-title">Fluid balance after cardiac arrest: any impact on outcome? Insights from the MIMIC IV database</div>
      <div class="pub-authors">Didier J, <span class="me">Murris J</span>, et al.</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Resuscitation Plus</span>
        <a class="pub-link" href="https://www.sciencedirect.com/science/article/pii/S2666520425001742" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card">
      <div class="pub-title">SurvTreeSHAP(t): scalable explanation method for tree-based survival models</div>
      <div class="pub-authors">Ducrot L, Fevry G, Dano C, Texier R, <span class="me">Murris J</span>, Katsahian S</div>
      <div class="pub-meta-row">
        <span class="pub-venue">XAI Workshop, IJCAI 2025</span>
        <a class="pub-link" href="https://hal.science/view/index/docid/5108033" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card">
      <div class="pub-title">Mitigating Text Toxicity with Counterfactual Generation</div>
      <div class="pub-authors">Bhan M, Vittaut JN, Achache N, Chesneau N, Blangero A, Legrand V, <span class="me">Murris J</span>, Lesot MJ</div>
      <div class="pub-meta-row">
        <span class="pub-venue">3rd World Conference on XAI 2025</span>
        <a class="pub-link" href="https://arxiv.org/abs/2405.09948" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card first-author">
      <div class="pub-title">Bridging interpretability and survival endpoints in health technology assessment</div>
      <div class="pub-authors"><span class="me">Murris J</span>, Bhan M, Ducrot L, Katsahian S</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Preprint</span>
        <a class="pub-link" href="https://hal.science/hal-04967719v1/document" target="_blank">paper ↗</a>
      </div>
    </div>
  </div>

  <!-- ═══ 2024 ═══ -->
  <div class="pub-year-group">
    <div class="pub-year">2024</div>

    <div class="pub-card first-author">
      <div class="pub-title">Predicting Hospital Readmission after Cancer Surgery with Survival Analysis and Machine Learning</div>
      <div class="pub-authors"><span class="me">Murris J</span>, Katsahian S, Lavenu A</div>
      <div class="pub-meta-row">
        <span class="pub-venue">International Conference on AI in Healthcare</span>
        <a class="pub-link" href="https://zenodo.org/records/13152435" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card first-author">
      <div class="pub-title">A novel methodological framework for the analysis of health trajectories and survival outcomes in heart failure patients</div>
      <div class="pub-authors"><span class="me">Murris J</span>, Amadei T, Kirscher T, Klein A, Tropeano AI, Katsahian S</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Learning from Time Series for Health, ICLR 2024</span>
        <a class="pub-link" href="https://arxiv.org/abs/2403.03138" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card">
      <div class="pub-title">Evolution of minimally invasive liver surgery in France over the last decade</div>
      <div class="pub-authors">Deyrat J, [...] <span class="me">Murris J</span>, et al.</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Surgical Endoscopy</span>
        <a class="pub-link" href="https://link.springer.com/article/10.1007/s00464-024-10951-3" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card">
      <div class="pub-title">Increased levels of GM-CSF and CXCL10 and low CD8+ memory stem T Cell count are markers of immunosenescence and severe COVID-19 in older people</div>
      <div class="pub-authors">Poisson J, [...] <span class="me">Murris J</span>, et al.</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Immunity &amp; Ageing</span>
        <a class="pub-link" href="https://immunityageing.biomedcentral.com/articles/10.1186/s12979-024-00430-7" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card">
      <div class="pub-title">Protocol for Fever Control Using External Cooling in Mechanically Ventilated Patients with Septic Shock: SEPSISCOOL II Randomised Controlled Trial</div>
      <div class="pub-authors">Arnoux A, <span class="me">Murris J</span>, et al.</div>
      <div class="pub-meta-row">
        <span class="pub-venue">BMJ Open</span>
        <a class="pub-link" href="https://bmjopen.bmj.com/content/14/1/e069430.long" target="_blank">paper ↗</a>
      </div>
    </div>
  </div>

  <!-- ═══ 2023 ═══ -->
  <div class="pub-year-group">
    <div class="pub-year">2023</div>

    <div class="pub-card first-author">
      <div class="pub-title">Health technology assessment of artificial intelligence-based medical devices: what healthcare stakeholders need to know</div>
      <div class="pub-authors">Farah L<span class="equal">*</span>, <span class="me">Murris J</span><span class="equal">*</span>, Borget I, Guilloux A, Martelli N, Katsahian S</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Mayo Clinic Proceedings: Digital Health</span>
        <a class="pub-link" href="https://www.mcpdigitalhealth.org/article/S2949-7612(23)00010-X/fulltext" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card first-author">
      <div class="pub-title">Towards filling the gap around recurrent events in high dimensional framework: literature review and early comparison</div>
      <div class="pub-authors"><span class="me">Murris J</span>, Charles-Nelson A, Tadmouri A, Lavenu A, Katsahian S</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Biostatistics and Epidemiology</span>
        <a class="pub-link" href="https://www.tandfonline.com/doi/full/10.1080/24709360.2023.2283650" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card">
      <div class="pub-title">Risk factors for thromboembolic events in patients hospitalized for Covid-19 pneumonia</div>
      <div class="pub-authors">Degrave R, <span class="me">Murris J</span>, et al.</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Postgraduate Medical Journal</span>
        <a class="pub-link" href="https://academic.oup.com/pmj/advance-article-abstract/doi/10.1093/postmj/qgad104/7425479" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card">
      <div class="pub-title">A systematic review and meta-analysis of post-thrombotic syndrome, recurrent thromboembolism, and bleeding after upper extremity vein thrombosis</div>
      <div class="pub-authors">Espitia O, Raimbeau A, Planquette B, Katsahian S, Sanchez O, Bénichou A, <span class="me">Murris J</span></div>
      <div class="pub-meta-row">
        <span class="pub-venue">J Vascular Surgery: Venous and Lymphatic Disorders</span>
        <a class="pub-link" href="https://www.jvsvenous.org/article/S2213-333X(23)00382-7/fulltext" target="_blank">paper ↗</a>
      </div>
    </div>
  </div>

  <!-- ═══ 2022 ═══ -->
  <div class="pub-year-group">
    <div class="pub-year">2022</div>

    <div class="pub-card">
      <div class="pub-title">A comparison of methods for high-dimensional survival data on small samples: hyperparameter optimization and validation</div>
      <div class="pub-authors">Lavenu A, <span class="me">Murris J</span>, Mareau A, Rouzé T, Fromont M, Gares V, Katsahian S</div>
      <div class="pub-meta-row">
        <span class="pub-venue">53ème Journées de Statistique, SFdS</span>
        <a class="pub-link" href="https://jds22.sciencesconf.org/data/pages/LivretJdS22_version_longue.pdf" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card">
      <div class="pub-title">Regulatory T cells infiltrate the tumor-induced tertiary lymphoid structures and impose poor clinical outcome of patients with lung cancer</div>
      <div class="pub-authors">Devi-Marulkar P, [...] <span class="me">Murris J</span>, et al.</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Communications Biology</span>
        <a class="pub-link" href="https://www.nature.com/articles/s42003-022-04356-y" target="_blank">paper ↗</a>
      </div>
    </div>

    <div class="pub-card">
      <div class="pub-title">Adenoma detection rate is enough to assess endoscopist performance: a population-based observational study of FIT positive colonoscopies</div>
      <div class="pub-authors">Denis B, Gendre I, Tuzin N, <span class="me">Murris J</span>, Guignard A, Perrin P, Rahmi G</div>
      <div class="pub-meta-row">
        <span class="pub-venue">Endoscopy International Open</span>
        <a class="pub-link" href="https://pubmed.ncbi.nlm.nih.gov/36118642/" target="_blank">paper ↗</a>
      </div>
    </div>
  </div>

  <!-- ═══ 2021 ═══ -->
  <div class="pub-year-group">
    <div class="pub-year">2021</div>

    <div class="pub-card">
      <div class="pub-title">Quality of life in patients with BRAF-mutant melanoma receiving encorafenib plus binimetinib: results from the COLUMBUS phase III study</div>
      <div class="pub-authors">Gogas H, [...] <span class="me">Murris J</span>, et al.</div>
      <div class="pub-meta-row">
        <span class="pub-venue">European Journal of Cancer</span>
        <a class="pub-link" href="https://pubmed.ncbi.nlm.nih.gov/34091420/" target="_blank">paper ↗</a>
      </div>
    </div>
  </div>

  <div class="pub-legend">
    <span class="pub-legend-dot"></span> first / co-first author
  </div>

</div>
