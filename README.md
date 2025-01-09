# Mileage Prediction Project🚗📊

Welcome to the **Mileage Prediction Project**! This repository explores and predicts city-cycle fuel consumption (measured in miles per gallon, or MPG) using a dataset provided by the StatLib library and used in the 1983 American Statistical Association Exploration.

## Dataset Overview
The dataset we’re working with is a slightly modified version of the original dataset hosted by Carnegie Mellon University. It was curated for machine learning and statistical exploration purposes. As part of this project, we focus on predicting fuel efficiency based on a mix of discrete and continuous attributes.

### Key Details:
- **Source**: StatLib library at Carnegie Mellon University
- **Context**: Used in the 1983 American Statistical Association Exploration
- **Modifications**: 8 instances with unknown MPG values were removed.

For reference, the original dataset can be found in the file `auto-mpg.data-original`.

## Attribute Information
The dataset contains the following attributes:

1. **mpg** (Miles per Gallon): Continuous target variable representing fuel efficiency.
2. **cylinders**: Multi-valued discrete attribute indicating the number of engine cylinders.
3. **displacement**: Continuous variable representing engine displacement (in cubic inches).
4. **horsepower**: Continuous variable indicating the engine’s horsepower.
5. **weight**: Continuous variable representing the car’s weight (in pounds).
6. **acceleration**: Continuous variable for acceleration (time to accelerate from 0 to 60 mph in seconds).
7. **model year**: Multi-valued discrete attribute representing the car’s model year.
8. **origin**: Multi-valued discrete attribute indicating the origin of the car (e.g., USA, Europe, Asia).
9. **car name**: String attribute unique to each car (used for identification).

## Project Goals
The main objective of this project is to develop a predictive model that can accurately estimate a car’s MPG based on its features. This analysis aims to:

- Understand relationships between vehicle attributes and fuel efficiency.
- Build regression models to predict MPG.
- Evaluate model performance using statistical metrics.

## Tools and Libraries
This project utilizes the following tools and libraries:

- **Python**: The primary programming language for data analysis and modeling.
- **Pandas**: For data cleaning and manipulation.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For building and evaluating machine learning models.
- **NumPy**: For numerical computations.

## Project Workflow
1. **Data Exploration**:
   - Load and inspect the dataset.
   - Visualize key relationships and distributions.
2. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical attributes.
   - Normalize or scale continuous features.
3. **Modeling**:
   - Experiment with different regression techniques (Linear Regression, Decision Trees, etc.).
   - Evaluate model performance.
4. **Evaluation**:
   - Compare models using metrics like RMSE, MAE, and R-squared.
5. **Insights**:
   - Derive actionable insights regarding fuel efficiency.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Prasanth7733/mileage-prediction.git
   ```
2. Navigate to the project folder:
   ```bash
   cd mileage-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the analysis:
   ```bash
   python main.py
   ```

## Acknowledgments
We extend our gratitude to the StatLib library and Carnegie Mellon University for making this dataset available. Special thanks to Ross Quinlan (1993) for his work on the dataset and its application in fuel efficiency prediction.

---



