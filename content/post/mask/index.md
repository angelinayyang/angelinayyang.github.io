---
title: The E-Mask
description: A non-invasive early detection mechanism of lung cancer by analyzing unique exhaled VOC signatures
image:
date: 2025-08-20

categories:
    - Research and Development
    - Personal Project
    
tags: 
    - feature extraction
    - python
    - cad
weight: 2     # You can add weight to some posts to override the default sorting (date descending)

---

## Introduction

Lung cancer is the leading cause of death by cancer, claiming nearly 1.5 million deaths each year. One of the largest issues pertaining to the diagnostic feasibility (stage 1 or 2) of the cancer is the lack of notable symptoms. In fact, nearly 70% of cases are discovered in late stages (stage 3 or 4), by which the cancer has metastatized, and full recovery is unlikely. Therefore, the most effective form of safety is early diagnosis.

## Project Stimulus

Recently, when researching promising non-invasive approaches to diagnosing lung cancer, I came across an article that used the presence of volatile organic compounds (VOCs) in exhaled breath as a biomarker for lung cancer. [^1] Acknowledging the recent surge in mask usage since the COVID pandemic, I sought to design a modular e-mask that could 1. attach to a standard K-95, and 2. track exhaled breath VOC signatures to provide real-time updates regarding potential cancer diagnoses. 

[^1]: [Jia et al.](https://pmc.ncbi.nlm.nih.gov/articles/PMC6044508/)

## Brainstorming

## Bill of Materials (BOM)

| Component    | Quantity | Source | Cost Per Unit |
| :-----------: | :-----------: | :------------: | :-------------: |
| Raspberry Pi Pico 2 | 1 | [Raspberry Pi](https://www.raspberrypi.com/products/raspberry-pi-pico-2/) | $5.00 |