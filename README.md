📰 Topic Modeling Analysis of National & International Media Coverage

Comparative Topic Modeling Study using Latent Dirichlet Allocation (LDA)

📌 Project Overview

This project presents a comparative Topic Modeling analysis of national and international news media coverage related to Universitas Airlangga.

The objective is to uncover dominant themes, analyze narrative structures, and examine how different media contexts frame similar issues.

Latent Dirichlet Allocation (LDA) is applied to extract latent thematic structures from Indonesian and English news corpora. Model selection is optimized using coherence score evaluation to ensure interpretability and topic stability.

🎯 Objectives

Identify dominant topics in local Indonesian news coverage

Compare thematic structures in local English media

Analyze narrative differences between national and international news

Determine the optimal number of topics using coherence score evaluation

⚙️ Methodology
1️⃣ Data Preprocessing

Lowercasing

Tokenization

Stopword removal

Lemmatization

Short token filtering

2️⃣ Feature Engineering

Dictionary creation using Gensim

Bag-of-Words representation

3️⃣ Topic Modeling

Latent Dirichlet Allocation (LDA)

Random state fixed for reproducibility

4️⃣ Model Evaluation

Coherence Score (C_v)

Topic range tested: k = 2–10

Best model selected based on highest coherence score

📊 Model Evaluation Strategy

Multiple topic numbers were evaluated for each dataset.
The optimal topic count was selected using coherence score comparison to balance interpretability and semantic consistency.

This approach ensures:

More stable topics

Reduced topic overlap

Better interpretability

📂 Repository Structure
Topic-Modeling-Media-Coverage/
│
├── data/
│   ├── DATASET_UNAIR_LENGKAP.csv
│   ├── DATASET_UNAIR_CLEAN.csv
│   ├── Berita_Lokal_Inggris.csv
│   └── Berita_Internasional.csv
│
├── notebooks/
│   ├── Lokal_Indonesia.ipynb
│   ├── Lokal_Inggris.ipynb
│   └── Internasional.ipynb
│
├── results/
│   ├── coherence_lokal_indonesia.csv
│   ├── coherence_lokal_inggris.csv
│   └── coherence_internasional.csv
│
└── README.md

🧠 Key Insights

Local Indonesian news emphasizes regional academic and campus-related activities.

Local English coverage focuses more on institutional communication and outreach.

International media highlights global recognition, reputation, and broader institutional impact.

Coherence-based model selection significantly improves topic clarity and stability.

🛠 Tech Stack

Python

Pandas

NLTK

Gensim

Matplotlib

👤 Author

Indrayana Widhikartiko
Data Science | Natural Language Processing | Machine Learning
