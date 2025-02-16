# Rotten Tomatoes Movie Analysis

## Project Overview
This project analyzes a dataset of movies from Rotten Tomatoes to gain insights into audience ratings and other key attributes. The goal is to preprocess the data, explore patterns, and apply machine learning techniques to predict audience ratings based on various features.

## Dataset
The dataset used in this project is `Rotten_Tomatoes_Movies3.csv`. It contains various attributes of movies, including:
- Movie title
- Movie information
- Critics' consensus
- Writers
- Release dates (in theaters and streaming)
- Studio name
- Audience rating (target variable)

### Dataset Source
The dataset can be found on Kaggle: [Rotten Tomatoes Movies Dataset](https://www.kaggle.com/datasets/pranavvkathar/rotten-tomatoes-movies3-csv)

## Data Preprocessing
The data undergoes multiple preprocessing steps to ensure quality and usability:
- **Removing unnecessary columns** to retain only relevant data.
- **Handling missing values** by filling or dropping as needed.
- **Removing duplicates** to maintain data integrity.
- **Separating numerical and categorical columns** for better processing.
- **Encoding categorical features** using Label Encoding and Category Encoders.
- **Scaling numerical features** using Standard Scaler to normalize values.

## Exploratory Data Analysis (EDA)
We explore trends and insights using visualization and statistics:
- Distribution of audience ratings
- Correlation between different features
- Impact of categorical variables on ratings

## Machine Learning Models
We build predictive models to estimate audience ratings:
- Feature engineering and selection
- Applying machine learning algorithms using Scikit-learn
- Evaluating model performance

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn

## How to Use
1. Clone the repository or download the notebook.
2. Run the Jupyter Notebook to preprocess the data and train models.

## Future Improvements
- Adding advanced machine learning models for better accuracy.
- Hyperparameter tuning to optimize model performance.
- Deploying the model as a web application.
  
