---
page_id: research
layout: page
permalink: /research/
title: Research
description:
subtitle: 
nav: true
nav_order: 1
---

<!-- Styles for collapsible sections -->
<style>
  /* Force the title color with more specificity */
  .projects h2.category {
    cursor: default; /* Remove pointer cursor */
    font-weight: bold; /* Make titles bold */
    font-size: 1.5rem; /* Increase font size slightly, more than before but not as large */
  }

  /* When the theme is light, use purple color */
  html[data-theme="light"] .projects h2.category {
    color: var(--global-theme-color, #9b59b6) !important; /* Use the theme's purple color */
  }

  /* When the theme is dark, use light blue/cyan color */
  html[data-theme="dark"] .projects h2.category {
    color: var(--global-theme-color, #00bcd4) !important; /* Use the theme's cyan/light blue color */
  }

  #content-2, #content-1, #abstract-1, #abstract-2 {
    display: block; /* Always visible now */
  }

  .b {
    font-weight: bold;
  }

  .paper {
  margin-bottom: 40px; /* Add space between papers */
  }

  /* Make Abstract stay on top of the dropdown */
  .abstract-container {
    position: relative;
  }

  .abstract-link {
    position: absolute;
    top: 0;
    left: 30px;
    font-size: 11pt;
    cursor: pointer;
  }

  #abstract-1, #abstract-2 {
    display: none;
    padding-left: 30px;
    padding-bottom: 10px; /* Space between abstract text and keywords */
    line-height: 12pt;
    font-size: 10pt;
    margin-top: 20px; /* Space between "Abstract" and the abstract content */
  }

   /* Fix space between Abstract link and text */
  .abstract-container {
    margin-bottom: 10px; /* Adds consistent space above the abstract text */
  }

    /* Add space specifically between abstract text and keywords */
  #abstract-1 div, #abstract-2 div {
    margin-top: 10px; /* Space above keywords section */
  }

  .abstract-container > .abstract-link + #abstract-1,
  .abstract-container > .abstract-link + #abstract-2 {
    margin-top: 20px; /* Fix space immediately after "Abstract" button */
  }
  
  #content-2, #content-1 {
    margin-top: 20px;
    margin-bottom: 20px;
  }

  /* Reduce font size for text inside round brackets */
  .bracket-text {
    font-size: 0.85em; /* Slightly smaller font size */
  }
  
</style>

<!-- PROJECTS SECTION -->
<div class="projects">
  <h2 class="category">
    Working Papers
  </h2>
</div>

<!-- WORKING PAPERS -->
<div id="content-2">
  <div class="paper">
  <div style="margin: 0; padding: 0; position: relative;">
    <div style="display: inline-block; padding-left: 30px; line-height: 16pt;">
      <span><i>Measuring the Euro Area Output Gap</i> (<span class="bracket-text">joint with 
        <a href="https://www.barigozzi.eu/Home.html">Matteo Barigozzi</a> and 
        <a href="https://sites.google.com/site/lucianimatteo/">Matteo Luciani</a></span>)
      </span>
    </div>
    <!-- ABSTRACT -->
    <div class="abstract-container">
      <div class="abstract-link">
        <a href="javascript:void(0);" id="toggle-abstract-1" onclick="toggleAbstract('abstract-1')">
          <i class="fa-solid fa-chevron-right fa-2xs"></i> Abstract
        </a>
      </div>
      <div id="abstract-1">
        We measure the Euro Area (EA) output gap and potential output using a non-stationary dynamic
        factor model estimated on a large dataset of macroeconomic and financial variables. From 2012
        to 2023, we estimate that the EA economy was tighter than the European Commission and the
        International Monetary Fund estimate, suggesting that the slow EA growth is the result of a
        potential output issue, not a business cycle issue. Moreover, we find that credit indicators are
        crucial for pinning down the output gap, as excluding them leads to estimating a lower output
        gap in periods of debt build-up and a higher gap in periods of deleveraging.
        <br>
        <div>
          <b>Keywords:</b> output gap, factor models, large-dimensional data, non-stationarity, COVID19
        </div>
      </div>
    </div>
  </div>
  </div>

  <div class="paper">
  <div style="margin: 0; padding: 0; position: relative;">
    <div style="display: inline-block; padding-left: 30px; line-height: 16pt;">
      <span><i>Large datasets for the Euro Area and its member countries and the dynamic effects of the common monetary policy</i> (<span class="bracket-text">joint with 
        <a href="https://www.barigozzi.eu/Home.html">Matteo Barigozzi</a> and 
        <a href="https://sites.google.com/view/lorenzotonni/home-page?authuser=0">Lorenzo Tonni</a></span>)
      </span>
    </div>
    <!-- ABSTRACT -->
    <div class="abstract-container">
      <div class="abstract-link">
        <a href="javascript:void(0);" id="toggle-abstract-2" onclick="toggleAbstract('abstract-2')">
          <i class="fa-solid fa-chevron-right fa-2xs"></i> Abstract
        </a>
      </div>
      <div id="abstract-2">
        We present and describe a new publicly available large dataset which encompasses quarterly and monthly macroeconomic time series for both         the Euro Area (EA) as a whole and its ten primary member countries. The dataset, which is called EA-MD-QD, includes more than 800 time            series and spans the period from January 2000 to the latest available month. Since January 2024 EA-MD-QD is updated on a monthly basis            and constantly revised, making it an essential resource for conducting policy analysis related to economic outcomes in the EA. To                 illustrate the usefulness of EA-MD-QD, we study the country specific Impulse Responses of the EA wide monetary policy shock by means of           the Common Component VAR plus either Instrumental Variables or Sign Restrictions identification schemes. The results reveal asymmetries           in the transmission of the monetary policy shock across countries, particularly between core and peripheral countries. Additionally, we           find comovements across Euro Area countries' business cycles to be driven mostly by real variables, compared to nominal ones.
        <br>
        <div>
          <b>Keywords:</b> factor models, large-dimensional data, monetary policy, CC-SVAR
        </div>
      </div>
    </div>
  </div>
  </div>
 
</div>


<!-- WORK IN PROGRESS SECTION -->
<div class="projects">
  <h2 class="category">
    Work in Progress
  </h2>
</div>

<div id="content-1">
  <!-- Content for 'Work in Progress' -->
</div>

<!-- JavaScript for Abstract Toggle -->
<script>
  function toggleAbstract(id) {
    const element = document.getElementById(id);
    element.style.display = element.style.display === "none" ? "inline-block" : "none";
  }
</script>

<!-- FontAwesome Icons -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
