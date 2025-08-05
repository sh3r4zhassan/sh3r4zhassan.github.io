---
layout: default
title: Research
---

<style>
  .research-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 1em 1em 1em;
  }

  .research-row {
    display: flex;
    gap: 2em;
    margin-bottom: 4em;
    align-items: stretch;
    justify-content: space-between;
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
    margin-top: 0.5em;
  }

  .research-image {
    width: 100%;
    max-height: 300px;
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
    margin-right: 0.8em;
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
  .research-divider {
    border-top: 1.5px dashed #bbb;
    margin: 2.5em 0;
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
      max-height: none;
    }
  }
</style>

<div class="research-container">
  <h2 style="margin-bottom: 1em; font-size: 1.5em;">Selected Research</h2>

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/Skinspex.png" alt="SkinSpex" class="research-image">
    </div>
    <div class="research-text">
      <h3>SkinSpex</h3>
      <p>
        A laser speckle imaging system for multi-biomarker monitoring (heart rate, breath, perfusion) from skin. Designed a compact setup and validated against reference sensors for accuracy across different wavelengths and skin sites.
      </p>
      <div class="research-buttons">
        <a href="#">Paper</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row even-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/Puff.png" alt="PuffPacket" class="research-image">
    </div>
    <div class="research-text">
      <h3>PuffPacket</h3>
      <p>
        A wearable acoustic sensing system for automatic detection of smoking and vaping episodes. Developed robust ML pipelines using IMU and microphone signals for free-living inference on embedded systems.
      </p>
      <div class="research-buttons">
        <a href="#puffem-paper">Paper</a>
      </div>
    </div>
  </div>


  <div class="research-divider"></div>

  <div class="research-row even-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/STEF.jpg" alt="STEF-DHNET" class="research-image">
    </div>
    <div class="research-text">
      <h3>STEF-DHNet</h3>
      <p>
        Built a deep hybrid network for activity recognition using sequential transformer blocks fused with CNNs. Applied to multimodal human activity datasets and optimized for on-device deployment.
      </p>
      <div class="research-buttons">
        <a href="#stef-paper">Paper</a>
      </div>
    </div>
  </div>


  <div class="research-divider"></div>

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/Tiny.png" alt="TinyML Benchmarking" class="research-image">
    </div>
    <div class="research-text">
      <h3>TinyML Benchmarking for Edge Devices</h3>
      <p>
        Designed a benchmark suite for evaluating classification models on microcontrollers using quantization-aware training. Benchmarked performance, memory, and latency across datasets and deployment targets.
      </p>
      <div class="research-buttons">
        <a href="#">Blog</a>
      </div>
    </div>
  </div>


  <div class="research-divider"></div>

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/ELM.png" alt="PPG HR Estimation" class="research-image">
    </div>
    <div class="research-text">
      <h3>Heart Rate Estimation using RKF & ELM</h3>
      <p>
        Developed a real-time pipeline for heart rate estimation using PPG sensors. Combined recursive Kalman filtering with Extreme Learning Machines for lightweight signal tracking under noise.
      </p>
      <div class="research-buttons">
        <a href="#">Blog</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row even-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/Adversarial.jpeg" alt="HR Robustness" class="research-image">
    </div>
    <div class="research-text">
      <h3>Robustness of HR Estimation</h3>
      <p>
        Evaluated performance of wearable HR estimation pipelines under varying lighting, motion, and sensor conditions. Conducted robustness analysis across 5+ experimental settings to guide model generalizability.
      </p>
      <div class="research-buttons">
        <a href="#">Blog</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/Motionartifacts.png" alt="HR Robustness" class="research-image">
    </div>
    <div class="research-text">
      <h3>PPG Motion Artifacts </h3>
      <p>
        Evaluated performance of wearable HR estimation pipelines under varying lighting, motion, and sensor conditions. Conducted robustness analysis across 5+ experimental settings to guide model generalizability.
      </p>
      <div class="research-buttons">
        <a href="#">Blog</a>
      </div>
    </div>
  </div>
</div>



<div class="research-container">
  <h2 style="margin-top: 3em; font-size: 1.5em;">Publications</h2>

  <ul style="font-size: 1.05em; line-height: 1.6; margin-top: 1em;">
    <li id="puffem-paper">
      <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=aNlZoQwAAAAJ&citation_for_view=aNlZoQwAAAAJ:u-x6o8ySG0sC" target="_blank" style="color: #1a0dab; text-decoration: none;">
        <em>“PuffEM: An E-cigarette Sleeve for Estimating User Nicotine Intake.”</em>
      </a>
      Yiyang Wang, Rishabh Goel, <strong>Sheraz Hassan</strong>, Taegen J Doscher, Shilin Wang, Lexington Allen Whalen, Aditya S Gandhi, Yaman S Sangar, Alex Cabral, Xuhai Xu, Josiah Hester, Alexander T Adams.  
      <span>ACM/IEEE Conference on Connected Health: Applications, Systems and Engineering Technologies (CHASE), 2025.</span>
    </li>
    <li id="stef-paper">
      <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=aNlZoQwAAAAJ&citation_for_view=aNlZoQwAAAAJ:u5HHmVD_uO8C" target="_blank" style="color: #1a0dab; text-decoration: none;">
        <em>“STEF-DHNet: Spatiotemporal External Factors Based Deep Hybrid Network for Enhanced Long-Term Taxi Demand Prediction.”</em>
      </a>
      <strong>Sheraz Hassan</strong>, Muhammad Tahir, Momin Uppal, Zubair Khalid, Ivan Gorban, Selim Turki.  
      <span><em>*arXiv preprint arXiv:2306.14476*</em>, 2023.</span>
    </li>
  </ul>
</div>