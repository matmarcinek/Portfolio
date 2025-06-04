# Portfolio 
### 🏙️[Project 1: AirBnb New York Market Analysis](https://github.com/matmarcinek/AirBnb)

A concise data analysis project exploring Airbnb listings in New York City using Python and Tableau.

### 🔍 Overview
- Analyzed Airbnb data with **Python** (Pandas, Seaborn, Matplotlib)
- Visualized key trends using **Tableau**
- Explored **pricing**, **room types**, and **neighborhood distributions**

### 🛠 Tools & Technologies
- **Python** – Pandas, Seaborn, Matplotlib
- **Jupyter Notebook**
- **Tableau Desktop**


### 🏙️[Project 2: Decoding the Cubs Offensive Performance Through Data](https://github.com/matmarcinek/Decoding-the-Cubs-Offensive-Performance-Through-Data)


### 🔍 Overview
This project explores the offensive performance of the Chicago Cubs using **PostgreSQL** queries on Major League Baseball data. The analysis covers key player statistics, team-wide metrics, and historical trends to highlight standout performances and long-term contributors to the franchise.
The entire analysis was performed using SQL and dashboard development in tools like **Power BI**  .

### 🛠 Tools & Technologies
- **PostgreSQL** – Querying and aggregation
- **Window Functions** – For ranking and time-based analysis
- **Common Table Expressions (CTEs)** – For streak and cohort calculations
  
- **Power BI** Analysis Overview  
For the dashboard portion of this project, the original MLB dataset was cleaned, transformed, and structured into a robust data model.

### 🔄 Data Preparation:
- ✅ **CSV Segmentation**: The original dataset was split into four focused CSV files:
  - `teams.csv` – Team-level details
  - `players.csv` – Player identifiers and names
  - `seasons.csv` – Seasonal breakdowns
  - `stats.csv` – Offensive statistics (HRs, AVG, OPS, etc.)
- 🌐 **Web Scraping**: Attendance data across seasons was scraped from a [reliable source](https://www.baseball-reference.com/teams/CHC/attend.shtml) and added to the model to analyze fan engagement over time.
- 🔗 **Data Modeling**: All sources were connected in Power BI through relationships and lookups to create a unified star schema optimized for analysis.


### 🫀[Project 3 Heart Disease Prediction using Machine Learning](https://github.com/matmarcinek/Heart-Disease-Prediction-using-Machine-Learning)

### 🔍 Problem Statement
The objective is to predict whether a patient has heart disease (binary classification) using features such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and other clinical data.


### 🧾 Dataset
Source: Kaggle – Heart Disease Classification Dataset

Attributes used: 14 (including age, sex, cp, chol, thalach, etc.)

Target: 1 indicates presence of heart disease, 0 indicates absence


### ⚙️ Workflow
Exploratory Data Analysis (EDA)

Model Building: Multiple classifiers including Logistic Regression, Random Forest, and K-Nearest Neighbors

Model Evaluation: Accuracy, precision, recall, F1-score

Cross-Validation & Hyperparameter Tuning

Feature Importance Analysis


### 🧪 Tools & Libraries
**Python** (**Pandas**, **NumPy**)

Visualization: **Matplotlib**, **Seaborn**

Machine Learning: **Scikit-learn**


### ✅ Outcome
The best-performing model reached accuracy close to 90%, showcasing effective feature usage and model tuning


# 🍔 Food Image Classification Using Deep Learning

## 🔍 Problem Statement  
The goal of this project is to classify images of food into 3 different categories using deep learning. Accurate food classification can be applied in nutrition tracking apps, smart kitchen assistants, or restaurant recommendation systems.

---

## 🧾 Dataset  
- **Source:** [Food-101 Dataset – ETH Zurich](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/)  
- **Classes:** 101 food categories (e.g., pizza, burger, sushi, pad thai)  
- **Size:** 101,000 images (750 training + 250 testing images per class)  
- **Structure:** Organized in folders per class with separate train/test splits

For this project only 3 food categories and 10% of dataset was used.

---

## ⚙️ Workflow  
- Data Loading and Directory Structuring  
- Image Preprocessing & Augmentation with `ImageDataGenerator`  
- Model Design:  
  - Custom Convolutional Neural Network (CNN)  
  - Transfer Learning with **MobileNetV2**  
- Model Training and Evaluation  
- Visualization of Training & Validation Accuracy/Loss

---

## 🧪 Tools & Libraries  
- **Python**
- **TensorFlow**, **Keras** – Deep learning framework  
- **NumPy**, **Pandas** – Data manipulation  
- **Matplotlib** – Visualization  
- **ImageDataGenerator** – Real-time image augmentation

---

## ✅ Outcome  
- Achieved high validation accuracy on a complex multi-class image dataset  
- Transfer Learning with MobileNetV2 improved performance and reduced training time  
- This project highlights the practical use of CNNs for real-world image classification challenges

---


## 🚀 Future Work  
- Integrate with a web app for real-time food recognition  
- Implement additional architectures (e.g., ResNet, EfficientNet)  
- Experiment with model quantization for mobile deployment

---

> 👨‍🍳 This project serves as a foundation for AI-based food recognition systems across health, diet, and hospitality domains.






