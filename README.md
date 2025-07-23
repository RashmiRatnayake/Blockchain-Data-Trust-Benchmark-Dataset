# BLOCKCHAIN DATA TRUST (BDT) BENCHMARK DATASET

Authors: Rashmi Ratnayake, Madhusanka Liyanage, Liam Murphy
School of Computer Science, University College Dublin, Ireland

----------

This repository provides a benchmark dataset for using machine learning models for blockchain data trustworthiness. The data is categorized into three major dimensions of trust, each with **balanced** and **imbalanced** versions. Supporting Jupyter notebooks are included for data generation, labeling using weak supervision (Snorkel), and exporting.

The dataset files can be found at: https://github.com/RashmiRatnayake/Blockchain-Data-Trust-Benchmark-Dataset/releases/tag/v1.0

---

## 📁 Dataset Files

Each trust category includes two versions:
- **Balanced**: 50% trustworthy, 50% untrustworthy
- **Imbalanced**: 95% trustworthy, 5% untrustworthy (to simulate real-world scenarios)

### 🔹 Data Source Trust
- `data_source_trust_balanced.csv`  
- `data_source_trust_imbalanced.csv`  
> Trust metrics related to the reliability and credibility of data sources, such as certification status, update frequency, uptime, and past false data reports.

### 🔹 Blockchain Trust
- `blockchain_trust_balanced.csv`  
- `blockchain_trust_imbalanced.csv`  
> Metrics focused on blockchain integrity, including transaction success rate, misbehavior reports, hash integrity, node uptime, and smart contract audit status.

### 🔹 External Entity Trust
- `external_entity_trust_balanced.csv`  
- `external_entity_trust_imbalanced.csv`  
> Trust metrics from third-party sources and external validators, such as cross-chain verification, crowdsourced ratings, and institutional trust scores.

---

## 📓 Script Files

These Jupyter Notebooks generate, label, and export the corresponding datasets.

- `data_source_trust_script.ipynb`  
- `blockchain_trust_script.ipynb`  
- `external_entity_trust_script.ipynb`  

Each script includes:
- Feature generation with realistic distributions
- Labeling function definitions
- Snorkel label modeling
- Attack Data simulation
- Balanced and imbalanced dataset creation
- Optional ML model evaluation pipeline

## 🔧 Usage

These datasets and scripts are designed to support experiments on trust prediction, anomaly detection, and adversarial robustness in blockchain-integrated systems using supervised and weakly supervised learning.

## 📄 License

This benchmark dataset is provided for academic and research use only.
