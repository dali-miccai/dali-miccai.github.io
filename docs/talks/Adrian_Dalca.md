---
layout: page
title: "Invited Talk: Adrian Dalca"
subtitle: Augmentation and Synthesis for Learning Domain Invariances in Medical Image Analysis
author: The DALI Organizers
---

### Abstract

Distribution shift and domain generalization are fundamental challenges in machine learning, and present unique difficulties in medical imaging. General data augmentation strategies provide a helpful framework for tackling distribution shift, but are very often hand-tuned and fail to capture the complex variations in the medical imaging domain. I'll first describe a framework for improving data augmentation by learning spatial transforms, which exploits the regularity of medical images. Based on insights from this work, I'll introduce a recent line of research that achieves domain generalization doing the opposite -- instead of learning distributions of plausible images, it uses carefully crafted synthesis techniques to generate implausible images. This strategy teaches a network to ignore various aspects of images, like the MR contrast, and hence be invariant to these properties at test time. This paradigm facilitates popular medical image analysis tasks, like segmentation and registration, on unprocessed scans of any MR contrast and many image corruption types, and requires minimal or even no real training data. I'll close by discussing sometimes surprising insights we learned about what neural networks are capable of in medical image analysis, and exciting resulting directions.

## Speaker's Bio

Adrian V. Dalca is Assistant Professor at Harvard Medical School, and research scientist at the Massachusetts Institute of Technology. He obtained his PhD from CSAIL, MIT, and his research focuses on probabilistic models and machine learning techniques to capture relationships between medical images, clinical diagnoses, and other complex medical data. His work spans medical image analysis, computer vision, machine learning and computational biology. He received his BS and MS in Computer Science from the University of Toronto.
