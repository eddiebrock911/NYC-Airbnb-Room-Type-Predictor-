# 🏙️ NYC Airbnb Room Type Predictor

<p align="center">
  <strong>Machine Learning • Classification • Data Science • Predictive Analytics</strong>
</p>

<p align="center">
  A Machine Learning project that analyzes NYC Airbnb listing data and predicts the room type of an Airbnb listing.
</p>

<p align="center">
  <a href="https://github.com/eddiebrock911/NYC-Airbnb-Room-Type-Predictor-">💻 GitHub Repository</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Machine%20Learning-Classification-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Data%20Visualization-Matplotlib%20%7C%20Seaborn-4C72B0?style=for-the-badge">
</p>

---

## 📌 Overview

**NYC Airbnb Room Type Predictor** is a Machine Learning classification project built using NYC Airbnb listing data.

The main objective is to learn patterns from Airbnb listing features and use those patterns to predict the **room type** of a listing.

The project follows a standard end-to-end Machine Learning workflow:

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Exploratory Data Analysis
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Data Preprocessing
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Room Type Prediction
```

The project is listed under the **Machine Learning Projects** category in a public AI project collection.

---

## 🎯 Problem Statement

Airbnb listings contain many attributes related to properties, hosts, locations, pricing, reviews, and availability.

One useful classification problem is:

> **Given the characteristics of an Airbnb listing, can a Machine Learning model predict its room type?**

This project explores that problem using NYC Airbnb data.

---

## 🏠 Prediction Target

The target variable is the **room type** of an Airbnb listing.

Typical room-type categories in NYC Airbnb datasets include:

```text
🏠 Entire home/apt
🛏️ Private room
🚪 Shared room
```

The exact classes depend on the dataset used by the project.

---

## 🧠 Machine Learning Pipeline

```text
                    NYC Airbnb Dataset
                            │
                            ▼
                 ┌────────────────────┐
                 │ Data Exploration   │
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │ Data Cleaning      │
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │ Feature Engineering│
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │ Preprocessing      │
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │ Classification     │
                 │ Model              │
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │ Room Type          │
                 │ Prediction         │
                 └────────────────────┘
```

---

## 📊 Dataset Features

Depending on the dataset version, Airbnb listing data can contain features such as:

| Feature Category | Examples                           |
| ---------------- | ---------------------------------- |
| Location         | Latitude, Longitude, Neighbourhood |
| Property         | Room Type                          |
| Pricing          | Price                              |
| Reviews          | Number of Reviews                  |
| Availability     | Availability in Days               |
| Booking          | Minimum Nights                     |
| Host             | Host-related information           |
| Activity         | Reviews per Month                  |

These features can be analyzed to identify patterns associated with different room types.

---

## 🔍 Exploratory Data Analysis

Exploratory Data Analysis helps understand the structure and distribution of the Airbnb dataset before training a model.

Important areas include:

### Room Type Distribution

```text
Room Type
   │
   ├── Entire Home / Apartment
   ├── Private Room
   └── Shared Room
```

### Location Analysis

NYC Airbnb listings can be analyzed according to:

* Boroughs
* Neighbourhoods
* Geographic coordinates
* Listing density

### Price Analysis

Price distributions can help identify differences between various types of Airbnb listings.

### Review Analysis

Review-related features can provide additional information about listing activity and popularity.

---

## 🧹 Data Preprocessing

Machine Learning models require clean and properly formatted data.

A typical preprocessing workflow is:

```text
Raw Data
   ↓
Missing Value Detection
   ↓
Missing Value Handling
   ↓
Duplicate Detection
   ↓
Feature Selection
   ↓
Categorical Encoding
   ↓
Numerical Processing
   ↓
Training Dataset
```

Depending on the feature types, preprocessing may include:

* Handling missing values
* Encoding categorical variables
* Scaling numerical features where required
* Removing irrelevant columns
* Handling outliers
* Selecting useful features

---

## 🤖 Classification Problem

This project is a **supervised Machine Learning classification problem**.

The model learns:

```text
Airbnb Listing Features
          ↓
     ML Algorithm
          ↓
     Room Type Class
```

After training, the classifier can be used to predict the room type of an unseen listing.

---

## 📈 Model Evaluation

A classification model should be evaluated using more than a single metric.

Useful metrics include:

| Metric           | Description                               |
| ---------------- | ----------------------------------------- |
| Accuracy         | Overall percentage of correct predictions |
| Precision        | Correctness of positive predictions       |
| Recall           | Ability to identify a class               |
| F1 Score         | Balance between precision and recall      |
| Confusion Matrix | Detailed class-level performance          |

### Confusion Matrix

```text
                 Predicted
              ┌─────┬─────┬─────┐
              │ C1  │ C2  │ C3  │
Actual    C1  │ ✓   │     │     │
          C2  │     │ ✓   │     │
          C3  │     │     │ ✓   │
              └─────┴─────┴─────┘
