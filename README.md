# ZTF-ParSNIP-Classification
# Exploring Transient Classification using Deep Generative Models
Binary classification of Supernovae from ZTF data using the ParSNIP deep generative model. Includes adaptation of ZTF light curves for models pre-trained on Pan-STARRS1.


**Author:** Siméon Vareilles  
**Supervisor:** Dr. Dominique Fouchez (CPPM)

## Abstract
This project performs binary classification (Type Ia vs. non-Ia) on 1,606 supernovae from the ZTF catalogue using the **ParSNIP** machine learning tool. While ParSNIP was originally designed for Pan-STARRS1 (PS1) surveys, this work adapts ZTF data to the required standardised format.

Key findings include:
* **79% Accuracy** on Type Ia Supernovae classification using PS1 pre-trained models.
* **Analysis of Transfer Learning** limitations between PS1 and ZTF surveys.
* **Pipeline Development** for converting heterogeneous ZTF light curves into ParSNIP-compatible HDF5 formats.

## Repository Contents
* **`Predictions_PS1.ipynb`**: Baseline predictions using the original PS1 subset.
* **`Predictions_ZTF.ipynb`**: The main pipeline—fetches ZTF data, processes light curves, and evaluates classification performance.
* **`Supernova_Classification_Report.pdf`**: The full scientific report detailing methodology and physical interpretation.
