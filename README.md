# 🎮 Steam Games Popularity Prediction 

This project uses machine learning to predict whether a computer game is popular or not, based on various features such as price, release date, genre, and review scores.

## 📊 Dataset
The dataset contains information about Steam games, including:
- Price
- Release date
- Genres and tags
- Review scores
- Number of owners (used to define popularity)

## 🎯 Goal
The goal of this project is to classify games as **popular** or **not popular**.  
A game is considered popular if its number of owners is above the median value.

## 🛠️ Feature Engineering
Several new features were created to improve model performance, such as:
- Game age (based on release year)
- Price categories (cheap, mid, expensive)
- Discount indicator (yes/no)
- Genre-based binary features
- Score categories (low, medium, high)

## 🤖 Model
The model used in this project is **K-Nearest Neighbors (KNN)**.

Steps:
- Data preprocessing and cleaning
- Train/test split (80/20)
- Feature scaling using StandardScaler
- Model training and evaluation

## 📈 Evaluation
The model was evaluated using:
- Accuracy
- Classification report

Final accuracy is around **80%**, which is considered a good result for this task.

## 🔍 Improvements (Bonus)
Additional improvements include:
- Grid Search with 5-fold cross-validation to tune hyperparameters
- Comparison between different feature sets
- Selection of the best model based on validation results

## ⚙️ Requirements
To run this project, install the following libraries:

```bash
pip install -r requirements.txt
