# lenz-hyperspectral-building-materials
Hyperspectral material identification in buildings using LENZ dual-sensor imaging (400–1650 nm) and machine learning — TFG, ETSEIB-UPC / DISCOVER project
# Hyperspectral Material Identification in Building Environments

Code and data for the bachelor's thesis "Material Identification in Building 
Environments Using Hyperspectral Imaging and Machine Learning" 

Developed within the DISCOVER project (CDEI-UPC), targeting autonomous 
material classification for the Oliwall deconstruction robot using the LENZ 
dual-sensor camera (Si + InGaAs, 400–1650 nm).

**Best model:** XGBoost + SNV+D1 · macro-F1 = 0.873 ± 0.051 · MCC = 0.881  
**7 classes:** brick, cementitious, ceramic, gypsum, metal, polymer, wood  
**7 027 spectra · 104 physical specimens · 5-fold specimen-grouped CV**
