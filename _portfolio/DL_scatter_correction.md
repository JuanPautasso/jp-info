---
title: "Deep learning for x-ray scatter correction in dedicated breast CT"
excerpt: >
  <div>
    <p>Developed a deep learning model for scatter correction in breast CT images, improving image quality and enabling real-time clinical applications. Achieved 25% contrast enhancement and effective scatter correction as shown in the figure below.</p>
    <img src="https://raw.githubusercontent.com/JuanPautasso/jp-info/master/images/image_DL.png" />
    <p>Figure: Example of profiles obtained for the three selected slices of reconstructed patient bCT images, both uncorrected and DL-corrected. The filled band represents the obtained range of x-ray linear attenuation values for fibroglandular (fuchsia) and adipose tissue (pink).</p>
    <p>For more information, please click the title above.</p>
  </div>
collection: portfolio
---

### Overview
This project focuses on developing a deep learning (DL) model to correct x-ray scatter in breast computed tomography (bCT) images. The goal is to improve image quality by enhancing contrast and correcting artifacts, ultimately supporting quantitative reconstructions for clinical applications.

### Key Features
- Utilized U-Net architecture for scatter correction.
- Generated training data using Monte Carlo simulations.
- Improved contrast by a mean of 25% and reduced cupping artifacts.
- Achieved near real-time scatter correction (~0.2s per projection).
- Validated results with structural similarity (SSIM) of 0.99.

### Technical Highlights
1. **Data Generation**:
   - Segmented patient scans into breast tissue types: skin, adipose, fibroglandular.
   - Augmented phantoms with translations to create robust training datasets.
   - Simulated primary and scatter projection images using Monte Carlo algorithms.

2. **Model Development**:
   - Designed a U-Net model to estimate scatter signal.
   - Incorporated breast thickness maps and positional data as additional inputs.
   - Trained on 110 phantoms, validated internally, and tested externally.
  
   <img src="https://raw.githubusercontent.com/JuanPautasso/jp-info/master/images/image_DL.png" alt="Schematic overview of the DL architecture used for scatter estimation. The total projection images of size 128 × 80 pixels were
defined as the main input, while the respective thickness maps and the breast center of mass distance were included at the network bottleneck" />

3. **Validation & Testing**:
   - Internal Validation: Mean Absolute Error (MAE) of 2.94%.
   - External Testing: MAE of 2.84% and structural similarity of 0.99.
   - Clinical Evaluation: Improved contrast-to-noise ratio (CNR) and reduced artifacts.

### Clinical Significance
The scatter-corrected images enhanced visual interpretation, improved contrast by a mean of 25%, and significantly reduced artifacts. These results demonstrate the feasibility of integrating this model into daily clinical workflows.


---
<section id="presentation">
  <h2>Presentation</h2>
  <iframe src="https://docs.google.com/gview?url=https://raw.githubusercontent.com/JuanPautasso/jp-info/master/presentations/presentation_DL_scatter.pdf&embedded=true" width="100%" height="600px"></iframe>
  <p>If the presentation does not load, simply refresh or you can <a href="https://raw.githubusercontent.com/JuanPautasso/jp-info/master/presentations/presentation_DL_scatter.pdf" target="_blank">download it here</a>.</p>
</section>

---

<p>You can download the full document from the "Publications" section under the title:</p>
<p><strong>"Deep learning for x-ray scatter correction in dedicated breast CT"</strong>. <em>Published in Medical Physics, 2023.</em></p>


