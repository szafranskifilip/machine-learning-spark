# Credit Card Default Prediction with Spark

## Overview

This GitHub repository contains a data science project focused on building a credit card default prediction model using Apache Spark. The main objective of the project is to practice data loading, manipulation, and model fitting within the Spark framework. Additionally, various visualizations will be utilized to gain insights from the model.

The dataset used in this project is provided by a Taiwanese financial company and includes several characteristics of individuals, such as limit balance, past payment history, age, marriage status, and sex. The task is to predict which individuals are likely to default on their credit card based on these features.

## Project Structure

The repository is structured as follows:

- `data/`: This folder contains the dataset files used in the project.

- `notebooks/`: This directory contains Jupyter notebooks that walk through the different stages of the data science process:
  - `01_Data_Exploration.ipynb`: Exploring the dataset, performing data cleaning, and visualizing the distributions of various features.
  - `02_Model_Training.ipynb`: Preprocessing the data, splitting it into training and testing sets, and fitting a predictive model using Spark's MLlib.
  - `03_Model_Evaluation.ipynb`: Evaluating the model's performance on the test set and analyzing the prediction results.
  - `04_Visualizations.ipynb`: Creating different visualizations to gain insights from the model and interpret the results.

- `scripts/`: This directory contains any helper scripts or functions used in the notebooks.

- `README.md`: This file, providing an overview of the project and instructions on how to replicate the analysis.

## Environment and Dependencies

To replicate the analysis in this project, you will need the following dependencies:

- Apache Spark: The project is developed using Apache Spark 3.1.2 with Hadoop 3.2 support.
- PySpark: Python API for Spark. Install it using `pip install pyspark`.
- JupyterLab: For running the Jupyter notebooks. Install it using `pip install jupyterlab`.
- Matplotlib: For creating visualizations. Install it using `pip install matplotlib`.

Ensure you have installed the required dependencies before running the notebooks.

## How to Use

1. Clone the repository to your local machine using `git clone https://github.com/yourusername/credit-card-default-prediction.git`.

2. Navigate to the repository directory: `cd credit-card-default-prediction`.

3. Launch JupyterLab: `jupyter lab`.

4. Open and run the Jupyter notebooks in the `notebooks/` directory in the specified order: `01_Data_Exploration.ipynb`, `02_Model_Training.ipynb`, `03_Model_Evaluation.ipynb`, and `04_Visualizations.ipynb`.

5. Follow the step-by-step instructions in the notebooks to perform data exploration, model training, evaluation, and visualization.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

The dataset used in this project is provided by the Taiwanese financial company and can be found at [insert dataset source link]. Special thanks to the company for making the data available for educational purposes.

Feel free to contribute to the project, suggest improvements, or use the code as a reference for your own credit card default prediction projects. Happy coding!
