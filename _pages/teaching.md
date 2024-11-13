---
page_id: teaching
layout: page
permalink: /teaching/
title: Teaching
description:
subtitle: 
nav: true
nav_order: 2
---

<!-- Custom Styles for Teaching Page -->
<style>
  /* Styling for the Teaching Sections */
  .teaching-entry {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 30px;
    padding-bottom: 10px;
    border-bottom: 2px solid var(--global-theme-color, #9b59b6); /* Line below each entry */
  }

  /* Course Title */
  .teaching-entry-title {
    font-size: 1.5rem;
    font-weight: bold;
    color: var(--global-theme-color, #9b59b6);
  }

  /* Course Description */
  .teaching-entry-details {
    font-size: 1rem;
    flex-grow: 1;
    margin-left: 20px;
    line-height: 1.6;
    color: var(--global-text-color, #333);
  }

  /* Align Title to the Right */
  .teaching-entry-title {
    text-align: right;
    min-width: 200px;
  }

  /* Adjust colors for Dark Theme */
  html[data-theme="dark"] .teaching-entry-title {
    color: var(--global-theme-color, #00bcd4);
  }

  html[data-theme="dark"] .teaching-entry-details {
    color: var(--global-text-color, #ddd);
  }
</style>

<!-- Teaching Content -->
<div class="teaching-entry">
  <div class="teaching-entry-title">Course Title 1</div>
  <div class="teaching-entry-details">
    <p>Details about the course, including topics covered, teaching activities, or other relevant information.</p>
  </div>
</div>

<div class="teaching-entry">
  <div class="teaching-entry-title">Course Title 2</div>
  <div class="teaching-entry-details">
    <p>Additional information about this course or workshop, including key takeaways and objectives.</p>
  </div>
</div>

<div class="teaching-entry">
  <div class="teaching-entry-title">Course Title 3</div>
  <div class="teaching-entry-details">
    <p>Description of another course, such as tutorials or special lectures, and relevant details for students.</p>
  </div>
</div>
