---
title: "Design and development of a novel pipeline for resting-state functional magnetic resonance imaging (R-fMRI) processing"
excerpt: >
  <div>
    <p>The developed pipeline automates preprocessing and processing of R-fMRI data to analyze functional connectivity, particularly in the Default Mode Network (DMN). Key outcomes include:</p>
    <ul>
      <li>Functional connectivity differences between control subjects (27) and patients with mild cognitive impairment (32) were identified, specifically reduced connectivity between the left hippocampus and right medial prefrontal cortex.</li>
      <li>Statistical analyses, accounting for age and gender, confirmed significant differences (p < 0.05 after Bonferroni correction).</li>
      <li>The pipeline enables efficient data analysis with results generated in approximately 50 minutes per subject, a significant improvement over manual methods.</li>
      <li>The tool is flexible, standardized, and accessible on conventional hardware, promoting widespread usability and reducing workload and costs for researchers and clinicians.</li>
      <li>After analyzing the results, it was found that there are differences in connectivity between the control group and the groups with mild cognitive impairment. The difference is found in regions 4-5, that is, between the left hippocampus and the right medial prefrontal cortex. See the figure below:</li>
    </ul>
    <img src="https://raw.githubusercontent.com/JuanPautasso/jp-info/master/images/image_24.jpg" alt="Pipeline image" />
    <p>Figure: Right medial prefrontal cortex and left hippocampus.</p>
    <p>For more information, please click the title above.</p>
  </div>
collection: portfolio

---

A preprocessing and processing pipeline for R-fMRI data was developed, tailored to meet research needs with input from professionals at Hospital General Universitario Gregorio Marañón. The pipeline integrates the strengths of various open-source fMRI software tools and was successfully implemented and tested.

### Key Achievements:
- Accurate cortical surface extraction and successful structural-functional image registration.
- Automated execution: The pipeline can be executed from a terminal or executable file, allowing analysis of multiple patients with results organized for easy access.
- Compatibility: Works on both personal computers and clusters, requiring only standard hardware (e.g., 8GB RAM, i5 processor).
- Efficiency: Processing time is reduced to approximately 50 minutes per patient, compared to a full day when done manually.
- Standardized processing: The pipeline ensures uniform analysis for all patients, with flexibility to replace individual software functions as needed.
- Scalable analysis: It efficiently analyzed a study sample of 59 patients (healthy controls and patients with mild cognitive impairment) in just 3 days, identifying connectivity differences between the left hippocampus and right medial prefrontal cortex. The results demonstrated the pipeline's reliability and its seamless integration with Python for statistical analyses.

This multidisciplinary project combines mathematics, statistics, programming, machine learning, and medical imaging. It highlights the benefits of collaboration in research, reducing workload and costs while accelerating results, thus advancing patient care and scientific understanding.

---
<section id="presentation">
  <h2>Presentation</h2>
  <iframe src="https://docs.google.com/gview?url=https://raw.githubusercontent.com/JuanPautasso/jp-info/master/presentations/presentation_master.pdf&embedded=true" width="100%" height="600px"></iframe>
  <p>If the presentation does not load, simply refresh or you can <a href="https://raw.githubusercontent.com/JuanPautasso/jp-info/master/presentations/presentation_master.pdf" target="_blank">download it here</a>.</p>
</section>

---

<p>You can download the full document from the [Publications](/jp-info/publications/) section under the title:</p>
<p><strong>"Design and Development of a Novel Pipeline for Resting-State Functional Magnetic Resonance Imaging Processing"</strong>. <em>Published in E.T.S.I. Telecomunicación (UPM), 2019.</em></p>
