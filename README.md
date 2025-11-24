# Fair-Data-Generation-SLR
We collect 76 papers and summarize their datasets, models (GAN, VAE, etc.), sensitive attributes, domains, and fairness/utility metrics.

This repository contains the resources and summary tables for our **systematic literature review (SLR)** on **fair synthetic data generation**.

We collect and analyse **76 papers (2018–2025)** that use **generative models or synthetic data** to improve **algorithmic fairness** across different data types (tabular, image, text, graph) and domains (finance, healthcare, criminal justice, NLP, vision, recommender systems, etc.).   

---

## 📂 Repository Contents
  Structured table for all selected papers with the following columns:  
  - SL No.  
  - Year  
  - Title  
  - Publication venue  
  - Dataset and dataset type  
  - Short description of the study  
  - Classifier / model used  
  - Sensitive attribute(s)  
  - Taxonomy / technique (GAN, VAE, diffusion, causal model, augmentation, etc.)  
  - Application domain (finance, healthcare, vision, NLP, recommendation, etc.)  
  - Fairness & utility evaluation metrics  
  - Library / index (Web of Science, Scopus, ACM, etc.)  
  - Short summary of the paper   

## 🧠 Scope of the Review

Our review focuses on **fairness-aware synthetic data** and **generative approaches for debiasing**, including (but not limited to):

- **GAN-based models** such as FairGAN, FairGAN+, TabFairGAN, Distance-Correlation GAN, DECAF, Bt-GAN, FACGAN, ImpartialGAN, FairGen, Bt-GAN, and others. :contentReference[oaicite:2]{index=2}  
- **VAE-based and causal generative models** for counterfactual fairness, disentangled representations, and fair latent spaces.   
- **Diffusion models and graphical models** for fair tabular data, images, and graphs. :contentReference[oaicite:4]{index=4}  
- **Data augmentation & oversampling methods** (e.g., SMOTE variants, subgroup mixup, counterfactual data augmentation, LLM-guided synthetic data) designed to reduce bias.   

The table also records which **fairness metrics** each paper uses (e.g., Statistical Parity Difference, Demographic Parity, Equalized Odds, Equal Opportunity, Risk Difference, Disparate Impact, Worst Group Accuracy, etc.) and which **downstream utility metrics** they report (e.g., Accuracy, F1, AUC, BCA).   

---

## ✅ How to Use This Repository
  - Quickly filter papers by **year**, **domain**, **model type** (GAN/VAE/diffusion/causal/augmentation), or **fairness metric** using the Excel or CSV version of the table.  
  - Identify research gaps (e.g., under-explored domains, metrics, or data types).
