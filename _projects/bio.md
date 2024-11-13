---
title: Developing a GNN Model for Alzheimer’s Disease Research  
subtitle: Internship at Harvard Medical School /Mass General Hospital  
date: 2024-07-01 09:00:00 -0400  
description: Working on ALZ-PINNACLE, a GNN model that integrates protein, cell-type, and tissue data within a unified latent space. Tasks included pre-training the model on extensive protein interaction data and investigating the role of APOE, a major genetic risk factor for Alzheimer’s.  
featured_image: /images/massg.jpg 
---

<br>
<h2>Objective</h2>
<blockquote>
<p>Developed a novel multi-scale graph neural network model (ALZ-PINNACLE) to bridge molecular, cellular, and tissue-level insights in Alzheimer's disease research by integrating and analyzing complex brain omics data across the aging to AD continuum.</p>
</blockquote>
<br>

<h2>Model Details</h2>
<blockquote>
<p style="color: #666;">
- Built on PINNACLE framework with adaptations for AD-specific data<br>
- Integrated 14,951 proteins and 206,850 protein interactions<br>
- Incorporated 7 cell types and 48 cell subtypes/states<br>
- Implemented protein-protein and cell-type interaction networks<br>
- Developed custom protein-to-cell-type attention mechanism<br>
- Pre-trained on self-supervised link prediction tasks<br>
- Fine-tuned using AD GWAS data (78 positive, 65 negative samples)
</p>
</blockquote>
<br>

<h2>Results</h2>
<blockquote>
<p style="color: #666;">
- Identified astrocyte, endothelial, and neuronal subclusters as most predictive of APOE's role in AD<br>
- Outperformed baseline models in multiple metrics:<br>
&nbsp;&nbsp;• 70.83% better AP@5 vs Random Walk<br>
&nbsp;&nbsp;• 72.92% better AUPRC vs Random Walk<br>
&nbsp;&nbsp;• 77.08% better Recall@5 vs Random Walk<br>
- Demonstrated superior performance compared to BIONIC:<br>
&nbsp;&nbsp;• 60.42% better AP@5<br>
&nbsp;&nbsp;• 50.00% better AUPRC<br>
- Successfully validated model's ability to capture cell-type specific contexts in AD
</p>
</blockquote>
<br>

<p style="color: #666;"><em>This research represents a significant step forward in understanding Alzheimer's disease mechanisms through advanced machine learning techniques. The project demonstrates the power of multi-scale modeling in capturing complex biological relationships across molecular, cellular, and tissue levels. The developed framework provides a foundation for future therapeutic target discovery and longitudinal disease progression studies. </em></p>
<br>

---
<div class="gallery" data-columns="1">
	<img src="/images/Fig1.png">
	<img src="/images/Fig2.png">
</div>

---





