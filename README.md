# Robust-CRAFG-framework (Robust Common-Root Aware Feature Generation)

  This repository contains the official implementation of the research paper:
"Robust-CRAFG: A Common-Root-Aware Framework for Efficient Feature Generation on High-Dimensional and Imbalanced Data" (Author: Teerapat Chundetsumrit, 2025).

The **Robust-CRAFG framework** aims to enhance classification performance on both **balanced** and **imbalanced** datasets by integrating fours main processes:
- **Subsampling:** Reducing size of dataset for mining knowledge.
- **Resampling Techniques:** applying methods such as **Condensed Nearest Neighbor (CNN)** and **Synthetic Minority Over-sampling Technique (SMOTE)** to handle data imbalance.
- **Feature Selection:** filtering redundant or irrelevant features. 
- **Feature Generation:** creating informative features using common-root relationships and recommendation binary operator selection via using cluster based.  
 
The notebooks demonstrate:
1) RobustCRAFG.ipynb /// Developed framework
2) 01_robust_crafg_framework_tutorial.ipynb/// Tutorial running output from framework
   - Using dataset from opensoure OpenML with library openml
   - Generate output with Robust-CRAFG framework both of balance and imbalance dataset
4) 02_evaluation_classification_performance.ipynb/// Evaluation classification performance of framework
   - Generate baseline for evaluate classification performance both of balance and imbalance dataset
   - Show improving classification performance both of balance and imbalance dataset
