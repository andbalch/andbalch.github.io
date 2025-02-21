---
title: "Exploring Smartphone-based Spectrophotometry for Nutrient Identification and Quantification"
collection: papers
category: preprints
permalink: /paper/2024-10-16-spectrophotometer-device
excerpt: 'During my time as a UVA Dean’s Research Fellow, I utilized my physical prototyping skills to refine an existing design for a smartphone-based spectrophotometer. I built a custom image analysis pipeline to extract quantitative absorbance spectra data using just a smartphone camera and conducted several experiments to fine-tune the performance of the device on micronutrient samples. <strong>I demo’d our approach at MobiCom 2024 where I won 3rd place at the undergraduate research competition</strong>, and the project was featured in <a href="https://news.virginia.edu/content/peek-summer-research-engineering-deans-fellows">a news article by UVA Today</a>!<br/><img src="/images/papers/spectro_flowchart.png" width="50%" height="50%">'
date: 2024-10-16
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2410.11027'
repourl: 'https://github.com/andbalch/Spectrophotometry-Project-Fine-Tuning'
citation: 'Balch, Andrew, Cardei, Maria A., Doryab, Afsaneh. (2024). &quot;Exploring Smartphone-based Spectrophotometry for Nutrient Identification and Quantification.&quot <i>arXiv preprint arXiv:2410.11027.</i>'
---
During my time as a UVA Dean's Research Fellow, I utilized my physical prototyping skills to refine an existing design for a smartphone-based spectrophotometer. I built a custom image analysis pipeline to extract quantitative absorbance spectra data using just a smartphone's camera and conducted several experiments to fine-tune the performance of the device on micronutrient samples. This project was featured in [a news article by UVA Today](https://news.virginia.edu/content/peek-summer-research-engineering-deans-fellows)! Submitted to the 2025 IEEE International Conference on Pervasive Computing and Communications.

<img src='/images/papers/spectro_flowchart.png' width='75%' height='75%'><br/>
*The processing and analysis pipeline for generating absorbance spectra of a sample from a smartphone captured image.*

## Abstract

Imbalanced nutrition is a global health issue with significant downstream effects. Current methods of assessing nutrient levels face several limitations, with accessibility being a major concern. In this paper, we take a step towards accessibly measuring nutrient status within the body. We explore the potential of smartphone-based spectrophotometry for identifying and quantifying nutrients in a solution by building and testing two prototype devices. We compared the prototypes and found that the limitations posed by the initial, simpler prototype were well addressed in the more portable and reliable second-generation device. With the second-generation prototype, we created and implemented a semi-automatic signal processing and analysis pipeline for analyzing absorption spectra. We thoroughly evaluated the prototypes by analyzing the effect of four different light sources and three reference spectra strategies. Results demonstrate that an LED bulb light source performed best, and all reference spectra strategies performed similarly. We then compared the second-generation prototype to a benchtop laboratory spectrophotometer to further validate the device. We applied the Beer-Lambert Law to demonstrate that our prototype is able to quantify the amount of vitamin B12 in a solution with an accuracy of up to 91.3%. Our in-depth analyses, discussions, and results demonstrate the potential use of smartphone-based spectrophotometry as an accessible method to identify and quantify nutrients and pave the way for future developments that can apply this approach to the human body.
