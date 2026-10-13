# student-placement-prediction

# Student Placement Prediction using Machine Learning

A beginner-friendly Machine Learning project built in Python to predict whether a student will be placed or not based on academic and technical performance metrics.

## 🚀 Project Overview
This project uses a **Decision Tree Classifier** to analyze student attributes and predict career placement outcomes (Placed / Not Placed). 

### Features Analyzed ($X$):
* **CGPA**
* **Skills** rating
* **Projects** completed
* **Internships** completed
* **Certifications** earned
* **DSA_Score** (Data Structures and Algorithms score)

### Target Variable ($y$):
* **Placed**: `1` for Placed, `0` for Not Placed

## 🛠️ Tech Stack & Libraries
* **Python**
* **Pandas** (for data manipulation and creating DataFrames)
* **Scikit-Learn** (for data splitting, model training, and accuracy evaluation)

## 💻 Code Summary
1. Loads a dataset of student records into a Pandas DataFrame].
2. Splits the dataset into training and testing subsets using `train_test_split` (`test_size=0.2`).
3. Trains a `DecisionTreeClassifier` model.
4. Evaluates model performance using `accuracy_score`.
5. Tests the model on a completely new student profile to output a real-time placement prediction (`PLACED ✅` or `NOT PLACED ❌`).

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
