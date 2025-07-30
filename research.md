---
layout: default
title: Research
---

<style>
  .research-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2em 1em;
  }

  .research-row {
    display: flex;
    align-items: stretch;
    gap: 2em;
    margin-bottom: 4em;
    flex-wrap: wrap;
  }

  .even-row {
    flex-direction: row-reverse;
  }

  .research-image-wrapper {
    flex: 0 0 30%;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .research-text {
    flex: 0 0 70%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .research-text p {
    text-align: justify;
  }

  .research-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
    transition: transform 0.2s ease;
  }

  .research-image:hover {
    transform: scale(1.03);
  }

  .research-divider {
    border-top: 1.5px dashed #bbb;
    margin: 2.5em 0;
  }

  .research-buttons {
    margin-top: 1em;
  }

  .research-buttons a {
    display: inline-block;
    padding: 0.4em 0.9em;
    background-color: #f1f1f1;
    color: #222;
    font-size: 0.85rem;
    text-decoration: none;
    border-radius: 6px;
    transition: background-color 0.2s;
  }

  .research-buttons a:hover {
    background-color: #ddd;
  }

  @media (max-width: 768px) {
    .research-row {
      flex-direction: column !important;
    }

    .research-image-wrapper,
    .research-text {
      flex: 1 1 100%;
    }

    .research-image {
      height: auto;
    }
  }
</style>

<div class="research-container">

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/skinspex.jpg" alt="SkinSpex" class="research-image">
    </div>
    <div class="research-text">
      <h3>SkinSpex</h3>
      <p>
        A laser speckle imaging system for multi-biomarker monitoring (heart rate, breath, perfusion) from skin. Designed a compact setup and validated against reference sensors for accuracy across different wavelengths and skin sites.
      </p>
      <div class="research-buttons">
        <a href="#">Details</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row even-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/puffpacket.jpg" alt="PuffPacket" class="research-image">
    </div>
    <div class="research-text">
      <h3>PuffPacket</h3>
      <p>
        A wearable acoustic sensing system for automatic detection of smoking and vaping episodes. Developed robust ML pipelines using IMU and microphone signals for free-living inference on embedded systems.
      </p>
      <div class="research-buttons">
        <a href="#">Details</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/tinyml_benchmark.jpg" alt="TinyML Benchmarking" class="research-image">
    </div>
    <div class="research-text">
      <h3>TinyML Benchmarking for Edge Devices</h3>
      <p>
        Designed a benchmark suite for evaluating classification models on microcontrollers using quantization-aware training. Benchmarked performance, memory, and latency across datasets and deployment targets.
      </p>
      <div class="research-buttons">
        <a href="#">Details</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row even-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/stef.jpg" alt="STEF-DHNET" class="research-image">
    </div>
    <div class="research-text">
      <h3>STEF-DHNet</h3>
      <p>
        Built a deep hybrid network for activity recognition using sequential transformer blocks fused with CNNs. Applied to multimodal human activity datasets and optimized for on-device deployment.
      </p>
      <div class="research-buttons">
        <a href="#">Details</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/ppg_hr.jpg" alt="PPG HR Estimation" class="research-image">
    </div>
    <div class="research-text">
      <h3>Heart Rate Estimation using RKF & ELM</h3>
      <p>
        Developed a real-time pipeline for heart rate estimation using PPG sensors. Combined recursive Kalman filtering with Extreme Learning Machines for lightweight signal tracking under noise.
      </p>
      <div class="research-buttons">
        <a href="#">Details</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row even-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/robustness.jpg" alt="HR Robustness" class="research-image">
    </div>
    <div class="research-text">
      <h3>Robustness of HR Estimation</h3>
      <p>
        Evaluated performance of wearable HR estimation pipelines under varying lighting, motion, and sensor conditions. Conducted robustness analysis across 5+ experimental settings to guide model generalizability.
      </p>
      <div class="research-buttons">
        <a href="#">Details</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/activity.jpg" alt="Activity Recognition" class="research-image">
    </div>
    <div class="research-text">
      <h3>Human Activity Sensing</h3>
      <p>
        Designed real-time activity recognition pipeline using IMU and environmental sensors on wrist-worn devices. Implemented gesture-aware filtering and on-device inference to reduce latency and power.
      </p>
      <div class="research-buttons">
        <a href="#">Details</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <h2 style="margin-top: 2em;">Publications</h2>

  <ul style="padding-left: 1.2em; line-height: 1.7;">
    <li><strong>Author1, Sheraz Hassan, Author3.</strong> "Title of the Paper." <em>Conference Name</em>, 2025.</li>
    <li><strong>Sheraz Hassan, Author2.</strong> "Another Publication Title." <em>Journal Name</em>, 2024.</li>
    <li><strong>Sheraz Hassan, Author2.</strong> "Another Publication Title." <em>Journal Name</em>, 2024.</li>
  </ul>

</div>
