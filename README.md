<div align="center">
  
# Welcome to the COSI Data Challenges!

<p align="center">
<img width="350"  src="logo.png">
</p>

### latest release: [cosi-data-challenge-2](cosi-data-challenge-2)

<div align="left">

## Table Of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Releases](#releases)
- [Simulation Tools](#simulation-tools)
- [Computing Resources](#computing-resources)
- [Summary of Challenges](#summary-of-challenges)

## Introduction
The COSI data challenges are released on a yearly basis in preparation for the launch of the COSI SMEX mission. They are based on simulated data, which is intended to closely mimic the real flight data. Every year the data challenges have increasingly more realistic source and background models, and they are analyzed with increasingly complete and matured analysis tools. In general there are two main goals of the data challenges:

1. Facilitate development of the COSI data pipeline and analysis tools.
   - With routine feedback from scientists. 
   - Alongside development of the expected source models by the science team. 
2. Provide resources to the astrophysics community to become familiar with COSI data.
   - Excellent training for science team in preparation for first analyses after launch.
   - Public releases help with community building before COSI data is released. 

## Getting Started

## Releases

- Data challenge 1, March 2023: [cosi-data-challenge-1](cosi-data-challenge-1)
- Data challenge 2, March 2024: [cosi-data-challenge-2](cosi-data-challenge-2)
- Data challenge 3, March 2025: [cosi-data-challenge-3](cosi-data-challenge-3)
- Data challenge 4: Planned for March 2026
- Data challenge 5: Planned for March 2027 (final challenge before launch :rocket:!)

## Simulation Tools

## Computing Resources
<img  align="right" width="250"  src="images/clusters.png">

The source simulations were ran on NASA's [Discover cluster](https://www.nccs.nasa.gov/systems/discover). We used 1000 parallel CPUs for most of the source simulations, which allowed us to simulate them in a fairly short time (typically less than ~10 minutes of total wall time per source). The source models were provided by the COSI science teams, and more information about them can be found in the respective **Data Challenges** section on the main page. The Background simulations were ran on the [MOGON](https://mogonwiki.zdv.uni-mainz.de/docs/introduction/what_is_mogon) cluster in Mainz and Clemson University's [Palmetto](https://docs.rcd.clemson.edu/palmetto/) cluster. Simulations of the backgrounds were highly computationally intensive. The most time-consuming simulations were the primary protons, which required 57.5 years of CPU time! This was accomplished by using 6045 parallel cores. More details about the background simulations can be found in the [backgrounds](https://github.com/cositools/cosi-data-challenge-2/tree/main/backgrounds) directory.

## Summary of Challenges 
