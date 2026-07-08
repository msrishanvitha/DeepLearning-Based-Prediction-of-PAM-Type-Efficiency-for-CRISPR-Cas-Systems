# Deep Learning-Based Prediction of PAM Type Efficiency for CRISPR-Cas Systems

## Overview

This project predicts the efficiency of Protospacer Adjacent Motif (PAM) sequences in CRISPR-Cas systems using deep learning techniques. It preprocesses genomic sequences, extracts biologically relevant features, and trains neural network models to estimate PAM efficiency across multiple target genes.

The project demonstrates how machine learning can assist genome editing by identifying highly efficient PAM sequences for CRISPR applications.

---

## Features

- DNA sequence preprocessing
- gRNA sequence extraction
- PAM type identification
- Biological feature engineering
- Deep Learning-based efficiency prediction
- Model evaluation and visualization

---

## Dataset

A sample dataset (`sample_combined_processed_grnas.xlsx`) is included for demonstration.

The original dataset is not included due to its large size.

Target genes include:

- HTT
- CFTR
- HBB
- DYSF

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- OpenPyXL

---

## Project Structure

```
DeepLearning-Based-Prediction-of-PAM-Type-Efficiency-for-CRISPR-Cas-Systems/
│
|
│   sample_combined_processed_grnas.xlsx
├── notebooks/
│   └── PAM_Prediction.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Running

Open the notebook and execute all cells.

---

## Future Improvements

- Transformer-based sequence models
- Additional Cas variants
- Larger genomic datasets
- Web deployment

---

## Author

Sri Shanvitha
