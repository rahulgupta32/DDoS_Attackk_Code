# DDoS_Attackk_Code

# Analyzing the Effects of DDoS Attacks on Digital Twin-Enabled Industrial Systems  
### A Feature Selection with Particle Swarm Optimization based Extreme Learning Machine (PSO-ELM) Approach  

---

## 📌 Overview  
This repository contains the source code and implementation of our research:  

**"Analyzing the Effects of DDoS Attacks on Digital Twin-Enabled Industrial Systems: A Feature Selection with Particle Swarm Optimization based ELM Approach" (2025)**  

The study introduces a **hybrid DDoS detection framework** that integrates:  
- Data preprocessing and class balancing with **SMOTE**  
- Feature selection using **Information Gain, Gain Ratio, ANOVA F-test, Pearson Correlation**, and **TOPSIS**  
- Dimensionality reduction with **Incremental PCA**  
- Classification using **Extreme Learning Machine (ELM)** optimized by **Particle Swarm Optimization (PSO)**  

Our proposed PSO-ELM model achieved **99.97% detection accuracy** with the **CICDDoS2019 dataset**, outperforming existing ML and DL baselines.  

---

## Dataset  
We use the **[CICDDoS2019 dataset](https://www.unb.ca/cic/datasets/ddos-2019.html)**, which contains 88 network traffic features extracted via CICFlowMeter.  

- **Benign traffic → `0`**  
- **All attack types → `1`**  



---

## ⚙️ Requirements  

Install the dependencies before running:  

```bash
pip install numpy pandas scikit-learn imbalanced-learn matplotlib seaborn pyswarm
