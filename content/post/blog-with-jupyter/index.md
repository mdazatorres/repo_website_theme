---
title: "Kalman Filter definition, formulation, and application to wastewater SARS-CoV-2 concentration data"
date: '2023-11-04'
summary: "This post showcases an analysis conducted in R and published using Rpub."
tags: ['R', 'Data Analysis']
---

    
The Kalman Filter is an essential estimation algorithm used across various fields to estimate the hidden states of systems with noisy observations. It operates in two steps: prediction and correction, combining past estimates and current observations to generate accurate future state predictions. This post details the mathematical formulation of the Kalman Filter, its two-step process, and a practical implementation example using SARS-CoV-2 RNA concentrations in wastewater from the City of Davis. By incorporating variables such as BCoV Recovery Percentage and precipitation data, the filter provides robust estimates that account for environmental influences on wastewater measurements. The full Rpub document can be accessed [here](https://rpubs.com/mdazatorres/1175065).
