
# Student Performance Prediction using Machine Learning

## Project Overview
This project analyses student-related data and predicts academic performance using machine learning regression algorithms.

## Dataset
The dataset contains 10,000 student records.

### Input Features
- Hours Studied
- Previous Scores
- Extracurricular Activities
- Sleep Hours
- Sample Question Papers Practiced

### Target Variable
- Performance Index

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models
The following regression algorithms were trained and compared:

1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. ElasticNet Regression
5. K-Nearest Neighbors Regression
6. Decision Tree Regression
7. Random Forest Regression

## Model Evaluation
Model performance was evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Linear Regression achieved an R² score of approximately 98.91% in the evaluated train-test split.

## Project Structure
- `student.ipynb` – Data analysis and model training
- `Student_Performance.csv` – Dataset
- `pyproject.toml` – Project dependencies
- `uv.lock` – Dependency lock file

## How to Run
1. Clone this repository.
2. Install the project dependencies.
3. Open `student.ipynb` in Jupyter Notebook.
4. Run the notebook cells sequentially.

## Author
Steve Joshua T