```

A confusion matrix is especially useful when the dataset contains multiple room-type classes.

---

## 🛠️ Technology Stack

### Programming

* Python

### Data Processing

* Pandas
* NumPy

### Machine Learning

* Scikit-learn
* Classification algorithms
* Feature preprocessing
* Model evaluation

### Visualization

* Matplotlib
* Seaborn

### Development

* Jupyter Notebook
* Git
* GitHub

---

## 🔄 End-to-End Workflow

```text
1. Collect Dataset
       ↓
2. Understand Dataset
       ↓
3. Perform EDA
       ↓
4. Clean Data
       ↓
5. Prepare Features
       ↓
6. Encode Categorical Data
       ↓
7. Split Dataset
       ↓
8. Train Classification Model
       ↓
9. Evaluate Model
       ↓
10. Generate Predictions
```

---

## 💻 Repository

**GitHub:**
https://github.com/eddiebrock911/NYC-Airbnb-Room-Type-Predictor-

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/eddiebrock911/NYC-Airbnb-Room-Type-Predictor-.git
```

### Enter the Project

```bash
cd NYC-Airbnb-Room-Type-Predictor-
```

### Create Virtual Environment

#### Windows

```bash
python -m venv venv
```

Activate:

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv venv
```

Activate:

```bash
source venv/bin/activate
```

---

## 📦 Install Dependencies

If the repository contains a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

The exact command depends on the application/notebook included in the repository.

For a Python application:

```bash
python app.py
```

For a Streamlit application:

```bash
streamlit run app.py
```

For notebook-based experimentation:

```bash
jupyter notebook
```

---

## 🧪 Model Development

The Machine Learning development process can be summarized as:

```text
Dataset
   ↓
EDA
   ↓
Feature Engineering
   ↓
Preprocessing
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Evaluation
   ↓
Prediction
```

This structure makes the project useful for understanding how a real-world tabular dataset can be transformed into a predictive Machine Learning system.

---

## 🌆 Why NYC Airbnb Data?

NYC Airbnb data is a useful Machine Learning dataset because it combines:

* Geographic information
* Numerical features
* Categorical features
* Pricing information
* Review activity
* Availability information

This makes it suitable for practicing several important Data Science concepts at once.

---

## 🎯 Learning Objectives

This project demonstrates practical experience with:

* Machine Learning classification
* Exploratory Data Analysis
* Data cleaning
* Feature engineering
* Categorical data handling
* Numerical data processing
* Model evaluation
* Predictive analytics
* Real-world tabular datasets

---

## 📚 Skills Demonstrated

```text
Python
  ↓
Pandas / NumPy
  ↓
Data Cleaning
  ↓
EDA
  ↓
Feature Engineering
  ↓
Machine Learning
  ↓
Classification
  ↓
Model Evaluation
  ↓
Prediction
```

---

## 🔮 Future Improvements

Potential improvements for the project:

* [ ] Add an interactive prediction interface
* [ ] Add prediction probability
* [ ] Add feature importance visualization
* [ ] Compare multiple ML algorithms
* [ ] Add hyperparameter tuning
* [ ] Add cross-validation
* [ ] Add automated preprocessing pipeline
* [ ] Add model versioning
* [ ] Add REST API
* [ ] Add FastAPI backend
* [ ] Add Streamlit frontend
* [ ] Add Docker support
* [ ] Add automated testing
* [ ] Add GitHub Actions CI/CD
* [ ] Add model monitoring
* [ ] Add deployment

---

## 🚀 Advanced Architecture

A production-oriented version could use a complete preprocessing and prediction pipeline:

```text
                    User Input
                        │
                        ▼
              ┌──────────────────┐
              │ Input Validation │
              └────────┬─────────┘
                       │
                       ▼
              ┌──────────────────┐
              │ Preprocessing    │
              │ Pipeline         │
              └────────┬─────────┘
                       │
                       ▼
              ┌──────────────────┐
              │ ML Classifier    │
              └────────┬─────────┘
                       │
                       ▼
              ┌──────────────────┐
              │ Prediction +     │
              │ Probability      │
              └──────────────────┘
```

This would make the project easier to deploy as a production-ready Machine Learning application.

---

## ⚠️ Limitations

Predictions can be affected by:

* Missing information
* Incorrect input values
* Dataset imbalance
* Outliers
* Limited training data
* Geographic distribution
* Changes in Airbnb market behavior
* Features not represented in the dataset

A Machine Learning prediction should therefore be interpreted as a model output rather than a guaranteed result.

---

## 👨‍💻 Author

### Ankit

**AI / Machine Learning Developer**

GitHub:
https://github.com/eddiebrock911

Repository:
https://github.com/eddiebrock911/NYC-Airbnb-Room-Type-Predictor-

---

## ⭐ Support

If you find this project useful:

⭐ Star the repository
🍴 Fork the project
🐛 Report bugs
💡 Suggest improvements

---

## 📜 License

This project is intended for educational and portfolio purposes.

If the project uses external datasets or third-party resources, please check their respective licenses and terms before redistribution.

---

<p align="center">

<strong>🏙️ NYC Airbnb → 📊 Data → 🤖 ML → 🏠 Room Type</strong>

<br><br>

Built with <strong>Python • Pandas • Scikit-learn • Machine Learning</strong>

<br><br>

Made by <strong>Ankit</strong> 🚀

</p>
