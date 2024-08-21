---
title: "ML4VA Project: Classifying Food Access Regions to Inform Food Bank Policy"
collection: papers
category: coursework
permalink: /paper/2023-12-02-ML4VA-project
excerpt: "Our final project in CS 4774 - Machine Learning targeted a social issue facing Virginia: food insecurity. We applied clustering analysis and deep learning to identify food access by county to aid food banks and policy makers in fine-tuning interventions to the unique needs of each region.<br/><img src='/images/papers/ml4va_feat_density.png'>"
date: 2023-12-02
paperurl: 'https://www.andrewbalch.com/files/ML4VA_Project.pdf'
repourl: 'https://github.com/ericwhamilton1/gradient-descent-into-madness'
---
Our final project in CS 4774 - Machine Learning targeted a social issue facing Virginia: food insecurity. We applied clustering analysis and deep learning to identify food access by county to aid food banks and policy makers in fine-tuning interventions to the unique needs of each region.

![image](/images/papers/ml4va_feat_density.png)
*Key feature distributions based on UMAP cluster. We found that cluster 0 was a food desert, 1 was a food swamp, and 2 was a food oasis.*

## Abstract

This project sought to address the problem of food insecurity in Virginia by classifying regions to help inform policy.
The approach involved combining a dataset of Virginia food bank data with USDA’s Food Access Research Atlas, which
contains data on food security. Early on, three distinct clusters of Virginia counties were discovered. The researchers
found little success in linearly differentiating these clusters with a single metric, but were able to clearly distinguish
them using a more holistic approach and feature analysis. These three clusters were called "food oasis", "food swamp",
and "food desert", which corroborated previous literature’s characterizations of such regions. Finally, the researchers
were able to hand-select 9 features from the over 100 features, and use only these to predict which category a new
region belonged to with 100% testing accuracy using a Deep Neural Network. With such a model, the researchers hope
to better inform policy for both existing counties which have already been classified and new regions - whether in other
states or in census tracts more local than counties - since food oases, food swamps, and food deserts should employ
separate protocols to better suit their needs.
