# Datathon 2025 - Healthcare Cost Prediction

## Overview
In this project, we aim to predict hospital inpatient mean costs using structured healthcare data.  
Healthcare costs are a critical real-world issue. Accurate prediction models can help increase transparency, affordability, and decision support for both patients and providers.

## Environment Setup

To reproduce the results, please follow these steps:

1. Clone this repository.
2. We used python=3.10.16
3. Install all dependencies via:

```bash
pip install -r requirements.txt
```


## Project Structure

| File                     | Purpose                                                                                     |
|--------------------------|---------------------------------------------------------------------------------------------|
| `eda.ipynb`              | Exploratory Data Analysis: visualize distributions, understand feature relationships.       |
| `Q2_attempt.ipynb`       | Early baseline regression modeling attempts.                                                |
| `Q2_RandomForest.ipynb`  | Random Forest final model for  discharges prediction.                                |
| `Q3_decisionTree.ipynb`  | Decision Tree attempt to capture more complex behavior.                                 |
| `Q3_linearRegression.ipynb` | Linear Regression predictive baseline.                   |
| `Q3_polynomial_reg.ipynb` | Polynomial Regression attempt for capturing non-linear relationships.                
| `Q3_final.ipynb`         | Final two stage ensemble model for cost forcast.     |
| `README.md`              | This file: project description, installation guide, file explanations.                      |
| `requirements.txt`       | Python package dependencies required to run the project.                            |

## Dataset

The dataset used for this project can be accessed at:  
**[Cleaned Dataset Download Link](https://drive.google.com/file/d/1b1N3keJDasp10gJuVpHZow8JU9a_aaiM/view?usp=drive_link)**


## Presentation

The final presentation summarizing our methodology, modeling strategy, and key findings:  
**[PPT Download Link](https://www.canva.com/design/DAGlxQG7m3g/9873kRtrmPSsXDKxACnhmg/edit?utm_content=DAGlxQG7m3g&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)** 


## Visualization

Tablau Data Visualization link:
**[Link To Dashboard](https://public.tableau.com/app/profile/anna.huang8759/viz/datathon2025/MappingOnSeverityDistribution)**


## Key Highlights

- Fairness criteria on model evaluation
- Target Encoding with smoothing parameter
- Feature interaction
- XGBoost and Two Stage Training

Thank you for reviewing our project!
