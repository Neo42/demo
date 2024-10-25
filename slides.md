---
# You can also start simply with 'default'
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# some information about your slides (markdown enabled)
title: Visual Flux
layout: section
transition: fade-out
overviewSnapshots: true
---

# Visual Flux

<div class="absolute bottom-10">
  <span class="font-700">
    INFLUXUI-PG02
  </span>
</div>

<!--
Thank you respectable representatives from ATSTS, Amali and the teaching team for having us. 
Really previledged and fortunate to be here to present you our solution for the influx ui project. Let's jump right in.
-->

---
layout: section
---

# Problem We Are Solving

<!--
The problem we are trying to solve is that many data analysts or business analysts have to use InfluxDB for analysing time-series data in their daily work but don’t have programming skills or are unfamiliar with the Flux language. Those analysts are the typical users who will use our software. But other than that, because we have implemented screen reader voice-over accessibility on our user interface, our software is also accessible to those who are visually impaired.
-->

---
transition: fade-out
layout: section
---

# Our Users and Their Goals

<!--  
Goals:
* Querying data without writing any code
* Visualizing data in a way that is easy to understand
-->

---
transition: fade-out
layout: section
---

# Design

* ## Minimalism
* ## Customizable 

<!-- 
Frontend team put a lot of thoughts into the design

* Style
  * Minimalism: Minimal distraction
* Customizable Layout, make it your own
  * Multi-panel
  * Toggle panels
  * Sidebar collapse & expand for icon only nodes
  * header w/ three toggles for the panels, resizable
  * Run and pause query execution for real-time query result update
  * Light & Dark theme
 -->

---
transition: fade-out
layout: section
---

# Functionalities

* ## Drag & Drop
* ## Flux Code
* ## Data Preview
* ## Charts
* ## Accessibility for Visually Impaired

<!-- 
* On the side, we have all 5 nodes that we can drag and drop
* If you hesitate and want to withdraw the node, place it outside of the flow panel and it will bounce back with a toast.
* Notice how smooth and beautiful the animation is
* Drop and connect nodes
    * Zoom panel in and out
    * Fit the flow to the view
    * Lock the flow chart and disable modification
    * Mess the flow chart up and auto-align it
    * Reset the flow chart to the initial state

* Nodes
    * Three Selectors
    * Two filters
    * Date range with input and presets
    * Value threshold composition (And & Or)

* Flux query update in real time
  * Syntax highlighting with two themes according to the mode you are in
  * Valid syntax with operator precedence
  
* Click on the run query button to execute the query

* Data Preview
  * row selection
  * Sort by a column ascending or descending
  * pagination
  * Search filter
  * custom column display
  * CSV export

* Charts
  * Line chart
  * Bar chart
  * Area chart 
  * Tooltips with legend
  * Data summary
  * Display name
  * Select which fields you want to display

* Accessibility
  * Equally accessible to the visually impaired
  * Keyboard navigation
  * Screen reader support
  * Inclusive & Equal access to information
-->

---
layout: section
---

# Future Steps

* ## Grafana integration & Better Visualization
* ## Editable Flux Code
* ## Deployment on Cloud
