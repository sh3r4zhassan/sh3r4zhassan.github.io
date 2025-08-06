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
    transform: scale(1.20);
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
<h2 style="margin-bottom: 1em; font-size: 2.2em; text-align: center;">Selected Research</h2>

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/Skinspex.png" alt="SkinSpex" class="research-image">
    </div>
    <div class="research-text">
      <h3>SkinSpex: A Portable Speckle Imaging System</h3>
      <p>
        SkinSpex is a compact, low-cost  system for non-contact monitoring of heart rate, respiration, perfusion, and structural skin features such as piloerection through laser speckles. Built on a Raspberry Pi Zero 2 with a multi-wavelength laser setup (560, 750, and 930 nm), the system is designed for use in everyday and point-of-care settings. I led the design and development of the full pipeline, including hardware, embedded software, and real-time speckle analysis and validated its ability to capture acute physiological changes. The work demonstrates the potential of speckle imaging for comprehensive, wearable health monitoring in real-world environments.
      </p>
      <div class="research-buttons">
        <a href="#">Paper</a>
      </div>
    </div>
  </div>

  <div class="research-divider"></div>

  <div class="research-row even-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/Puff.png" alt="PuffEM" class="research-image">
    </div>
    <div class="research-text">
      <h3>PuffEM: An E-cigarette Sleeve for Estimating User Nicotine Intake</h3>
      <p>
        PuffEM is a low-power, sensor-driven system designed to detect and analyze vaping behavior on electronic nicotine delivery systems (ENDS). By combining magnetometer, touch, and IMU sensors, it enables reliable estimation of puff timing, duration, and intensity, overcoming the limitations of gesture based and self reported methods. The system supports multidevice compatibility and was validated through both lab testing and in-wild studies, capturing over 750 puffs. My contributions focused on the hardware design, sensor integration and complete embedded firmware development to support efficient, real-time sensing across different ENDS devices.
      </p>
      <div class="research-buttons">
        <a href="#puffem-paper">Paper</a>
      </div>
    </div>
  </div>


  <div class="research-divider"></div>

  <div class="research-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/STEF.jpg" alt="STEF-DHNET" class="research-image">
    </div>
    <div class="research-text">
      <h3>STEF-DHNet: External Factors Based Deep Hybrid Network for Enhanced Taxi Demand Prediction</h3>
      <p>
        STEF-DHNet is a deep learning framework for predicting regional ride-hailing demand by capturing complex spatiotemporal patterns influenced by factors like time of day, weather, and location. The model combines Convolutional Neural Networks and LSTMs to integrate external features and forecast demand trends across urban grids. Unlike traditional models, STEF-DHNet is designed to maintain high accuracy over long periods without retraining, making it more suitable for real-world deployment. I designed, implemented, and evaluated the full pipeline, including model architecture, feature engineering, and performance benchmarking across three large-scale datasets.
      </p>
      <div class="research-buttons">
        <a href="#stef-paper">Paper</a>
      </div>
    </div>
  </div>


  <div class="research-divider"></div>

  <div class="research-row even-row">
    <div class="research-image-wrapper">
      <img src="/assets/images/Tiny.png" alt="TinyML Benchmarking" class="research-image">
    </div>
    <div class="research-text">
      <h3>TinyMLBench: Benchmarking and Optimizing ML for Microcontrollers</h3>
      <p>
        This work explores the challenges of deploying machine learning models on microcontrollers and proposes a benchmarking framework tailored for TinyML applications. Focusing on image classification and wake word detection, the project evaluates a range of models including ResNet, MobileNetV1, TinyCNN, and a custom teacher-student model, across optimization techniques like Post-Training Quantization and Quantization Aware Training. Using TensorFlow Lite Micro and deploying on the Arduino Nano 33 BLE Sense, the study highlights tradeoffs between model accuracy and memory footprint, and demonstrates how carefully selected architectures and optimizations can enable practical, on-device intelligence in resource-constrained environments.
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
      <h3>RKF-ELM: Lightweight Heart Rate Estimation Using Kalman-Aided Extreme Learning</h3>
      <p>
        This work explores a resource-efficient approach to heart rate monitoring from photoplethysmography (PPG) signals using a hybrid framework that combines an Extreme Learning Machine (ELM) with robust Kalman filtering. The system eliminates the need for auxiliary sensors and large scale neural networks, enabling accurate HR estimation from single channel wrist PPG, even in the presence of motion artifacts. Evaluated on IEEE and PPG-DaLiA datasets, the approach outperforms several deep learning baselines in both accuracy and computational efficiency. Its low parameter count and fast inference make it well suited for on-device deployment in wearable health monitors.
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
      <h3>Robustness in Heart Rate Estimation: Distribution Based Attacks on PPG Time Series Models</h3>
      <p>
        This work investigates the vulnerability of heart rate estimation models to adversarial perturbations in photoplethysmography (PPG) time series data. We propose two new white-box attacks—Fast Distribution Attack (FDA) and Filtered Distribution Alpha Attack (FDAA) that strategically disrupt model outputs by targeting the most influential signal regions. Evaluated on IEEE and PPG-DaLiA datasets, these attacks consistently degrade the performance of both deep CNN-BiLSTM models and resource efficient ELMs, highlighting critical robustness gaps in wearable HR systems.
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
      <h3>Signal Recovery from Motion: A Framework for Cleansing Wrist Worn PPG"</h3>
      <p>
        This work presents a motion artifact removal framework for wearable photoplethysmography (PPG) signals acquired from sensors like the MAXREFDES103. The system classifies artifacts into far-wrist and near-wrist motions using statistical features (skewness and kurtosis), then applies customized denoising techniques: averaging for low-intensity motions and a combination of adaptive and notch filters for high intensity artifacts. This tiered approach improves both signal clarity and processing efficiency. Evaluated across multiple motion types and subjects, the method significantly reduces noise while preserving physiological features like R-R intervals and breathing trends, enabling more accurate heart rate and respiratory monitoring in real-world wearable settings.
      </p>
      <div class="research-buttons">
        <a href="#">Blog</a>
      </div>
    </div>
  </div>
</div>



<div class="research-container">
<h2 style="margin-bottom: 1em; font-size: 2em; text-align: center;">Publications</h2>

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