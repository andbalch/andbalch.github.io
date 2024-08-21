---
title: "Governor's School Mentorship: Transformer-Based Architecture for Android Malware Classification and TTP Prediction"
collection: papers
category: coursework
permalink: /paper/2021-04-22-gov-school-mentorship
excerpt: "In my senior year of high school at the Governor's School for Science and Technology (a public, dual-enrollment program), I conducted a deep learning research project for Android malware detection under the mentorship of Wes Jordan at MITRE. I used the TensorFlow and data science skills I picked up during COVID to develop a framework that generalized the problem to an NLP task via tokenization and applied a transformer architecture. Although the computational cost far exceed anything I had access to, I still learned a lot!"
date: 2021-04-22
paperurl: 'https://www.andrewbalch.com/files/Transformer-Based Architecture for Android Malware Classification and TTP Prediction.pdf'
repourl: 'https://github.com/andbalch/MITRE_modeling'
---
In my senior year of high school at the Governor's School for Science and Technology (a public, dual-enrollment program), I conducted a deep learning research project for Android malware detection under the mentorship of Wes Jordan at MITRE. I used the TensorFlow and data science skills I picked up during COVID to develop a framework that generalized the problem to an NLP task via tokenization and applied a transformer architecture. Although the computational cost far exceed anything I had access to, I still learned a lot!

## Abstract

Transformers promise groundbreaking advances in deep learning by allowing models to
generalize and form attention between elements in a sequence better than ever before. While
typically constrained to Natural Language Processing (NLP) tasks, this study applies
Transformers to Android malware proposing a unique, multi-task approach to malware
classification and technique prediction from time-series dynamic analysis and context from
MITRE’s ATT&CK. The model would use the encoder outputs for classification and the decoder
element to predict technique chains with a diverging transfer learning element allowing the two
to generalize, then separate and fine-tune. Compared to previous research into deep learning and
cybersecurity in traditional deep, convolutional, or recurrent neural networks, expected results
from the proposed architecture improve on traditional networks yielding 98% accuracy in
malware classification and 99.9% accuracy in technique prediction (on training data only). The
expected findings support the utility of Transformers in use cases beyond NLP and provide a
method for proactive anti-malware to detect malicious activity in real-time via malware
techniques. Unfortunately, the study could not be completed as planned due to unforeseen time
and resource constraints.
