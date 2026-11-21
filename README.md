# -Analysis-of-Intrusion-Patterns-Using-Campus-Network-Firewall-Records
# Analysis of Intrusion Patterns Using Campus Network Firewall Records

## Project Overview
This project uses machine learning to analyze campus network firewall records and predict firewall actions based on network traffic patterns.

## Objective
To perform multi-class classification and predict firewall actions using port, NAT, byte, packet, and timing attributes.

## Dataset
- Total records: 65,532
- Total columns: 12
- Target variable: `Action`
- Classes: `allow`, `deny`, `drop`, `reset-both`

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithms
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Model Performance

| Algorithm | Accuracy |
|---|---:|
| Logistic Regression | 97.92% |
| Decision Tree | 99.77% |
| Random Forest | 99.78% |

## Workflow
1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature selection
4. Train-test splitting
5. Model training
6. Model evaluation and comparison

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Execution

```bash
jupyter notebook
```

Load `log2.csv` and run the notebook cells.

## Conclusion
The three machine learning algorithms were successfully implemented and evaluated. Random Forest achieved the highest testing accuracy of 99.78%, followed closely by Decision Tree and Logistic Regression.

## Domain
Network Security | Machine Learning | Multi-class Classification
