Task 5 - Decision Trees and Random Forests (AI & ML Internship)

Objective
This task focuses on learning and applying tree-based machine learning models — **Decision Trees** and **Random Forests** — for classification using a health indicators dataset. It includes model training, evaluation, visualization, and analysis of overfitting and feature importance.

Dataset
Name:diabetes_012_health_indicators_BRFSS2015.csv  

Target Column:  
- 0: No diabetes  
- 1: Prediabetes  
- 2: Diabetes  

Tools Used
- Python
- Jupyter Notebook
- Scikit-learn
- Matplotlib
- Seaborn
- Graphviz (for visualizing decision trees)

Tasks Completed

1. Data Preprocessing
- Loaded the dataset and checked for missing values
- Defined features (X) and target (y)
- Split the data into training and testing sets

2. Decision Tree Classifier
- Trained a Decision Tree with limited depth to avoid overfitting
- Visualized the tree using `plot_tree`
- Analyzed performance using accuracy and classification report

3. Overfitting Analysis
- Plotted train vs test accuracy for varying tree depths

4. Random Forest Classifier
- Trained a Random Forest with 100 trees
- Compared its accuracy to that of the Decision Tree

5. Feature Importance
- Plotted feature importances from the Random Forest model

6. Cross-Validation
- Evaluated both models using 5-fold cross-validation

Results

| Model              | Test Accuracy | CV Accuracy (mean) |
|-------------------|---------------|---------------------|
| Decision Tree      | ~[your_value] | ~[your_value]       |
| Random Forest      | ~[your_value] | ~[your_value]       |

Visualizations
- Decision Tree structure (`plot_tree`)
- Feature importance bar chart
- Depth vs Accuracy plot
