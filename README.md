# Project: Predicting English Marks using Linear Regression

## Description

This project aims to build a linear regression model to predict students' English marks based on various background and study habit factors.  We will use a dataset containing student information, including demographics, prior academic performance, study habits, and lifestyle factors, to train a model that can estimate English marks.

This project serves as a practical exercise in applying linear regression using PyTorch and understanding the process of data exploration, preprocessing, model building, training, and evaluation in a machine learning context.

## Dataset

The dataset used for this project is:

*   **ResearchInformation3.csv**:  This CSV file contains student data, including features like Department, Gender, HSC, SSC, Income, Hometown, Computer usage, Preparation time, Gaming time, Attendance, Job status, English marks, Extracurricular activities, Semester, Last semester GPA, and Overall GPA.

    *   The dataset is assumed to be located in a `data/` subfolder relative to the project directory, or in the same directory as the project notebook.
    *   For detailed information about the dataset columns, please refer to the `README.md` file located in the `data/` directory (if available) or the dataset description on Mendeley Data ([https://data.mendeley.com/datasets/5b82ytz489/1](https://data.mendeley.com/datasets/5b82ytz489/1)).

## Project Goal

The primary goal is to:

1.  **Explore the `ResearchInformation3.csv` dataset** to understand its structure, data types, and identify relevant features for predicting English marks.
2.  **Preprocess the data** by handling categorical features (e.g., using one-hot encoding) and preparing it for linear regression.
3.  **Build a linear regression model using PyTorch** to predict the `English` column based on selected input features.
4.  **Train and evaluate the model** using appropriate metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.
5.  **Interpret the model's coefficients** to understand the relationships between the input features and the predicted English marks.

## Intended Use

This project is primarily for educational purposes, to learn and practice:

*   Linear Regression concepts and theory.
*   Data exploration and preprocessing techniques.
*   Building and training machine learning models using PyTorch.
*   Model evaluation and interpretation.

The insights gained from this project could potentially be used to understand factors influencing English language performance in students, although the model's predictive accuracy and generalizability would need to be carefully assessed.

## Steps to Run the Project

1.  **Ensure you have Python and necessary libraries installed.**  See the "Dependencies" section below.
2.  **Download the `ResearchInformation3.csv` dataset** and place it in a `data/` subfolder within your project directory, or in the same directory as your project notebook.
3.  **Open and run the `linear.ipynb` Jupyter Notebook.** This notebook contains the code for data loading, preprocessing, model building, training, and evaluation.
4.  **Follow the instructions and comments within the notebook** to understand each step of the project.
5.  **Experiment with different features, hyperparameters, and preprocessing techniques** to improve the model and deepen your understanding.

## Dependencies

*   **Python 3.x**
*   **PyTorch** (`torch`)
*   **pandas** (`pandas`)
*   **NumPy** (`numpy`)

You can install these libraries using pip:

```bash
pip install torch pandas numpy
```

## License
This project is for educational purposes and does not include a specific license. Standard data usage ethics apply to the use of the
```
ResearchInformation3.csv
```
dataset. Please refer to the original dataset source for any specific license or usage terms.


## Contact
Faturrachman - faturrachman6773@gmail.com
