---
title: Exploring AI-Generated Cardiac MRI Data for Machine Learning  
subtitle: Harvard Undergraduate OpenBio Laboratory  
date: 2024-06-01 09:00:00 -0400  
description: Explored the use of AI-generated cardiac MRI data to train machine learning models. Work addressed issues of data scarcity and patient privacy, evaluating whether models trained exclusively on synthetic data could still perform well on real-world datasets.
  
featured_image: /images/sri_1.png  
---

<br>

<h2>Objective</h2> <blockquote> <p style="color: #666;"> Investigated whether an AI model, trained exclusively on AI-generated (synthetic) cardiac MRI images, could accurately predict clinical metrics—specifically the left ventricular sphericity index—on real patient data. This research addresses critical challenges related to data privacy and accessibility in medical AI development by utilizing synthetic data to maintain patient confidentiality while still achieving clinically relevant outcomes. </p> </blockquote> <br> <h2>Model Details</h2> <blockquote> <p style="color: #666;"> - <strong>Architecture &amp; Training:</strong> Implemented a modified ResNet50 model, pre-trained on ImageNet and fine-tuned for sphericity index prediction. The model was exclusively trained on a dataset of AI-generated cardiac MRI images. </p> <p style="color: #666;"> - <strong>Data Augmentation:</strong> Employed comprehensive augmentation techniques, including random rotations, contrast and brightness adjustments, and Gaussian blurring to ensure robust model training and prevent overfitting to synthetic data. </p> <p style="color: #666;"> - <strong>Interpretability:</strong> Utilized Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize the model’s attention, confirming it focused on clinically significant areas of the heart relevant to the sphericity index. </p> <p style="color: #666;"> - <strong>Data Labeling:</strong> Developed a custom application to manually compute and label the sphericity index on synthetic MRI images to establish reliable ground truth for model training. </p> </blockquote> <br> <h2>Key Achievements</h2> <blockquote> <p style="color: #666;"> - <strong>High Performance on Synthetic Data:</strong> Achieved exceptional predictive performance with a Mean Squared Error (MSE) of 0.0015 and a Pearson's correlation coefficient (r²) of 0.9452 when evaluated on a synthetic test set. </p> <p style="color: #666;"> - <strong>Strong Generalization to Real Data:</strong> Maintained robust accuracy on real cardiac MRI images, achieving an MSE of 0.0089 and an r² of 0.6860. The model’s performance on real data was found to be comparable to the variability observed between different physician measurements, demonstrating its clinical applicability. </p> <p style="color: #666;"> - <strong>Clinical Relevance:</strong> Results suggest that models trained on synthetic data can provide predictions within the range of expert human performance, significantly reducing the gap between synthetic training conditions and real-world clinical scenarios. </p> <p style="color: #666;"> - <strong>Published Findings:</strong> The research findings were peer-reviewed and published in <em>The Young Researcher</em>, highlighting the academic and scientific contributions of this work. </p> </blockquote> <br> <h2>Significance</h2> <blockquote> <p style="color: #666;"> This research, conducted under the mentorship at the SRI (Harvard Undergraduate OpenBio Laboratory's Student Research Institute), demonstrates the feasibility of using synthetic data to train AI models for clinical tasks while preserving patient privacy. By successfully predicting clinically relevant metrics from real patient data using a model trained solely on AI-generated images, this project addresses key challenges in data scarcity and data sharing in medical AI. Not only did it showcase the technical merits of synthetic data usage, but it also contributed valuable insights into how machine learning can be responsibly integrated into real-world medical diagnostics. </p> </blockquote>
<br>

---

<div class="gallery" data-columns="1">
	<img src="/images/sri_1.png">
	<img src="/images/sri_3.png">
</div>

<strong>Figure 1. Key Stages in Developing an AI Model for Sphericity Index Prediction from Cardiac MRI Data </strong><br>
- <strong>(A) Data Preparation:</strong> Used both AI-generated and real cardiac MRI images. The AI-generated images had manually calculated SI values; real MRI images had physician-computed SI values. This provided diverse training data and reliable ground truth. <br>
- <strong>(B) Model Training:</strong> Trained a ResNet50 to predict left ventricle SI as highlighted by Grad-CAM visualizations. The figure shows the labeled SI value (0.587) and the computed SI value (0.592). <br>
- <strong>(C) Model Performance:</strong> Evaluated on AI-generated images (MSE=0.0015, r² = 0.9452) and real MRI images (MSE= 0.0089, r² = 0.6860). Accuracy on real data is comparable to inter-physician variability, suggesting clinical potential.

---


