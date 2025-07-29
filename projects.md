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
      <img src="/assets/images/Plateperfect.jpg" alt="PlatePerfect" class="project-image">
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
        <a href="/assets/pdfs/PlatePerfect.pdf" target="_blank">Report</a>
      </div>
    </div>
  </div>

  <div class="project-divider"></div>

  <div class="project-row even-row">
    <div class="project-image-wrapper">
        <img src="/assets/images/VizWhiz.png" alt="VizWhiz" class="project-image">
    </div>
    <div class="project-text">
        <h3>VizWhiz: A visualization Wizard</h3>
        <p>
        VizWhiz is an interactive web application built with Streamlit for exploratory data analysis. It allows users to upload and analyze any CSV file, offering real-time visual feedback through over 5 plot types including bar charts, box plots, and histograms. The app includes built-in tools for data cleaning, descriptive statistics, and dimensionality reduction (PCA), making it suitable for both novice and advanced users. Tested on datasets with over 50,000 rows, VizWhiz provides responsive performance and is fully browser-based with no local setup required.
        </p>
        <div class="project-buttons">
        <a href="https://github.com/sh3r4zhassan/VizWhiz" target="_blank">GitHub</a>
        <a href="/assets/pdfs/VizWhiz.pdf" target="_blank">Report</a>
        </div>
    </div>
  </div>


  <div class="project-divider"></div>

  <div class="project-row">
    <div class="project-image-wrapper">
        <img src="/assets/images/EdgeGuard.png" alt="PlatePerfect" class="project-image">
    </div>
    <div class="project-text">
      <h3>EdgeGuard: On-Device Entry System</h3>
      <p>
        This project implements a smart multi-modal door security system using TinyML, integrating both audio and image inputs for secure and efficient on-device inference. Deployed on the Arduino Nano 33 BLE Sense, the system uses a lightweight student model distilled from a larger MobileNetV2-based (α = 0.35) teacher network to detect the presence of a person at the door, achieving 84% image classification accuracy in under 200 KB post-quantized size. Upon detection, the system activates a wake-word listener using a DS-CNN model that operates at 95% accuracy with a compact 46 KB footprint. The system only proceeds to unlock the door if a valid voice command is received, ensuring secure, energy-efficient access control entirely on-device.
      </p>
      <!-- <div class="project-buttons"> -->
        <!-- <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank">GitHub</a> -->
        <!-- <a href="/assets/pdfs/Does_the_plate_look_correct.pdf" target="_blank">Report</a> -->
      <!-- </div> -->
    </div>
  </div>

  <div class="project-divider"></div>

  <div class="project-row even-row">
    <div class="project-image-wrapper">
        <img src="/assets/images/GRN.png" alt="Smart Doorbell" class="project-image">
    </div>
    <div class="project-text">
      <h3>Gene Regulatory Network Prediction</h3>
      <p>
        This project reconstructs Gene Regulatory Networks (GRNs) from simulated gene expression data using supervised machine learning models. With the goal to predict transcription factor (TF)-target gene interactions and evaluate the accuracy of reconstructed GRNs against known bipartite ground truth networks, I designed a hybrid model combining Random Forest, Lasso Regression, and Neural Networks achieving up to 10% higher AUROC than individual models and consistently outperformed baseline GRN inference across all conditions.
      </p>
      <div class="project-buttons">
        <a href="https://github.com/sh3r4zhassan/Gene_Regulatory_Network_Prediction" target="_blank">GitHub</a>
        <!-- <a href="/assets/pdfs/TinyML_Doorbell_Report.pdf" target="_blank">Report</a> -->
      </div>
    </div>
  </div>

  <div class="project-divider"></div>

<div class="project-row">
  <div class="project-image-wrapper">
    <img src="/assets/images/SoundIQ.png" alt="Sound Prediction & Cancellation" class="project-image">
  </div>
  <div class="project-text">
    <h3>SoundIQ: A Sound Prediction & Cancellation System</h3>
    <p>
      Built a two-stage pipeline for environmental sound classification and real-time active noise cancellation. A custom 7-layer CNN—comprising three convolutional layers, max-pooling, dropout, and dense layers—was trained on the UrbanSound8K dataset and achieved 85.75% accuracy on 10 environmental classes. Based on classification, a Python-Simulink interface selected pre-trained adaptive filters for cancellation. The full system visualizes and analyzes input vs. output sound pressure levels, enabling context-aware suppression of urban and environmental noise.
    </p>
    <div class="project-buttons">
      <a href="https://github.com/sh3r4zhassan/Sound-Prediction-and-Cancellation-Model" target="_blank">GitHub</a>
    </div>
  </div>
</div>

  <div class="project-divider"></div>

  <div class="project-row even-row">
    <div class="project-image-wrapper">
        <img src="/assets/images/MarchMadness.png" alt="PlatePerfect" class="project-image">
    </div>
    <div class="project-text">
      <h3>March Madness Prediction Network</h3>
      <p>
        Built a deep learning pipeline to predict NCAA March Madness basketball outcomes using historical box score data and time-series models. We experimented with MLPs, CNNs, LSTMs, and Transformers, evaluating performance across 60,000+ matchups. Our CNN model achieved the highest accuracy (63.4%) and F1-score (0.66) across validation, while hybrid CNN-LSTM models showed strong generalization. Tested on the 2025 bracket, the models correctly predicted up to 13 of 32 first-round games and revealed challenges in accounting for team seeding and strength of schedule.
      </p>
      <div class="project-buttons">
        <!-- <a href="https://github.com/sh3r4zhassan/PlatePerfect" target="_blank">GitHub</a> -->
        <a href="/assets/pdfs/March_Madness.pdf" target="_blank">Report</a>
      </div>
    </div>
   </div>


</div>
