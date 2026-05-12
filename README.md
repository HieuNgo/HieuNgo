<div align="center">

# Hieu Ngo (Henry)

**Machine Learning Research Scientist &nbsp;·&nbsp; PhD Computer Science**

Postdoctoral Researcher · Yeshiva University, Katz School of Science & Health, New York

[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=NfCIh8gAAAAJ&hl=en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hieu-ngo-014901a3/)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-2595-2166)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=github&logoColor=white)](https://hieungo.github.io)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:ngohieu241@gmail.com)

</div>

---

## About

I build machine learning systems at the intersection of **federated learning**, **health AI**, and **agentic AI**. My research focuses on enabling privacy-preserving, distributed analysis of large-scale clinical and behavioral data — designing algorithms that work across heterogeneous sites without centralizing sensitive records.

Currently a Postdoctoral ML Researcher at Yeshiva University (XR AI Lab). PhD in Engineering & Applied Science (Computer Science), UMass Dartmouth, Oct 2025.

**Research areas:** Federated & distributed learning · Unsupervised/fuzzy modeling · Missing-data frameworks · Computer vision (BEV-map, V2V perception) · LLM fine-tuning & agentic AI · Health AI · Privacy-preserving ML

---

## Featured Projects

### 🔬 FUSE — Federated Fuzzy Consensus Clustering for Health Data
*Under review · ACM Transactions on Computing for Healthcare*

End-to-end federated clustering pipeline for incomplete multi-site longitudinal health data.
- **Lossless FeFCM** protocol preserving full fuzzy membership across sites
- **Fuzzy co-association + NMF** consensus aggregation: ARI 0.494 → **0.593** (free-K setting)
- **GapDB composite** automatic (K, m) selection without global data sharing
- Validated on **6 datasets** including 2 national cohorts: **3M+ records**, 88% structural missingness, 31:1 site imbalance

---

### 🤖 FedAutoCluster — Federated Clustering with Per-Site LLM Agents
*Manuscript in preparation*

Federated framework where each site runs a **QLoRA-finetuned LLM agent** (Qwen-7B/72B) that autonomously selects its own clustering pipeline and cluster count K from a **49,920-configuration space**.
- Trained on **1,915 expert trajectories** across **246 datasets** (fully held-out train/val/test splits)
- Two-tier orchestrator: method-specific federated protocol + trust-weighted EMA fallback
- Evaluated on 4 real MA RCT cohorts + **MIMIC-eICU** clinical held-out validation

---

### 🚗 V2V Cooperative Perception — Real-Time BEV-Map Fusion
*Published · IEEE Transactions on Vehicular Technology (IF 6.1, 73 citations)*

BEV-map based V2V collaborative perception for autonomous vehicles to resolve occlusion.
- Inference latency: **0.0456 s/frame** (~**21.9 Hz**) — meets real-time 10 Hz requirement
- BEV map 1.1 Mb @ 0.011 s vs compressed LiDAR 4,000 Mb @ 40 s over 100 Mbps
- Tested on KITTI dataset

---

### 📡 FeMIFuzzy — Federated Fuzzy Clustering Under Missingness
*Published · IEEE Internet of Things Journal (IF 8.2, 14 citations)*

Novel federated fuzzy clustering for decentralized incomplete longitudinal behavioral data.
- **~93% accuracy** vs ~52% decentralized FCM baseline at 20% missingness (N=30k, 8 clients)
- Validated on 4 real clinical cohorts (N=957, 4 sites, NIH R01-funded)
- Converged in ~10–80 iterations; reproducible multi-trial evaluation harness

---

## Publications

**Under Review / In Preparation**
- **H. Ngo**, H. Fang, H. Wang — *FUSE: Federated Fuzzy Consensus Clustering Under Missing Data for Longitudinal Digital Health Trials*. ACM Trans. Computing for Healthcare (under review).
- **H. Ngo** et al. — *FedAutoCluster: Distilling Clustering Expert Judgment into Federated Per-Site LLM Agents*. In preparation.

**Journal Articles**
- **H. Ngo** et al. — *Federated fuzzy clustering for decentralized incomplete longitudinal behavioral data*. **IEEE IoT Journal** (2023). IF 8.2 · 14 citations
- **H. Ngo** et al. — *Cooperative perception with V2V communication for autonomous vehicles*. **IEEE TVT** (2023). IF 6.1 · 73 citations
- S. V. Balkus, ..., **H. Ngo** et al. — *A survey of collaborative ML using 5G vehicular communications*. **IEEE Comm. Surveys & Tutorials** (2022). IF 35.6 · 128 citations
- B. Cornet, ..., **H. Ngo** et al. — *An overview of WBANs for mobile health applications*. **IEEE Network** (2022). IF 9.3 · 88 citations
- **H. Ngo** et al. — *Beamforming and scalable image processing in V2V networks*. **J. Signal Processing Systems** (2022).
- V. S. Gurugubelli, ..., **H. Ngo** et al. — *A review of harmonization methods for studying dietary patterns*. **Smart Health** (2022).

**Conference Papers**
- **H. Ngo** et al. — *Deep learning-based adaptive beamforming for mmWave WBAN*. **IEEE GLOBECOM 2020**. 🏆 **Best Paper Award** (IEEE ComSoc)
- **H. Ngo** et al. — *Intelligent fuzzifier-based cluster validation*. **IEEE/ACM CHASE 2022**
- J. Matos, **H. Ngo** et al. — *XR-enabled digital twins in longitudinal trials*. **IEEE/ACM CHASE 2025**

📚 Full list on [Google Scholar](https://scholar.google.com/citations?user=NfCIh8gAAAAJ&hl=en) · h-index: 8 · 382+ citations

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Lightning](https://img.shields.io/badge/PyTorch%20Lightning-792EE5?style=flat&logo=lightning&logoColor=white)

**Agentic AI / LLMs**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

**Infrastructure**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Awards & Funding

🏆 **Best Paper Award** — IEEE ComSoc Multimedia Communications TC, IEEE GLOBECOM 2020  
🎓 **CIS Graduate Research Award** — UMass Dartmouth, 2023  
✈️ **NSF Student Travel Grant** — IEEE/ACM CHASE, 2022  
🔬 **NSF Grants** — ECCS 2010366, IIS 2140729 | **NIH** — R01DK129432  
🏅 **CMU × NVIDIA Federated Learning Hackathon** — Team Lead, 2026 (privacy-preserving biobank AI)

---

<div align="center">
  <sub>📍 Union City, NJ &nbsp;·&nbsp; Open to Research Scientist / Applied Scientist / ML Engineer roles</sub>
</div>
