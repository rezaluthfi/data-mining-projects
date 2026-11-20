# Data Mining Projects

A collection of data mining and machine learning projects implemented in Python using Jupyter Notebooks, covering exploratory data analysis, preprocessing, supervised learning, unsupervised learning, time series forecasting, imbalanced data handling, natural language processing, and computer vision.

## Projects

| Notebook | Topic | Key Techniques & Models | Datasets |
| :--- | :--- | :--- | :--- |
| [Exploratory_Data_Analysis.ipynb](./Exploratory_Data_Analysis.ipynb) | Exploratory Data Analysis (EDA) | Line chart, pie chart, bar & stacked bar plot, histogram, scatter plot, box plot, violin plot, subplots, annotations, legends | Credit Card Customers (BankChurners), IoT Occupancy Sensor |
| [Data_Preprocessing.ipynb](./Data_Preprocessing.ipynb) | Data Preprocessing | Descriptive statistics, correlation analysis, missing value imputation, duplicate removal, one-hot & label encoding, train-test split, standardization, normalization | Titanic |
| [EDA_and_Data_Preprocessing.ipynb](./EDA_and_Data_Preprocessing.ipynb) | End-to-End EDA & Preprocessing | Full exploratory visualization workflow combined with data cleaning, feature encoding, and scaling | BankChurners, IoT Occupancy Sensor, Titanic, Bengaluru House Price |
| [Classification_Models.ipynb](./Classification_Models.ipynb) | Classification | Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Random Forest, AdaBoost, Confusion Matrix, Accuracy, Precision, Recall | Stroke Prediction, Loan Status Prediction |
| [Regression_Models.ipynb](./Regression_Models.ipynb) | Regression | Linear Regression, Decision Tree Regressor, Random Forest Regressor, MSE, RMSE, $R^2$ | King County House Prices, Car Price Prediction |
| [Time_Series_Forecasting.ipynb](./Time_Series_Forecasting.ipynb) | Time Series Forecasting | Sliding window sequence generation, statistical feature extraction, MLP, KNN, Decision Tree, SVR, Random Forest, RMSE & Pearson correlation | Bike Sharing Daily, Tesla Stock (TSLA) |
| [Clustering_KMeans_KMedoids.ipynb](./Clustering_KMeans_KMedoids.ipynb) | Clustering | K-Means, K-Medoids, Elbow/Knee Method (`kneed`), Silhouette Score, 2D & 3D cluster visualization | Credit Card Customers, Air Traffic Passenger Statistics |
| [Imbalanced_Data_Handling.ipynb](./Imbalanced_Data_Handling.ipynb) | Imbalanced Data Handling | RandomUnderSampler, RandomOverSampler, SMOTE, ADASYN, before-vs-after balancing evaluation with Random Forest | Stroke Prediction, Bank Churn Modelling |
| [MLP_Classification_and_Regression.ipynb](./MLP_Classification_and_Regression.ipynb) | Neural Networks (MLP) | Multilayer Perceptron (`MLPClassifier`, `MLPRegressor`), feature scaling, multi-layer architecture evaluation | BankChurners, Diabetes, King County House Prices, Boston Housing |
| [Text_Mining_Sentiment_Analysis.ipynb](./Text_Mining_Sentiment_Analysis.ipynb) | Text Mining & NLP | Tokenization, stopword removal, stemming, lemmatization (NLTK), Bag of Words, TF-IDF, WordCloud, Naive Bayes, Random Forest | Twitter Airline Sentiment |
| [Image_Classification_CNN.ipynb](./Image_Classification_CNN.ipynb) | Image Classification (CNN) | Image augmentation (`ImageDataGenerator`), Convolutional Neural Network (`Conv2D`, `MaxPooling2D`, `Dropout`, `Dense`), training & validation curves | Image Classification Dataset |

## Tech Stack

- **Language:** Python 3
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly, WordCloud
- **Machine Learning:** Scikit-learn, Scikit-learn-extra, imbalanced-learn, Kneed
- **NLP & Deep Learning:** NLTK, TensorFlow / Keras

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/rezaluthfi/data-mining-projects.git
   cd data-mining-projects
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn scikit-learn-extra imbalanced-learn kneed nltk wordcloud tensorflow jupyter
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
