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
<p style="color: #666;"> Developed a multi-scale Graph Neural Network (ALZ-PINNACLE) to integrate and analyze complex brain omics data across the aging to Alzheimer’s Disease (AD) continuum. This model aimed to learn meaningful, context-aware embeddings for proteins and cell types to better understand AD neurobiology, focusing on data privacy and accessibility in medical research. 
</p> 
</blockquote> 

<br> 

<h2>Model Details</h2> 
<blockquote> 
<p style="color: #666;"> 
- <strong>Architecture:</strong> Adapted from the PINNACLE framework, ALZ-PINNACLE is a multi-scale GNN that integrates data on protein-protein interactions and cell-type relationships. It learns unified embeddings that capture cell-type-specific protein interactions and contexts relevant to AD. </p> 
<p style="color: #666;"> 
- <strong>Data Integration:</strong> Utilized single-nucleus RNA-Sequencing data and known protein-protein interactions from various sources, spanning 14,951 proteins, 206,850 interactions, 7 cell types, and 48 cell subtypes/states. This integrated dataset captures the complex cellular and molecular landscape of AD. 
</p> 
<p style="color: #666;"> 
- <strong>Training Framework:</strong> ALZ-PINNACLE was pre-trained using a self-supervised link prediction task on cell-type-specific protein interaction networks. The model initially masked a subset of edges and learned to predict both true and false edges, and was then fine-tuned using AD Genome-Wide Association Study (GWAS) data to predict AD risk genes. 
</p> 
<p style="color: #666;"> 
- <strong>Contextual Learning:</strong> The model employs cell-type identity and graph connectivity to develop context-aware embeddings. This allows ALZ-PINNACLE to learn how proteins interact and function differently across distinct cellular contexts, essential for understanding complex diseases like AD. 
</p> 
</blockquote> 

<br> 

<h2>Pre-Training & Fine-Tuning Results</h2> 
<blockquote> 
<p style="color: #666;"> 
- <strong>Pre-Training Performance:</strong> Achieved robust performance in link prediction tasks on held-out sets of protein-protein interactions and cell-type graphs. Metrics such as area under the ROC curve (AUROC) and average precision (AP) indicated that ALZ-PINNACLE effectively learned context-aware embeddings during pre-training. 
</p> 
<p style="color: #666;"> 
- <strong>Protein Embedding Similarities:</strong> The model captured cell-type-specific roles of proteins, evidenced by the learned embeddings of APOE (a major AD risk gene). APOE showed high embedding similarity in microglia, neuronal, and CD8+ T cells, highlighting its consistent functional role across these cell types. 
</p> 
<p style="color: #666;"> 
- <strong>Fine-Tuning on AD Risk Genes:</strong> The model was fine-tuned using a set of known AD risk genes and negative controls from AD GWAS data. ALZ-PINNACLE accurately identified and predicted the likelihood of gene associations with AD across different cell contexts, achieving high average precision and AUROC in distinguishing AD risk genes. 
</p> 
<p style="color: #666;"> 
- <strong>Context-Specific Predictive Power:</strong> ALZ-PINNACLE determined the most predictive cell-type contexts for AD gene roles. For example, it identified that astrocyte, endothelial, and neuronal subclusters were crucial for predicting APOE's role in AD, illustrating how the model can pinpoint specific cellular contexts relevant to disease pathology. 
</p> 
</blockquote> 

<br> 

<h2>Key Achievements</h2> 
<blockquote> 
<p style="color: #666;"> 
- <strong>Publication:</strong> Accepted paper at ML4H 2024, highlighting the recognition and contribution of ALZ-PINNACLE in the field of machine learning for health.

 <br>
 
<h2>Significance</h2> 
<blockquote> 
<p style="color: #666;"> ALZ-PINNACLE demonstrates the potential of using multi-scale, context-aware graph neural networks to integrate complex biomedical data, enabling better understanding of AD neurobiology. By pre-training on protein and cell interaction networks and fine-tuning on AD risk gene data, the model provides valuable insights into how molecular and cellular interactions contribute to AD, advancing knowledge of disease mechanisms and informing potential therapeutic strategies. 
</p> 
</blockquote> 

<br>


---
<div class="gallery" data-columns="1">
	<img src="/images/Fig1.png">
	<img src="/images/Fig2.png">
</div>

---





