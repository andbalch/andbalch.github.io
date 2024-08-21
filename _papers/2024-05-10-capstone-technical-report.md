---
title: "Capstone Technical Report: Visualizing and Predicting Rectal Cancer Treatment Outcomes"
collection: papers
category: coursework
permalink: /paper/2024-05-10-capstone-technical-report
excerpt: "For my Bachelor's of Science capstone project, I continued work I began in 2020 with Emory University modeling a unique dataset of rectal cancer treatment paths. I cleaned the hand-entered data and developed a novel, data-driven visualization approach that integrates feature selection techniques.<br/><img src='/images/papers/sample_leak_plot.png'>"
date: 2024-05-10
paperurl: 'https://www.andrewbalch.com/files/Capstone_Technical_Report.pdf'
repourl: 'https://github.com/HAI-lab-UVA/RCC-Project'
---
For my Bachelor's of Science capstone project, I continued work I began in 2020 with Emory University modeling a unique dataset of rectal cancer treatment paths. I cleaned the hand-entered data and developed a novel, data-driven visualization approach that integrates feature selection techniques.

![image](/images/papers/sample_leak_plot.png)
*Sankey-based visualization of Anastomotic Leak progression using ML-selected features.*

## Abstract

Effectively treating rectal cancer requires attentive consideration of hundreds of details about the patient and how each may influce patient outcomes and negative side-effects. The US Rectal Cancer Consortium has complied a one-of-a-kind dataset that contains fine-grain details about individual patient treatment paths from 6 different institutions over a decade. Only statistical analysis for the impact of post-op complications (POCs) on oncologic outcomes has been conducted on this dataset, so the development of visualization and machine learning tools could further progress in rectal cancer treatment. We present a simple data processing approach for the RCC as well as a data-driven event sequence visualization of the incidence of a major POC (anastomotic leakage). This visualization utilizes machine learning feature selection approaches to uncover variables that are powerful predictors of an anastomotic leak, including a novel chained approach for event sequences. A rectal cancer surgeon stakeholder was consulted throughout development and provided feedback on the final tool. The tool is generalizable to other event sequence datasets and has been made publically available at [https://github.com/HAI-lab-UVA/RCC-Project](https://github.com/HAI-lab-UVA/RCC-Project).
