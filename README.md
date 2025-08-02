# Decision Tree Classifier using Scikit-learn 

This project demonstrates how to use a **Decision Tree Classifier** to classify data using **Scikit-learn**. The dataset used is the popular **Iris dataset**, and the goal is to predict the species of iris flowers based on their features.

##  Model Used
- Decision Tree Classifier (`sklearn.tree.DecisionTreeClassifier`)
- Visualized using `plot_tree` from `sklearn`

##  Project Structure
```
decision-tree-classifier/
│
├── Data/
│   └── iris.csv
├── notebook/
│   └── decision_tree.ipynb
├── models/
│   └── dt_model.joblib
├── images/
│   └── tree_plot.png
└── src/
    ├── train_model.py
    └── predict.py
```

##  Setup Instructions
1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Open the notebook: `notebook/decision_tree.ipynb`

##  Output Visualization
The notebook includes:
- Feature importance graph
- Decision tree visualization
- Accuracy score

##  Author
Shejal Dhole

##  License
MIT License
