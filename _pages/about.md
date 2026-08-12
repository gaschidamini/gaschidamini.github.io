---
permalink: /
title: "Gustavo Aschidamini"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* Homepage-only heading sizes (this CSS loads only on the home page) */
.page__title { font-size: 1.15em; }
#selected-research { font-size: 1.15em; font-weight: normal; }
/* Intro text matches the publication font size */
.page__content > p { font-size: 14px; }
</style>

I am a PhD candidate in <a href="https://www.sfu.ca/fas/schools/sustainable-energy-engineering.html">Sustainable Energy Engineering</a> at Simon Fraser University and a member of the <a href="https://www.sfu.ca/fas/research/fas-research-labs/power-and-energy-systems/">Power & Energy Systems Research Group</a>, advised by <a href="https://scholar.google.com/citations?user=7Ef6qOIAAAAJ&hl=en">Dr. Mariana Resener</a>. My research interests are in power systems operation and expansion.



<h2 id="selected-research">Selected research</h2>

<div class="research-item">
  <div class="research-image">
    <img src="/images/figure_rl_hps.png"
         alt="Weather-adaptive reinforcement learning framework for heat pump control">
  </div>

  <div class="research-content">
    <h3>
      <a href="https://www.sciencedirect.com/science/article/pii/S0196890426009842">Weather-adaptive reinforcement learning framework for heat pump control under time-of-use tariffs</a>
    </h3>

    <p class="research-authors">
      <strong>Gustavo L. Aschidamini</strong>, Bradley A. Reinholz, Malcolm S. Metcalfe, Xue Bin Peng, Mariana Resener
    </p>

    <p class="research-venue">
      <em>Energy Conversion and Management</em>, 2026
    </p>

    <p class="research-desc">
      RL framework that learns how to control a variable-speed compressor heat pump for space heating to reduce electricity costs under time-of-use electricity prices while adapting to varying weather conditions.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="/images/figure_review_hps.gif"
         alt="Control of heat pumps for energy flexibility in distribution networks">
  </div>

  <div class="research-content">
    <h3>
      <a href="https://doi.org/10.1109/ACCESS.2025.3569761">Comprehensive Review on the Control of Heat Pumps for Energy Flexibility in Distribution Networks</a>
    </h3>

    <p class="research-authors">
      <strong>Gustavo L. Aschidamini</strong>, Mina Pavlovic, Bradley Reinholz, Malcolm S. Metcalfe, Taco Niet, Mariana Resener
    </p>

    <p class="research-venue">
      <em>IEEE Access</em>, 2025
    </p>

    <p class="research-desc">
      Review of existing methods for controlling heat pumps to provide energy flexibility under time-varying electricity prices, direct load control, and increased self-consumption.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="/images/figure_pv_disaggregation.png"
         alt="Practical method for behind-the-meter solar PV disaggregation">
  </div>

  <div class="research-content">
    <h3>
      <a href="https://ieeexplore.ieee.org/document/11199029">Practical Method for Behind-the-Meter Solar PV Disaggregation</a>
    </h3>

    <p class="research-authors">
      Dionathan S. Scheid, <strong>Gustavo L. Aschidamini</strong>, Eduardo S. Finck, Bibiana P. Ferraz, Sérgio Haffner, Luís Alberto Pereira
    </p>

    <p class="research-venue">
      <em>IEEE Access</em>, 2025
    </p>

    <p class="research-desc">
      Energy disaggregation method that operates solely on monthly net energy imports and exports, estimating behind-the-meter energy consumption and photovoltaic generation by leveraging reference generation profiles and typical load curves for end-users.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="/images/figure_framework_reliability.png"
         alt="Reliability assessment in power distribution systems">
  </div>

  <div class="research-content">
    <h3>
      <a href="https://doi.org/10.3390/en15145073">A Framework for Reliability Assessment in Expansion Planning of Power Distribution Systems</a>
    </h3>

    <p class="research-authors">
      <strong>Gustavo L. Aschidamini</strong>, Gederson A. da Cruz, Mariana Resener, Roberto C. Leborgne, Luis A. Pereira
    </p>

    <p class="research-venue">
      <em>Energies</em>, 2022
    </p>

    <p class="research-desc">
      Method that uses real interruption data from a utility to assess reliability and estimate reliability improvements from expansion alternatives.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-image">
    <img src="/images/figure_review_reliability.png"
         alt="Expansion planning of power distribution systems considering reliability">
  </div>

  <div class="research-content">
    <h3>
      <a href="https://doi.org/10.3390/en15062275">Expansion Planning of Power Distribution Systems Considering Reliability: A Comprehensive Review</a>
    </h3>

    <p class="research-authors">
      <strong>Gustavo L. Aschidamini</strong>, Gederson A. da Cruz, Mariana Resener, Marcelo J. S. Ramos, Luis A. Pereira, Bibiana P. Ferraz, Sérgio Haffner, Panos M. Pardalos
    </p>

    <p class="research-venue">
      <em>Energies</em>, 2022
    </p>

    <p class="research-desc">
      Review of methods that propose distribution network expansion during the planning stage to improve the expected reliability.
    </p>
  </div>
</div>

<div id="zoom-overlay" aria-hidden="true"><span class="close">&times;</span><img alt="zoomed figure"></div>

<script>
(function () {
  var overlay = document.getElementById('zoom-overlay');
  if (!overlay) return;
  var big = overlay.querySelector('img');
  document.querySelectorAll('.research-image img').forEach(function (im) {
    im.addEventListener('click', function () {
      big.src = im.currentSrc || im.src;
      big.alt = im.alt;
      overlay.classList.add('open');
    });
  });
  function closeOverlay() {
    overlay.classList.remove('open');
    big.removeAttribute('src');
  }
  overlay.addEventListener('click', closeOverlay);
  document.addEventListener('keydown', function (e) {
    if (e.key === 'Escape') closeOverlay();
  });
})();
</script>

