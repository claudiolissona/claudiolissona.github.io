---
page_id: data
layout: page
permalink: /data/
title: Data
description:
subtitle: 
nav: true
nav_order: 3 # Adjust based on desired menu position
---

<!-- Styles for collapsible sections -->
<style>
  .projects h2.category {
    cursor: default;
    font-weight: bold;
    font-size: 1.5rem;
  }

  html[data-theme="light"] .projects h2.category {
    color: var(--global-theme-color, #9b59b6) !important;
  }

  html[data-theme="dark"] .projects h2.category {
    color: var(--global-theme-color, #00bcd4) !important;
  }

  #content-1 {
    margin-top: 20px;
    margin-bottom: 20px;
  }

  .work-in-progress {
    margin-bottom: 15px;
  }

  .line-item {
    padding-left: 0px;
    line-height: 16pt;
  }
  
  .small-text {
    font-size: 0.8rem; /* Adjust the value as needed */
  }
</style>

<!-- DATA SECTION -->
<div class="projects">
  <h2 class="category">
    EA-MD-QD
  </h2>
</div>

<div id="content-1">
  <div class="work-in-progress">
    <div class="line-item">
        <div> EA-MD-QD is a collection of large monthly and quarterly EA and EA member countries datasets for macroeconomic analysis. </div>
        <div style="margin-bottom: 10px;"> The EA member countries covered are: AT, BE, DE, EL, ES, FR, IE, IT, NL, PT. </div>
        <div> The dataset is updated regularly and is publicly available under the license CC-BY-NC. </div> <a href="https://creativecommons.org/licenses/by-nc/4.0/" target="_blank">
        <img src="https://licensebuttons.net/l/by-nc/4.0/88x31.png" alt="CC-BY-NC License"></a>
        <div style="margin-bottom: 10px;"> The dataset with all vintages since December 2023 is available 
              <a href="https://zenodo.org/records/14018642">here</a>. </div>
        <div style="margin-bottom: 5px;"> If you find the data useful, and decide to use it for your own research, please cite: </div>
        <div> <span><i>Large datasets for the Euro Area and its member countries and the dynamic effects of the common monetary policy</i> </div>
        <div class="small.text;"> M. Barigozzi, C. Lissona, L. Tonni </div> 
        <div class="small.text;"> arXiv, 2024. </div>
    </div>
  </div>
</div>

