

# 🍷 Wine Quality Prediction

Predicting the quality score (0–10) of red wine based on its chemical properties using Machine Learning.

## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Project Objectives](#project-objectives)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Model Building](#model-building)
* [Results](#results)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

## 📝 Introduction

The **Wine Quality Prediction** project aims to build a machine learning model to predict the quality score of red wine (on a scale of 0 to 10) using its physicochemical attributes. Accurate wine quality prediction is useful for wine producers and quality assurance to maintain standards and improve production processes.



## 📊 Dataset

* **Source:** UCI Machine Learning Repository
* **Dataset:** [Wine Quality Data Set (Red Wine)](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
* **Attributes:**

  * Fixed acidity
  * Volatile acidity
  * Citric acid
  * Residual sugar
  * Chlorides
  * Free sulfur dioxide
  * Total sulfur dioxide
  * Density
  * pH
  * Sulphates
  * Alcohol
  * **Target:** Quality (score between 0 and 10)



## 🎯 Project Objectives

✅ Load and explore the wine dataset

✅ Perform exploratory data analysis (EDA)

✅ Preprocess data (handle missing values, normalization, feature selection)

✅ Build and train regression models (Linear Regression, Random Forest, etc.)

✅ Evaluate and compare model performance

✅ Predict wine quality from new input data



## 🛠️ Technologies Used

* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/wine_quality_prediction.git
cd wine_quality_prediction
```

2. **Create virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate      # On Linux/Mac
venv\Scripts\activate         # On Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```



## ▶️ Usage

1. **Run the Jupyter Notebook**

```bash
jupyter notebook Wine_Quality_Prediction.ipynb
```

2. **Follow the notebook steps to:**

* Explore data
* Train models
* Evaluate results
* Make predictions on new wine samples



## 🏗️ Model Building

The following models were implemented and compared:

| Model                 | Description                            |
| --------------------- | -------------------------------------- |
| **Linear Regression** | Baseline regression model              |
| **Random Forest**     | Ensemble method for better accuracy    |
| **Decision Tree**     | Interpretable tree-based model         |
| **Gradient Boosting** | Boosted trees for improved performance |

**Evaluation Metrics:**

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score



## 📈 Results

* **Best performing model:** Random Forest Regressor
* **RMSE:** *Value here*
* **R² Score:** *Value here*

> The Random Forest model achieved the highest predictive performance due to its ability to handle non-linearity and feature interactions.



## 🤝 Contributing

Contributions are welcome to improve models, add deployment scripts, or integrate with APIs for real-time wine quality prediction.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi501@gmail.com.com)



### ⭐️ If you find this project useful, please give it a star




