---
layout: clean
title: "Software"
permalink: /software/
redirect_from:
  - /portfolio/
---

I develop and maintain open-source tools for reproducible neuroimaging.

<div class="feature" markdown="1">
<span class="tag">Featured</span>

## Delineation Helper

<a href="https://github.com/readingroi-workshop-2026/app_manual_delineation_helper"><img class="demo" src="/images/software/delineation-helper.gif" alt="Delineation Helper rotating an inflated and a pial cortical surface together, with reading ROIs and a functional heatmap on the ventral occipitotemporal cortex"></a>

A light, fast, browser-based viewer for delineating ROIs on the cortical surface, built
for the 2026 reading-ROI delineation workshop. It shows FreeSurfer surfaces side by side
(inflated, pial or white) with linked cameras, and overlays a functional heatmap, auto
clusters, atlas labels and manual labels. ROIs are drawn directly on the surface
(Contour · Brush · Erase) and saved as FreeSurfer `.label` files.

* **Delineate**: one subject and hemisphere, every layer toggleable, draw and edit labels
* **Compare**: a reference rater's labels above another rater's, for inter-rater checks
* **Both hemispheres** and **Group** views, with cameras linked across subjects
* Runs in the browser with nothing to install; your data is read locally, never uploaded

<i class="fa-brands fa-github"></i> [Code](https://github.com/readingroi-workshop-2026/app_manual_delineation_helper) ·
<i class="fa-solid fa-quote-right"></i> [DOI 10.5281/zenodo.22044800](https://doi.org/10.5281/zenodo.22044800)
</div>

## Launchcontainers

A Python tool for launching containerized neuroimaging analyses (e.g. RTP2-pipeline,
fMRIPrep) on high-performance computing systems, with BIDS-aware configuration and
reproducible provenance. Presented as a workshop at BrainHack Donostia 2023.<br>
<i class="fa-brands fa-github"></i> [github.com/yongninglei/launchcontainers](https://github.com/yongninglei/launchcontainers)
