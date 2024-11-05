
# FIFA 23 Player Analysis

## Project Overview
This project analyzes player and team attributes in FIFA 23 to uncover patterns and relationships, using both supervised and unsupervised machine learning techniques. The analysis includes exploratory data analysis (EDA), regression modeling, and clustering to gain insights into player characteristics and predict player value.

## Objectives
- Perform EDA to explore FIFA 23 player attributes.
- Use regression models to predict player value based on various player attributes.
- Apply clustering to group players based on playing styles and abilities.
- Identify potential World Cup favorites based on player data.

## Dataset
- **Source**: [Kaggle - FIFA 23 Players Dataset](https://www.kaggle.com/datasets/sanjeetsinghnaik/fifa-23-players-dataset)
- **Description**: This dataset includes various player attributes like position, overall rating, potential, market value, and additional metadata.

## Files
- **`Fifa23_analysis.ipynb`**: Jupyter Notebook containing the code for data analysis, regression modeling, and clustering.
- **`README.md`**: Project description and setup instructions.
- **`requirements.txt`**: List of dependencies required to run the project.

## Instructions
1. **Setup Environment**:
   - Make sure you have Python 3 installed.
   - Install the required libraries with:
     ```bash
     pip install -r requirements.txt
     ```

2. **Run the Notebook**:
   - Open `Fifa23_analysis.ipynb` in Jupyter Notebook or JupyterLab.
   - Follow along with the code cells to reproduce the analysis and models.

3. **Data Source**:
   - Download the dataset from Kaggle and place it in the project directory.

## Analysis Summary
- **Exploratory Data Analysis**: Insights into player distribution by position, rating, country, and other features.
- **Regression Models**: Predicting player value using linear and polynomial regression.
- **Clustering Analysis**: Segmenting players into clusters based on attributes to identify different playing styles.
- **World Cup Predictions**: Using player data to identify potential top teams for the World Cup.

## Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Results
This project provides insights into player characteristics, identifies top players across various positions, and predicts player values. By clustering players, we can segment them by playing style, and make data-based predictions on World Cup favorites.
