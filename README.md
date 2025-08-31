# 🌙 Spectral Classification of Chandrayaan-2 IIRS using AI/ML

This project leverages **AI/ML techniques** to analyze hyperspectral data collected by the **Chandrayaan-2 Infrared Imaging Spectrometer (IIRS)** for understanding the geological diversity of the Moon.  
The research focuses on automating **lunar mineral classification** and detecting **hydration features**, enabling future exploration, mission planning, and resource utilization.  

---

## 📊 Dataset
- **Source:** Chandrayaan-2 Infrared Imaging Spectrometer (IIRS)  
- **Wavelength Range:** 0.8 – 5.0 µm  
- **Spectral Bands:** 256  
- **Spatial Resolution:** 80 m per pixel  
- **Target Features:** Lunar minerals (Pyroxene, Olivine, Plagioclase) and hydration (H₂O/OH) signatures  

---

## ⚙️ Methodology

### Data Preprocessing
- Radiometric & geometric corrections  
- Noise reduction using **Savitzky-Golay filtering** & **Wavelet transforms**  
- **Principal Component Analysis (PCA)** for dimensionality reduction  

### Machine Learning & Deep Learning Models
- **Support Vector Machines (SVM)**  
- **Random Forests (RF)**  
- **Convolutional Neural Networks (CNNs)**  
- **K-Means Clustering** for unsupervised exploration  

### Validation
- Evaluated with metrics such as **accuracy, F1-score, precision-recall**  
- Cross-verified with previous lunar datasets (Chandrayaan-1 M3, Apollo mission samples)  

---

## 📈 Key Results

| Region            | Composition Insights |
|-------------------|-----------------------|
| **Highlands**     | Dominated by Plagioclase (high reflectance) |
| **Mare Regions**  | Basaltic minerals (Pyroxene, Olivine) |
| **South Pole**    | Hydration signatures (H₂O/OH) detected in shadowed regions |

- **CNN** models achieved the **highest classification accuracy** among tested approaches.  
- PCA and filtering techniques significantly improved spectral signal quality.  
- Findings align with established lunar geology and confirm hydration features in shadowed regions.  

---

## 🚀 Applications
- **Lunar resource mapping** for in-situ resource utilization (ISRU)  
- **Mission planning** for future human and robotic exploration  
- **Advancing AI/ML in planetary science** and Earth-based remote sensing  

---

## 📂 Repository Contents
- `IIRS_Classification.ipynb` → End-to-end code (preprocessing, classification, visualization)  
- `Project Summary Report-1.pdf` → Academic project summary  
- `IEEE Report.pdf` → IEEE conference-style paper  
- `Final_Report.pdf` → Comprehensive final technical report  
- `images/` → Visualizations (spectral plots, classification maps, ROC curves)  

---

## ⚡ Requirements
```txt
numpy
pandas
scikit-learn
tensorflow
keras
spectral
matplotlib
seaborn
gdal
