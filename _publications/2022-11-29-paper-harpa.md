---
title: "HARPA: Hierarchical Attention with Relation Paths for Knowledge Graph Embedding Adversarial Learning"
collection: publications
category: manuscripts
permalink: /publication/2022-11-29-paper-harpa
excerpt: ''
date: 2022-11-29
venue: 'Data Mining and Knowledge Discovery (DMKD, Journal)'
#slidesurl: 'https://windyx.github.io/files/2022-paper-harpa-slide.pdf'
#paperurl: 'https://windyx.github.io/files/2022-paper-harpa.pdf'
citation: '**N. Zhang**, J. Wang, and J. He, &quot;HARPA: Hierarchical attention with relation paths for knowledge graph embedding adversarial learning.&quot; *Data Mining Knowl. Discov.*, vol. 37, no. 2, pp. 521–551, 2023.' [Link](https://dl.acm.org/doi/10.1007/s10618-022-00888-3)
---

Knowledge graph embedding (KGE) aims to map the knowledge graph into a low-dimensional continuous vector space and provide a unified underlying representation for downstream tasks. Recently, graph neural network (GNN) has been widely used in knowledge graph embedding because of its powerful feature extraction ability, and most KGE models based on GNN use aggregation operations to extract potential information from the triples. Unfortunately, they only emphasize entity embedding and use shallow operations to update relations. As a result, the learning of relation embedding is relatively simple. And they ignore the rich inference information contained in the multi-hop paths. In addition, their complex network structure lacks regularization constraint, which is prone to the over-fitting problem. Therefore, this paper proposes a novel hierarchical attention with relation paths model for knowledge graph embedding adversarial learning (HARPA). HARPA constructs a two-layer attention encoder to learn the information of triples and neighborhoods at the triples-level and further utilizes the rich inference information of paths to deeply learn relation embedding at the paths-level. Besides, HARPA proposes an improved generative adversarial network (GAN) named I-GAN as the regularization term of the model, which imposes constraints on the process of learning embedding and enables the model to learn high-quality and robust embedding. The link prediction experiments on four general knowledge graphs show that the HARPA model outperforms state-of-the-art methods.
