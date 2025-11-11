# Robust-CRAFG-framework (Robust Common-Root Aware Feature Generation)

  This repository contains the official implementation of the research paper:
"Robust-CRAFG: A Common-Root-Aware Framework for Efficient Feature Generation on High-Dimensional and Imbalanced Data" (Author: Teerapat Chundetsumrit, 2025).

The **Robust-CRAFG framework** aims to enhance classification performance on both **balanced** and **imbalanced** datasets by integrating fours main processes:
- **Subsampling:** Reducing dataset size for knowledge discovery via using stratified sampling.
- **Resampling Techniques:** applying methods such as **Condensed Nearest Neighbor (CNN)** and **Synthetic Minority Over-sampling Technique (SMOTE)** to handle data imbalance.
- **Feature Selection:** filtering redundant or irrelevant features. 
- **Feature Generation:** creating informative features using common-root relationships and recommendation binary operator selection via using cluster based.  

Notebook Descriptions
- **RobustCRAFG.ipynb**  
  Core implementation of the proposed Robust-CRAFG framework.

- **01_robust_crafg_framework_tutorial.ipynb**  
  Tutorial demonstrating how to run the Robust-CRAFG framework.  
  - Uses datasets from the open-source **OpenML** repository via the `openml` library.  
  - Generates outputs for both **balanced** and **imbalanced** datasets.

- **02_evaluation_classification_performance.ipynb**  
  Evaluation of the classification performance of the framework.  
  - Builds baseline models for comparison.  
  - Demonstrates classification performance improvements achieved by Robust-CRAFG.

pip install -r requirements.txt

How to Run
git clone https://github.com/<your-username>/Robust-CRAFG-framework.git
cd Robust-CRAFG-framework
pip install -r requirements.txt
jupyter notebook 01_robust_crafg_framework_tutorial.ipynb
jupyter notebook 02_evaluation_classification_performance.ipynb
