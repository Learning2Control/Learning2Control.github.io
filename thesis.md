---
layout: default
title: "Master's Thesis Proposals"
permalink: /thesis
---

<style>
  #master_thesis ul > li {
    margin-bottom: 1.5em;
  }
</style>

<section id="master_thesis">
  <h2>2025</h2>
  <ul>
  
    <li>
      <strong>Twin-embedded MPC for longitudinal/lateral vehicle control</strong><br><br>
      Development of a high-fidelity, physics-based vehicle dynamics simulator in <a href="https://modelica.org/">Modelica</a>/<a href="https://www.3ds.com/it/products/catia/dymola">Dymola</a>, integrated with a digital twin for predictive control tasks.<br><br>
      <strong>Key question: Can we reliably initialize a simulator using observed vehicle states?</strong><br><br>
      <strong>Tools & Skills:</strong> Modelica/Dymola, Python, Matlab, Simulink<br><br>
      <ul>
        <li><em>Development of physics-based digital twin</em></li>
        <li><em>Integration with Model Predictive Control frameworks</em></li>
        <li><em>Development of black-box non-linear controller (e.g., <a href="https://github.com/bayesian-optimization/BayesianOptimization">Bayesian Optimization [BO]</a>)</em></li>
        <li><em>Testing in simulation</em></li>
      </ul>
      <div style="text-align: center;">
    <img src="assets/images/BO-controller-run_20250514_154614.png" alt="simulation" style="height: 600px; width: 600px;" />
    <p style="margin-top: 0.5em; font-style: italic; color: #555;">
    Cruise control application – Bayesian-based throttle controller.
  </p>
    </div>
    </li>

    <li>
      <strong>Man-in-the-Middle (MiTM) Attack Detection [Cybersecurity/ML]</strong><br><br>
      Development of detection algorithms against MiTM attacks on control systems, focusing on resilient predictive controllers.<br><br>
      <strong>Tools & Skills:</strong> <a href="https://www.kali.org/">Kali Linux</a>, Python, <a href="https://pytorch.org/">PyTorch</a>/<a href="https://www.tensorflow.org/">TensorFlow</a>, <a href="https://www.wireshark.org/">Wireshark</a>, Matlab, Simulink<br><br>
      <ul>
        <li><em>Experimental deployment on actual networks</em></li>
        <li><em>In-depth study of industrial communication protocols</em></li>
        <li><em>Development of ML-based intrusion detection algorithms</em></li>
        <li><em>Design and testing of resilient predictive controllers under attack</em></li>
      </ul>
      <div style="text-align: center;">
    <img src="assets/images/mitm_image.png" alt="mitm" style="height: 600px; width: 600px;" />
    <p style="margin-top: 0.5em; font-style: italic; color: #555;">
    Man-in-the-Middle - Let's detect it!
  </p>
    </div>
    </li>

  </ul>
</section>
