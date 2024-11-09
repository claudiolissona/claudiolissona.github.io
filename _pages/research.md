---
page_id: research
layout: page
permalink: /research/
title: research
description:
subtitle: 
nav: true
nav_order: 1
---

<!-- Styles for collapsible sections -->
<style>
  .projects h2 {
    cursor: pointer;
  }

  #content-2, #content-1, #abstract-2 {
    display: none;
  }

  .b {
    font-weight: bold;
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

  #abstract-2 {
    display: none;
    padding-left: 30px;
    line-height: 12pt;
    font-size: 10pt;
    margin-top: 20px; /* Space between "Abstract" and the abstract content */
  }

  #content-2 {
    margin-top: 20px;
  }
</style>

<!-- PROJECTS SECTION -->
<div class="projects">
  <a id="toggle-content-2" href="javascript:void(0);" onclick="toggleVisibility('content-2')">
    <h2 class="category">
      <i class="fa-solid fa-chevron-down fa-2xs"></i> working papers
    </h2>
  </a>
</div>

<!-- WORKING PAPERS -->
<div id="content-2">
  <div style="margin: 0; padding: 0; position: relative;">
    <div style="display: inline-block; padding-left: 30px; line-height: 16pt;">
      <span><i>Measuring the Euro Area Output Gap</i>, joint with 
        <a href="https://www.barigozzi.eu/Home.html"><i>Matteo Barigozzi</i></a> and 
        <a href="https://sites.google.com/site/lucianimatteo/"><i>Matteo Luciani</i></a>
      </span>
    </div>
    <!-- ABSTRACT -->
    <div class="abstract-container">
      <div class="abstract-link">
        <a href="javascript:void(0);" id="toggle-abstract-2" onclick="toggleAbstract('abstract-2')">
          <i class="fa-solid fa-chevron-right fa-2xs"></i> <i>Abstract</i>
        </a>
      </div>
      <div id="abstract-2">
        Text
        <br>
        <div class="b">
          <b>Keywords:</b> output gap, factor models, large-dimensional data, non-stationarity, COVID19
        </div>
      </div>
    </div>
  </div>
</div>

<!-- WORK IN PROGRESS SECTION -->
<div class="projects">
  <a id="toggle-content-1" href="javascript:void(0);" onclick="toggleVisibility('content-1')">
    <h2 class="category">
      <i class="fa-solid fa-chevron-down fa-2xs"></i> Work in Progress
    </h2>
  </a>
</div>

<div id="content-1">
  <!-- Content for 'Work in Progress' -->
</div>

<!-- JavaScript for collapsible sections -->
<script>
  function toggleVisibility(id) {
    const element = document.getElementById(id);
    element.style.display = element.style.display === "none" ? "block" : "none";
  }

  function toggleAbstract(id) {
    const element = document.getElementById(id);
    element.style.display = element.style.display === "none" ? "inline-block" : "none";
  }
</script>

<!-- FontAwesome Icons -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
