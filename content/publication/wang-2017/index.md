---
title: "\"R\" Package for Computation of Earthquake Ground Motion Response Spectra"
date: 2017-01-01
publishDate: 2020-05-24T20:04:23.582701Z
authors: ["Pengfei Wang", "Jonathan Stewart", "Yousef Bozorgnia", "David M Boore", "Tadahiro Kishida"]
publication_types: ["4"]
abstract: "Earthquake ground motions are typically recorded with one vertical and two horizontal components. It has become standard practice to represent the horizontal component of ground shaking in a manner that recognizes a range of amplitudes with changing azimuths. These variable amplitudes can be generically denoted RotDxx, where xx indicates the percentile of the horizontal amplitude range. RotDxx representations of ground motion are used with amplitude parameters (peak acceleration and velocity) as well as response spectral ordinates for a range of oscillator periods. The use of RotDxx ground motions was introduced in the NGA-West2 project, and analysis procedures for their computation were originally developed in Fortran by the fourth author of this report. Here we describe the implementation of these analysis procedures in R, resulting in an “R” package referred to as Rotated Combination of Two-Component ground motions (RCTC). We describe related algorithms for recovering accurate peak quantities from digital data (i.e., Sincinterpolation and subset selection), which are also implemented in RCTC. We verify the code outputs by comparing them with a prior Fortran code. RCTC takes as input two horizontal components of ground motion, their azimuths, and their time step, and returns various types of variables, including pseudo spectral acceleration for each horizontal component, RotDxx for xx=0, 50, 100% as well as earlier, orientation-independent, geometric mean parameter GMRotI50. Other period-independent variables are also computed and outputted. We document here the code verification and provide instructions for its use."
featured: false
publication: ""
url_pdf: "https://peer.berkeley.edu/sites/default/files/2017_09_stewart_9.10.18.pdf"
---
