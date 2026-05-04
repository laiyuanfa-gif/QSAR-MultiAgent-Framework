# TCM-QSAR Multi-Agent Framework 🧬

An AI-driven, multi-agent automated workflow designed for high-throughput bioinformatics analysis, heavy metal safety risk assessment, and QSAR modeling of Traditional Chinese Medicines (TCMs). 

## 🎯 Core Features

* **Automated Data Validation (Agent A):** Processes large-scale sample data (e.g., heavy metal distributions of Pb, Cd, As, Hg, Cu across hundreds of batches). Includes a self-correcting mechanism that automatically recalculates statistical discrepancies (like CV% variance) to ensure rigorous data integrity.
* **Advanced QSAR Modeling (Agent B):** Automates the feature engineering and model training pipeline. Deploys optimized Stacking Ensemble architectures to predict drug-drug interactions involving key CYP450 enzymes (CYP3A4, 2D6, 2C9), consistently achieving AUC > 0.89.
* **Academic Compliance Engine (Agent C):** Prepares outputs strictly aligned with Q1 SCI journal requirements (e.g., *Journal of Pharmaceutical Analysis*). Automatically flags and executes specific formatting commands, such as removing non-compliant graphical elements (e.g., lower-right inset maps in geographical figures) to meet strict publication standards.

## 🛠 Tech Stack
* **Core:** Python 3.10+, Scikit-learn
* **AI Integration:** Multi-Agent LLM architecture via API 
* **Data Processing:** Pandas, NumPy, Monte Carlo Simulation scripts

## 📊 Application Scenario
This framework was successfully applied to the *Pollution Assessment of Tonic TCMs*, processing 589 batches across 18 tonic herb species, significantly reducing manual verification time and improving model robustness.

> **Note:** Full raw datasets and proprietary model weights are temporarily withheld pending peer-reviewed publication. This repository contains the core agent orchestration logic and evaluation scripts.
