# From a Single Drop to Intelligent Decisions 

### Diabetes Classification Using Decision Trees

## Project Overview

developed a **Decision Tree Classifier** to predict three diabetes categories:

- **N:** Non-diabetic
- **P:** Pre-diabetic
- **Y:** Diabetic

The project covers the complete machine learning workflow, from exploratory data analysis and preprocessing to model training, hyperparameter tuning, and evaluation.

## Dataset

**Source:** [Diabetes Dataset — Mendeley Data](https://data.mendeley.com/datasets/wj9rwkp9c2/1)

- Original records: 1,000
- Original columns: 14
- Records after preprocessing: 825
- Model features: 11
- Training samples: 660
- Testing samples: 165

Preprocessing included cleaning inconsistent labels, excluding identifiers, removing repeated medical profiles, handling an invalid cholesterol value, and encoding categorical features.

## Machine Learning Models

We trained and compared two classification models:

**Logistic Regression** — Baseline model  
**Decision Tree** — Main classification model

Decision Tree hyperparameters were explored using **5-fold cross-validation**, with **Macro F1-score** used to compare tree depths.

## Model Performance

| Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 93.9% | **98.8%** |
| Macro F1-score | 74.2% | **97.9%** |
| Pre-diabetic Recall | 25.0% | **100.0%** |

The selected Decision Tree used a maximum depth of **5** and correctly classified **163 out of 165 test records**.

Because the dataset is imbalanced, we evaluated class-level performance rather than relying on accuracy alone.

## Interactive Presentation

The presentation follows the story:

**From a Single Drop → Medical Data → Decision Trees → Intelligent Decisions**

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- JS/HTML5/CSS3

**From a Single Drop to Intelligent Decisions.**

*Turning data into understanding through machine learning.*
