# COSMOS2020 Quiescent Galaxy Classifier  
**Machine Learning Model and Classified Catalog for COSMOS2020 Galaxies (0.2 < z < 3.5)**  

## Description  
This repository contains:  
🚀 **Pre-trained ML model** for classifying quiescent vs. star-forming galaxies in COSMOS2020  
📊 **Full classified COSMOS2020 catalog** (machine-readable tables)  
📜 **Documentation** for reproducibility  

*Developed for the study:*  
*"Machine Learning Classification of COSMOS2020 Galaxies: Quiescent vs. Star-Forming"*  

---

## Repository Contents  

### 1. Trained Models  
- `ML_Model_Classifier.pkl` - ML model classifer  
- `ML_Model_Scaler.pkl`     - ML model scaler fitted on training data

### 2. Classified Catalog  
- `COSMOS2020_ml_classifications.csv.gz`
  - **Columns**: 'ra', 'dec', 'cfht_u_mag', 'acs_f814w_mag', 'uvista_y_mag',
                 'uvista_j_mag', 'uvista_h_mag', 'uvista_ks_mag', 'irac_ch1_mag',
                 'irac_ch2_mag', 'lp_zbest', 'lp_mass_med', 'lp_sfr_med', 'is_qg_ml',
                 'is_qg_nuvrj'
  - **Column descriptions**: COLUMN_DESCRIPTIONS.ipynb

### 3. Usage (Reproduce results)
- **File**: Quiescent_Galaxy_Classifier_Usage_Example.ipynb
- **Needed Libraries**: Pandas and joblib
