---
layout: default
title: Projects
---

<style>
  .project-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 1em 1em 1em;
  }

  .project-row {
    display: flex;
    gap: 2em;
    margin-bottom: 4em;
    align-items: stretch;
    justify-content: space-between;
  }

  .even-row {
    flex-direction: row-reverse;
  }

  .project-image-wrapper {
    flex: 0 0 30%;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .project-text {
    flex: 0 0 70%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .project-text p {
    text-align: justify;
    margin-top: 0.5em;
  }

  .project-image {
    width: 100%;
    max-height: 300px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
    transition: transform 0.2s ease;
  }

  .project-image:hover {
    transform: scale(1.03);
  }

  .project-buttons {
    margin-top: 1em;
  }

  .project-buttons a {
    display: inline-block;
    margin-right: 0.8em;
    padding: 0.4em 0.9em;
    background-color: #f1f1f1;
    color: #222;
    font-size: 0.85rem;
    text-decoration: none;
    border-radius: 6px;
    transition: background-color 0.2s;
  }

  .project-buttons a:hover {
    background-color: #ddd;
  }

  .project-divider {
    border-top: 1.5px dashed #bbb;
    margin: 2.5em 0;
  }

  @media (max-width: 768px) {
    .project-row {
      flex-direction: column !important;
    }

    .project-image-wrapper,
    .project-text {
      flex: 1 1 100%;
    }

    .project-image {
      height: auto;
      max-height: none;
    }
  }
</style>

<div class="project-container">

  <div class="project-row">
    <div class="project-image-wrapper">
      <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank" rel="noopener noreferrer">
        <img src="/assets/images/Plateperfect.jpg" alt="PlatePerfect" class="project-image">
      </a>
    </div>
    <div class="project-text">
      <h3>PlatePerfect</h3>
      <p>
        PlatePerfect is a computer vision-powered system designed to ensure consistency and quality in restaurant food presentation.
        Using a YOLOv8-nano model fine-tuned on the UECFOODPIX dataset (10,000+ labeled images), the system segments and classifies
        ingredients on plated dishes in real time. Deployed through an iPad app with an external camera, the model achieved over
        68% precision and recall across 101 food classes. By automating visual inspection, PlatePerfect helps reduce manual
        quality assurance effort and improves consistency across restaurant chains.
      </p>
      <div class="project-buttons">
        <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank">GitHub</a>
        <a href="/assets/pdfs/Does_the_plate_look_correct.pdf" target="_blank">Report</a>
      </div>
    </div>
  </div>

  <div class="project-divider"></div>

  <div class="project-row even-row">
    <div class="project-image-wrapper">
      <a href="https://github.com/your/tinyml-doorbell" target="_blank" rel="noopener noreferrer">
        <img src="/assets/images/profile.jpg" alt="Smart Doorbell" class="project-image">
      </a>
    </div>
    <div class="project-text">
      <h3>VizWhiz</h3>
      <p>
        This project uses knowledge distillation to deploy lightweight audio and image classifiers on the Nano BLE.
        It supports multi-tenant access and operates with low-power edge inference. Designed for private entry alerts in shared homes.
      </p>
      <div class="project-buttons">
        <a href="https://github.com/your/tinyml-doorbell" target="_blank">GitHub</a>
        <a href="/assets/pdfs/TinyML_Doorbell_Report.pdf" target="_blank">Report</a>
      </div>
    </div>
  </div>

  <div class="project-divider"></div>

  <div class="project-row">
    <div class="project-image-wrapper">
      <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank" rel="noopener noreferrer">
        <img src="/assets/images/Plateperfect.jpg" alt="PlatePerfect" class="project-image">
      </a>
    </div>
    <div class="project-text">
      <h3>Smart Doorbell with TinyML</h3>
      <p>
        PlatePerfect is a computer vision-powered system designed to ensure consistency and quality in restaurant food presentation.
        Using a YOLOv8-nano model fine-tuned on the UECFOODPIX dataset (10,000+ labeled images), the system segments and classifies
        ingredients on plated dishes in real time. Deployed through an iPad app with an external camera, the model achieved over
        68% precision and recall across 101 food classes. By automating visual inspection, PlatePerfect helps reduce manual
        quality assurance effort and improves consistency across restaurant chains.
      </p>
      <div class="project-buttons">
        <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank">GitHub</a>
        <a href="/assets/pdfs/Does_the_plate_look_correct.pdf" target="_blank">Report</a>
      </div>
    </div>
  </div>

  <div class="project-divider"></div>

  <div class="project-row even-row">
    <div class="project-image-wrapper">
      <a href="https://github.com/your/tinyml-doorbell" target="_blank" rel="noopener noreferrer">
        <img src="/assets/images/profile.jpg" alt="Smart Doorbell" class="project-image">
      </a>
    </div>
    <div class="project-text">
      <h3>March Madness</h3>
      <p>
        This project uses knowledge distillation to deploy lightweight audio and image classifiers on the Nano BLE.
        It supports multi-tenant access and operates with low-power edge inference. Designed for private entry alerts in shared homes.
      </p>
      <div class="project-buttons">
        <a href="https://github.com/your/tinyml-doorbell" target="_blank">GitHub</a>
        <a href="/assets/pdfs/TinyML_Doorbell_Report.pdf" target="_blank">Report</a>
      </div>
    </div>
  </div>

  <div class="project-divider"></div>

  <div class="project-row">
    <div class="project-image-wrapper">
      <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank" rel="noopener noreferrer">
        <img src="/assets/images/Plateperfect.jpg" alt="PlatePerfect" class="project-image">
      </a>
    </div>
    <div class="project-text">
      <h3>Gene Regulatory Network Prediction</h3>
      <p>
        PlatePerfect is a computer vision-powered system designed to ensure consistency and quality in restaurant food presentation.
        Using a YOLOv8-nano model fine-tuned on the UECFOODPIX dataset (10,000+ labeled images), the system segments and classifies
        ingredients on plated dishes in real time. Deployed through an iPad app with an external camera, the model achieved over
        68% precision and recall across 101 food classes. By automating visual inspection, PlatePerfect helps reduce manual
        quality assurance effort and improves consistency across restaurant chains.
      </p>
      <div class="project-buttons">
        <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank">GitHub</a>
        <a href="/assets/pdfs/Does_the_plate_look_correct.pdf" target="_blank">Report</a>
      </div>
    </div>
   </div>



</div>
