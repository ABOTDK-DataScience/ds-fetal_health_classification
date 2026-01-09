
# Predicting Fetal Health During Childbirth Using CTG Data: A Data Science Approach


## Introduction
Cardiotocography (CTG) is a vital prenatal diagnostic tool used to monitor fetal heart rate (FHR) and uterine contractions during pregnancy. By tracking these physiological signals, CTG assesses fetal well-being and enables early detection of fetal distress, helping clinicians identify high-risk pregnancies and intervene when necessary.

---

## Relevance
Accurate interpretation of CTG data is critical for distinguishing between normal, suspect, and pathological fetal states. Abnormal patterns may prompt further investigations, such as; ultrasound scans or blood tests, or urgent medical interventions like emergency delivery. However, CTG analysis is complex and subjective, often requiring advanced tools to standardize evaluations and reduce human error.

Tracking these physiological signals, CTG helps:
- Assess fetal well-being
- Detect fetal distress early
- Identify high-risk pregnancies
- Guide clinical interventions
  
---

## Problem Statement
The following are the current challenges in CTG:
- Subjective analysis leading to variability in interpretation
- Complex patterns are hard to standardize
- Delays in identifying pathological cases
- High false-positive rates in manual reading

---

## Project Objectives
This machine learning project aims to:
1. Automate fetal health classification into:
   - Class 1: Normal
   - Class 2: Suspect
   - Class 3: Pathological
2. Reduce interpretation subjectivity
3. Provide quantitative risk assessment
4. Support clinical decision-making

---

## Repository Structure
## Repository Structure
```bash
├── 1_machine_learning/
│   ├── notebooks/
│   │   ├── 01_data_loading.md
│   │   ├── 02_feature_engineering.md
│   │   ├── 03_model_training.md
│   │   └── 04_evaluation.md
│   ├── charts/
│   │   ├── performance_metrics.md
│   │   ├── feature_importance.md
│   │   └── confusion_matrices.md
│   └── README.md
│
├── 2_data_analysis/
│   ├── notebooks/
│   │   ├── 01_data_cleaning.md
│   │   ├── 02_statistical_analysis.md
│   │   └── 03_visualization.md
│   ├── dashboard/
│   │   ├── app_config.md
│   │   ├── assets.md
│   │   └── requirements.md
│   └── README.md
│
└── 3_data/
    ├── test_data/
    │   ├── test_set.md (with embedded tables/data samples)
    │   ├── test_labels.md
    │   └── metadata_test.md
    ├── train_data/
    │   ├── train_set.md
    │   ├── train_labels.md
    │   └── metadata_train.md
    └── README.md
```

---

## Key Features
### Data Attributes Analyzed
- **Baseline metrics**:
  - FHR baseline value
  - Number of accelerations
  - Fetal movement rate
- **Variability measures**:
  - Short-term variability
  - Long-term variability
- **Deceleration patterns**:
  - Light decelerations
  - Severe decelerations
  - Prolonged decelerations
- **Histogram data**:
  - Width, min, max values
  - Number of peaks/zeros
  - Statistical tendencies

### Technical Implementation
- **Data preprocessing**:
  - Missing value handling
  - Feature normalization
  - Class imbalance correction
- **Machine learning models**:
  - Random Forest
  - XGBoost
  - Support Vector Machines
- **Evaluation metrics**:
  - Precision and recall
  - F1-score
  - ROC-AUC curves

---

## Clinical Benefits
| Benefit | Impact |
|---------|--------|
| Early risk detection | Enables timely interventions |
| Standardized output | Reduces human variability |
| Quantitative scoring | Provides objective metrics |
| Decision support | Assists clinicians in triage |

---

## Usage Note
> This project is intended for **research purposes only**. Clinical deployment requires additional validation, clinical data and regulatory approvals.

---

## Future Work
- Integration with EHR systems
- Real-time monitoring capabilities
- Mobile application for remote areas

---
