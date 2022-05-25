---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Relational Database for Horizontal‐to‐Vertical Spectral Ratios
subtitle: ''
summary: ''
authors:
- Pengfei Wang
- Paolo Zimmaro
- Tristan E. Buckreis
- Tatiana Gospe
- Scott J. Brandenberg
- Sean K. Ahdi
- Alan Yong
- Jonathan P. Stewart
tags: []
categories: []
date: '2021-12-01'
lastmod: 2022-01-18T11:32:49-08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-01-18T19:32:49.035366Z'
publication_types:
- '2'
abstract: Frequency‐dependent horizontal‐to‐vertical spectral ratios (HVSRs) of Fourier
  amplitudes from three‐component recordings can provide useful information for site
  response modeling. However, such information is not incorporated into most ground‐motion
  models, including those from Next‐Generation Attenuation projects, which instead
  use the time‐averaged shear‐wave velocity (VS) in the upper 30 m of the site and
  sediment depth terms. To facilitate utilization of HVSR, we developed a publicly
  accessible relational database. This database is adapted from a similar repository
  for VS data and provides microtremor‐based HVSR data (mHVSR) and supporting metadata,
  but not parameters derived from the data. Users can interact with the data directly
  within a web portal that contains a graphical user interface (GUI) or through external
  tools that perform cloud‐based computations. Within the database GUI, the median
  horizontal‐component mHVSR can be plotted against frequency, with the mean and mean
  ± one standard deviation (representing variability across time windows) provided.
  Using external interactive tools (provided as a Jupyter Notebook and an R script),
  users can replot mHVSR (as in the database) or create polar plots. These tools can
  also derive parameters of potential interest for modeling purposes, including a
  binary variable indicating whether an mHVSR plot contains peaks, as well as the
  fitted properties of those peaks (frequencies, amplitudes, and widths). Metadata
  are also accessible, which includes site location, details about the instruments
  used to make the measurements, and data processing information related to windowing,
  antitrigger routines, and filtering.
publication: '*Seismological Research Letters*'
doi: 10.1785/0220210128
links:
- name: URL
  url: https://doi.org/10.1785/0220210128
---
