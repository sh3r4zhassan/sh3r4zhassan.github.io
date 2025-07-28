---
layout: default
title: Projects
---

<style>
  .project-row {
    display: flex;
    align-items: flex-start;
    gap: 2em;
    margin: 3em 0;
    flex-wrap: wrap;
  }

  .project-row:nth-of-type(even) {
    flex-direction: row-reverse;
  }

  .project-text {
    flex: 1;
    min-width: 250px;
  }

  .project-image-wrapper {
    flex: 1;
    max-width: 300px;
  }

  .project-image {
    width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
    transition: transform 0.2s ease;
  }

  .project-image:hover {
    transform: scale(1.03);
  }

  .project-divider {
    border-top: 1.5px dashed #bbb;
    margin: 2.5em 0;
  }

  .project-buttons {
    margin-top: 0.8em;
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
    border: 1px solid #ccc;
    box-shadow: 0 1px 4px rgba(0,0,0,0.05);
    transition: background-color 0.2s, color 0.2s;
  }

  .project-buttons a:hover {
    background-color: #e6e6e6;
    color: #0077cc;
  }

  @media (max-width: 768px) {
    .project-row {
      flex-direction: column !important;
    }

    .project-image-wrapper, .project-text {
      max-width: 100%;
    }
  }
</style>

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
      quality assurance effort, streamline operations, and improve customer satisfaction.
    </p>
    <div class="project-buttons">
      <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank" rel="noopener noreferrer">GitHub</a>
      <a href="/assets/pdfs/Does_the_plate_look_correct.pdf" target="_blank" rel="noopener noreferrer">Report</a>
    </div>
  </div>
</div>

<div class="project-divider"></div>

<div class="project-row">
  <div class="project-image-wrapper">
    <a href="https://github.com/your/tinyml-doorbell" target="_blank" rel="noopener noreferrer">
      <img src="/assets/images/doorbell.png" alt="Smart Doorbell" class="project-image">
    </a>
  </div>
  <div class="project-text">
    <h3>Smart Doorbell with TinyML</h3>
    <p>
      Deployed multi-tenant models using knowledge distillation to enable low-power audio and visual classification on the Arduino Nano BLE Sense. 
      The system recognizes visitors through real-time alerts and image/audio inference on-device without sending data to the cloud.
    </p>
    <div class="project-buttons">
      <a href="https://github.com/your/tinyml-doorbell" target="_blank" rel="noopener noreferrer">GitHub</a>
      <a href="/assets/pdfs/TinyML_Doorbell_Report.pdf" target="_blank" rel="noopener noreferrer">Report</a>
    </div>
  </div>
</div>

<div class="project-divider"></div>

<!-- Continue structure for other projects -->


<!-- Repeat structure above for other projects like Vizwhiz, Gene Regulatory Network, etc. -->

<!-- 
<div class="project-divider"></div>

<div class="project-row">
  <div class="project-image-wrapper">
    <a href="https://github.com/your/vizwhiz" target="_blank" rel="noopener noreferrer">
      <img src="/assets/images/vizwhiz.png" alt="Vizwhiz" class="project-image">
    </a>
  </div>
  <div class="project-text">
    <h3>Vizwhiz</h3>
    <p>Visual analytics toolkit for interactive data visualization and exploration. Add more details here.</p>
  </div>
</div>

<div class="project-divider"></div>

<div class="project-row">
  <div class="project-image-wrapper">
    <a href="https://github.com/your/grn" target="_blank" rel="noopener noreferrer">
      <img src="/assets/images/grn.png" alt="Gene Regulatory Network" class="project-image">
    </a>
  </div>
  <div class="project-text">
    <h3>Gene Regulatory Network Prediction</h3>
    <p>Deep learning-based inference of gene regulation using transcriptional profiles. Add more details here.</p>
  </div>
</div>

<div class="project-divider"></div>

<div class="project-row">
  <div class="project-image-wrapper">
    <a href="https://github.com/your/marchmadness" target="_blank" rel="noopener noreferrer">
      <img src="/assets/images/marchmadness.png" alt="March Madness Predictor" class="project-image">
    </a>
  </div>
  <div class="project-text">
    <h3>March Madness Prediction Network</h3>
    <p>Built a neural network to predict NCAA tournament outcomes based on historical data and stats.</p>
  </div>
</div>

<div class="project-divider"></div> -->
