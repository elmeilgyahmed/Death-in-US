# Death in the United States

This repository contains the code and analysis focusing on mortality data from the United States.


# Dataset:
Link to dataset (https://www.kaggle.com/cdc/mortality)
**The project utilizes a dataset named "Death in the United States," consisting of:**

    CSV files: Each file contains data for a specific year, with various attributes related to deaths.
    JSON files: Each JSON file corresponds to a CSV file and provides code mappings for interpreting the data.

# Project Structure:

    code/: Contains Python scripts for data analysis and machine learning tasks.
    data/: Stores the CSV and JSON files from the original dataset.
    results/: Intended to hold output files, such as Excel sheets for visualizations.

# Technical Analysis:

    Data Exploration:
        Scripts in code/ perform analysis on individual variables (e.g., "manner of death") and combinations of variables (e.g., "manner of death" with "sex").
        Analysis results are intended to be exported to results/ for further exploration and visualization.
    Machine Learning:
        Scripts in code/ aim to build a model to predict accidental deaths.
        Features like education, age, place of death, and others are used for training.
        The Random Forest Classifier is a potential candidate for this task.

# Results:
 ![image](https://github.com/elmeilgyahmed/Death-in-US/assets/50087016/551e26c2-6953-4891-9c38-b9826d3addd6)


![image](https://github.com/elmeilgyahmed/Death-in-US/assets/50087016/19901e70-28c5-41f7-94b3-4f0827543cc4)



![image](https://github.com/elmeilgyahmed/Death-in-US/assets/50087016/fbd6c5ed-4536-4304-b1d6-6c652d267dd3)

# Dependencies:

This project requires the Apache Spark library for data processing. You can install it using pip install pyspark.

Running the Analysis:

    Ensure you have Spark installed.
    Download or access the dataset (CSV and JSON files).
    Place the dataset files in the data/ directory.
    Execute the desired Python scripts from the code/ directory.
    Analysis results might be exported to results/ for further exploration.
