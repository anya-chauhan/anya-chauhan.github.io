---
title: Exploring AI-Generated Cardiac MRI Data for Machine Learning  
subtitle: Harvard Undergraduate OpenBio Laboratory  
date: 2024-06-01 09:00:00 -0400  
description: Explored the use of AI-generated cardiac MRI data to train machine learning models. Work addressed issues of data scarcity and patient privacy, evaluating whether models trained exclusively on synthetic data could still perform well on real-world datasets.
  
featured_image: /images/sri_1.png  
---

<br>

<h2>Objective</h2>
<blockquote>
<p style="color: #666;">Investigated whether AI models trained exclusively on synthetic cardiac MRI data could effectively predict clinical metrics when tested on real patient data, addressing crucial challenges of data privacy and accessibility in medical AI development.</p>
</blockquote>

<br>

<h2>Model Details</h2>
<blockquote>
<p style="color: #666;">
- Used a modified ResNet50 architecture trained on AI-generated cardiac MRI images<br>
- Implemented comprehensive data augmentation pipeline including rotations, contrast adjustments, and controlled blur effects<br>
- Utilized Grad-CAM visualization to verify model's focus on clinically relevant cardiac features<br>
- Developed custom application for precise labeling of synthetic images
</p>
</blockquote>

<br>

<h2>Findings</h2>
<blockquote>
<p style="color: #666;">
- Model achieved high performance on synthetic data (MSE = 0.0015, r² = 0.9452)<br>
- Maintained strong performance on real MRI images (MSE = 0.0089, r² = 0.6860)<br>
- Accuracy comparable to inter-physician variability, demonstrating clinical potential<br>
- Results published in <em>The Young Researcher</em>
</p>
</blockquote>

<br>

<p style="color: #666;">This research, conducted under mentorship at SRI (Harvard Undergraduate OpenBio Laboratory's Student Research Institute), demonstrates the potential of synthetic data in advancing medical AI while protecting patient privacy. The project not only yielded promising technical results but also provided valuable insights into model interpretability and the balance between complexity and performance in medical AI applications.</p>


<p><em>This was more than just a technical milestone; it was my first chance to see AI interact with real-world medical challenges.</em></p>

<br>

---

<div class="gallery" data-columns="1">
	<img src="/images/sri_1.png">
	<img src="/images/sri_3.png">
	<img src="/images/sri_4.png">
</div>

<p><em>Figure 1. Key Stages in Developing an AI Model for Sphericity Index Prediction from Cardiac MRI Data
(A) Data Preparation: Used both AI-generated and real cardiac MRI images. The AI-generated images had manually calculated SI values; real MRI images had physician-computed SI values. This provided diverse training data and reliable ground truth. (B) Model Training: Trained a ResNet50 to predict left ventricle SI as highlighted by Grad-CAM visualizations. The figure shows the labeled SI value (0.587) and the computed SI value (0.592). (C) Model Performance: Evaluated on AI-generated images (MSE=0.0015, r² = 0.9452) and real MRI images (MSE= 0.0089, r² = 0.6860). Accuracy on real data is comparable to inter-physician variability, suggesting clinical potential.</em></p>

---


