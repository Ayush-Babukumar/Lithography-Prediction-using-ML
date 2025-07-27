#  Lithology Prediction from Well Log Data Using Machine Learning

This project uses synthetic well log data to predict lithology types (e.g., Sandstone, Shale, Limestone, Dolomite) using a *Random Forest Classifier. It includes full **EDA*, model training, evaluation, and visualization of subsurface lithology trends.

---

##  Features

-  Synthetic dataset simulation with realistic well log curves
-  Exploratory Data Analysis (EDA) with Seaborn & Matplotlib
-  Machine Learning with RandomForestClassifier
-  Confusion Matrix, Feature Importance, and Depth-wise Lithology visualization
-  Accuracy evaluation before and after visualization
-  Save graphs as .png and export dataset as .csv

---

##  Files Included

| File | Description |

| Lithology Prediction.ipynb | Full working Jupyter notebook |
| Simulated_Well_Log_Dataset.csv | Exported dataset with features and labels |
| images/ (optional) | Folder with saved PNG graphs |
| requirements.txt | Python libraries needed |
| README.md | This file |

---

##  Dataset Description

The dataset includes 300 synthetic samples with the following features:

| Feature | Description |

| GR | Gamma Ray |
| RHOB | Bulk Density |
| NPHI | Neutron Porosity |
| DT | Sonic Transit Time |
| ILD | Deep Resistivity |
| PE | Photoelectric Effect |
| DEPTH | Measured well depth |
| LITHOLOGY | Rock type label (categorical) |

---

##  Machine Learning Model

- Model: RandomForestClassifier (n=100)
- Train/Test Split: 80/20
- Accuracy: >95% on synthetic data

---

##  Visualizations

-  Correlation heatmap
-  Feature importance bar chart
-  Confusion matrix
-  Lithology prediction vs depth
