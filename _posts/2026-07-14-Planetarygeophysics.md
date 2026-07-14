---
layout: post
title:  "Beyond Earth: Introducing PlanetaryGeophysics"
excerpt: "An open-source toolkit for exploring the topography, seismicity, and magnetic fields of the Solar System."
date:   2026-07-14
categories: [Research, Open-Source]
tags: [PlanetaryScience, Geophysics, Python, Mars, InSight, OpenData]
comments: true
feature: assets/img/471267002-853df9dc-2fb6-4330-99ae-d44a5dc64988.png
---   

<p align="center">
  <a href="https://aradfarahani.github.io/PlanetaryGeophysics/mars_globe.html">
    <img src="https://github.com/user-attachments/assets/8bb1dda1-6f56-4870-84b5-16c6d14fde09" alt="3D Mars Globe Preview" width="300"/>
  </a>
</p>

While much of my work focuses on the geophysical complexities of our own planet, the vast datasets returning from our neighboring worlds offer a unique opportunity to apply modern data science to planetary exploration. Today, I am thrilled to officially introduce **PlanetaryGeophysics**.

**PlanetaryGeophysics** is an open-source research initiative designed to bridge the gap between raw planetary mission data and actionable scientific visualization. Whether you are a researcher studying planetary interiors or a space enthusiast, these tools provide a gateway to understanding the tectonics and surface processes of bodies beyond Earth.

### 🌍 The Star Feature: Interactive Mars 3D
One of the core highlights of this project is our **3D Interactive Mars Globe**. Built to be high-performance and accessible viaMarsquake Catalog:** Real-time visualization of seismic events recorded by **NASA’s InSight mission (SEIS)**.



👉 **[Explore the Interactive Mars Globe Live](https://aradfarahani/PlanetaryGeophysics/)**

### 📡 Integrated Scientific Data Sources
The power of this toolkit lies in its integration of multi-mission data. We have processed and unified several key datasets:
*   **Mars Topography (MOLA):** High-resolution elevation data processed via GDAL.
*   **Seismic Events:** The Marsquake catalog from the IRIS Data Portal (`v14`).
*   **Magnetic Field Dynamics:** Processing hundreds of CDF files from the **MAVEN** spacecraft.
*   **Mars Gravity Model 2011 (mgm2011):** For interior structure analysis.

### ⚙️ The Technical Core
True to my commitment to open science, the project is built entirely on a Python-based stack, making it easy for the community to contribute and extend:
*   **Geospatial Processing:** GDAL and Rasterio for handling planetary imagery.
*   **Visualization:** Plotly and Jupyter Notebooks for interactive analysis.
*   **Data Handling:** NumPy and Pandas for high-frequency magnetic and seismic data.

### 🚀 Get Involved
This project is released under the **MIT License**, and I strongly encourage the community to star the repo, report issues, or contribute new modules for other planetary bodies like Europa or Titan.

*   **GitHub Repository:** [aradfarahani/PlanetaryGeophysics](https://github.com/aradfarahani/PlanetaryGeophysics)
*   **Documentation & Live Site:** [PlanetaryGeophysics Portal](https://aradfarahani.github.io/PlanetaryGeophysics/)

Let’s keep exploring the Earth—and everything beyond it. 🌌🔭
