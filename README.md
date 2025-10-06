# Preprocessing_EEG_ICA
# EEG Artifact Repair with ICA (MNE-Python)

This repository demonstrates how to repair EEG signals by removing common artifacts  
(such as eye blinks and heartbeats) using **Independent Component Analysis (ICA)** .

----------------------------------------------------------------------------------------------------------------------------------------------

## 📂 Notebook
- `repairing_artifacts_with_ICA.ipynb` →  
  Steps included:
  - Load raw EEG data  
  - Apply filtering and preprocessing  
  - Fit ICA to extract independent components  
  - Identify EOG/ECG components (artifacts)  
  - Remove artifact components  
  - Reconstruct cleaned EEG signal  
  - Visualize before/after artifact removal  

-----------------------------------------------------------------------------------------------------------------------------------

## ▶️ How to Run
1. Install requirements:
   ```bash
   pip install mne numpy scipy matplotlib
