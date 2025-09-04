# Brain Tumor Classification (MRI) — Xception & Custom CNN

Classifies brain MRI scans into **four tumor types** — *glioma, meningioma, pituitary,* and *no tumor* — using transfer learning (Xception) and a lightweight custom CNN.

## Dataset
- **Source:** Kaggle — *Brain Tumor MRI Dataset* 
- **Structure:** `Training/` and `Testing/` 


## Results (Final Test)
| Model | Input Size | Epochs | Accuracy | Precision | Recall |
|---|---:|---:|---:|---:|---:|
| **Xception (TL)** | 299×299 | 5 | **98.78%** | ~98.79% | ~98.79% |
| **Custom CNN** | 224×224 | ≤20 (early stop) | **97.71%** | ~97.7% | ~97.7% |

> Weights are saved in-notebook as `xception_model.weights.h5` and `cnn_model2.h5`.

## Quick Start
1. **Clone & open the notebook:** `Brain_Tumor_Classification.ipynb` (Colab recommended).
2. **Run all cells** (top → bottom). The notebook handles preprocessing, training, evaluation, and saving weights.



