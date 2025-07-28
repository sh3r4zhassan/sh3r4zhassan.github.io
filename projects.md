---
layout: default
title: Projects
---

<style>
  .project-row {
    display: flex;
    align-items: center;
    gap: 2em;
    margin: 3em 0;
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;
    flex-wrap: wrap;
  }

  .project-row:nth-child(even) {
    flex-direction: row-reverse;
  }

  .project-text {
    flex: 1;
  }

  .project-text h3 {
    margin-bottom: 0.5em;
  }

  .project-text p {
    margin: 0;
    font-size: 0.95rem;
  }

  .project-image-wrapper {
    flex: 1;
    max-width: 400px;
  }

  .project-image {
    width: 100%;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.06);
    transition: transform 0.2s ease;
  }

  .project-image:hover {
    transform: scale(1.02);
  }

  .project-divider {
    max-width: 1200px;
    margin: 2em auto;
    border-top: 1.5px dotted #f1f1f1;
  }

  @media (max-width: 768px) {
    .project-row {
      flex-direction: column !important;
    }

    .project-image-wrapper {
      max-width: 100%;
    }
  }
</style>

# Research Projects

<div class="project-row">
  <div class="project-image-wrapper">
    <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank" rel="noopener noreferrer">
      <img src="/assets/profile.jpg" alt="PlatePerfect" class="project-image">
    </a>
  </div>
  <div class="project-text">
    <h3>PlatePerfect</h3>
    <p>Trained YOLOv8 to classify and verify plated food items in restaurant settings.</p>
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
    <p>Deployed multi-tenant models using knowledge distillation for audio/image inference on Nano BLE.</p>
  </div>
</div>

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

<div class="project-divider"></div>
