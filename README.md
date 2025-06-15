# Decision Tree Heart Analysis 

This project applies a **Decision Tree Classifier** to predict the presence of heart disease based on clinical and demographic features. Built as part of a self-learning journey, this notebook demonstrates a complete machine learning pipeline — from data preprocessing to model deployment with a Gradio-based web UI.

## 📊 Dataset

The dataset used (`heart.csv`) includes medical attributes such as:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol levels
- Fasting blood sugar
- Resting ECG results
- Max heart rate
- Exercise-induced angina
- ST depression (Oldpeak)
- Slope of the peak exercise ST segment
- Number of major vessels
- Thalassemia

##  Methodology

1. **Data Cleaning & Exploration**  
   - Handled missing values and categorical variables.
   - Used one-hot encoding for binary/multi-class features.
   - Performed statistical analysis and correlation checks.

2. **Modeling**  
   - Trained a **Decision Tree Classifier** using `scikit-learn`.
   - Used stratified train-test split for performance evaluation.

3. **Gradio UI**  
   - Deployed the trained model using **Gradio**.
   - Provides a user-friendly interface for predicting heart disease from user inputs.

   ➡ **Try it locally or host with Gradio for easy sharing.**

##  Evaluation
 _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
| Metric       | Class 0 | Class 1              |
|--------------|---------|--------------------- |
| Precision    | 0.90    | 0.82                 |
| Recall       | 0.81    | 0.91                 |
| F1-Score     | 0.85    | 0.86                 |
| **Accuracy** | **0.86** overall (276 samples) |
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ __ _ _ __ _ __ 
- **Macro Avg F1-Score:** 0.85  
- **Weighted Avg F1-Score:** 0.85

##  Live Demo

To launch the Gradio app:

pip install gradio  <br>
#  Run the notebook cell if integrated in Jupyter  <br>

## Technologies Used
- Python 
 
- pandas, numpy

- matplotlib, seaborn

- scikit-learn

- Gradio 

## File Structure
 Decision-tree-heart-analysis/     <br>
├──  Decision Tree(Self Learning).ipynb   # Main notebook with model pipeline  <br>
├──  heart.csv                            # Input dataset (required to run)  <br>
└──  README.md                            # Project documentation  <br>

## Future Enhancements
- Add feature importance chart to the UI for better interpretability

- Compare performance using Random Forest or XGBoost

- Add input validation to make the UI more robust

- Deploy publicly using Hugging Face Spaces or Streamlit Cloud
