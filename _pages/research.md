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
  /* Adjusting the title color to use the theme's global text color */
  .projects h2 {
    cursor: default; /* Remove pointer cursor */
    color: var(--global-text-color, #333); /* Default to the theme's text color */
    font-weight: bold; /* Make titles bold */
    font-size: 1.25rem; /* Adjust font size to match theme */
  }

  /* When the theme is light, use light colors */
  html[data-theme="light"] .projects h2 {
    color: var(--global-text-color, #333); /* Use light theme text color */
  }

  /* When the theme is dark, use dark colors */
  html[data-theme="dark"] .projects h2 {
    color: var(--global-text-color-light, #ccc); /* Use light theme text color for dark mode */
  }

  #content-2, #content-1, #abstract-2 {
    display: block; /* Always visible now */
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
  <h2 class="category">
    Working Papers
  </h2>
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
