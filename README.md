# Topic Modeling Analysis of National & International Media Coverage

**Comparative Topic Modeling Study using Latent Dirichlet Allocation (LDA)**

---

## Overview

This project presents a comparative Topic Modeling analysis of national and international news media coverage related to Universitas Airlangga.

The study aims to uncover dominant themes, examine narrative structures, and compare how different media contexts frame similar issues.

Latent Dirichlet Allocation (LDA) is applied to extract latent thematic structures from Indonesian and English news corpora.  
Model selection is performed using coherence score evaluation to ensure interpretability and topic stability.

---

## Objectives

- Identify dominant topics in local Indonesian news coverage  
- Compare thematic structures in local English media  
- Analyze narrative differences between national and international news  
- Determine the optimal number of topics using coherence score evaluation  

---

## Methodology

### Data Preprocessing
- Lowercasing  
- Tokenization  
- Stopword removal  
- Lemmatization  

### Feature Engineering
- Dictionary creation  
- Bag-of-Words representation  

### Topic Modeling
- Latent Dirichlet Allocation (LDA)  
- Random state fixed for reproducibility  

### Model Evaluation
- Coherence Score (C_v)  
- Topic range tested: k = 2–10  
- Best model selected based on highest coherence score  
