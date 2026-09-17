# 📱 SMS Spam Clustering

A machine learning project that applies **text preprocessing and clustering techniques** to analyze patterns in SMS messages from the `SMSSpamCollection` dataset.

## 📌 Project Overview

The rapid growth of digital communication has increased the amount of unwanted and potentially harmful messages received by users. Analyzing SMS message patterns can help identify groups of messages with similar characteristics.

This project explores the use of **unsupervised machine learning** to group SMS messages based on their textual characteristics.

The project was developed using **Python** in **Google Colab**.

## 🎯 Objectives

The main objectives of this project are:

* Explore and understand the `SMSSpamCollection` dataset.
* Perform text preprocessing on SMS messages.
* Convert text data into numerical representations.
* Apply clustering techniques to group similar SMS messages.
* Visualize the resulting clusters.
* Analyze the characteristics and patterns of each cluster.

## 📊 Dataset

The project uses the **SMSSpamCollection** dataset, which contains SMS messages along with their original labels.

The dataset consists of two main columns:

| Column    | Description               |
| --------- | ------------------------- |
| `label`   | Original message category |
| `message` | SMS text content          |

The original labels include:

* `ham` → legitimate SMS messages
* `spam` → unwanted SMS messages

Although the original dataset contains labels, the clustering process focuses on **unsupervised grouping** based on the characteristics of the SMS text.

## 🔎 Exploratory Data Analysis

Exploratory analysis was performed to understand the characteristics of the SMS messages.

The analysis includes:

* Checking dataset dimensions
* Checking data types
* Examining class distribution
* Analyzing message length
* Exploring frequently occurring words
* Examining patterns in SMS content

These steps help provide an initial understanding of the dataset before applying text clustering.

## 🧹 Text Preprocessing

Text data needs to be transformed before it can be processed by a machine learning algorithm.

The preprocessing workflow includes steps such as:

* Converting text to lowercase
* Removing unnecessary characters
* Cleaning text
* Tokenizing text
* Removing stopwords when appropriate
* Preparing the text for feature extraction

The goal is to reduce noise and create a cleaner representation of the SMS messages.

## 🔢 Text Feature Extraction

The cleaned SMS messages are transformed into numerical features so that they can be processed by machine learning algorithms.

A text vectorization technique such as **TF-IDF (Term Frequency–Inverse Document Frequency)** can be used to represent the importance of words within the dataset.

The general process is:

```text
SMS Messages
      ↓
Text Cleaning
      ↓
Tokenization
      ↓
Text Vectorization
      ↓
Numerical Feature Matrix
      ↓
Clustering
```

## 🤖 Clustering

This project applies an **unsupervised learning approach** to identify groups of SMS messages with similar textual characteristics.

Unlike supervised classification, clustering does not require the model to learn directly from the original `ham` and `spam` labels.

The clustering workflow is:

```text
SMS Dataset
     ↓
Text Preprocessing
     ↓
Feature Extraction
     ↓
Clustering Algorithm
     ↓
Cluster Assignment
     ↓
Cluster Analysis
```

The resulting clusters are then analyzed to understand the dominant characteristics of the messages within each group.

## 📈 Cluster Visualization

Visualization is used to make the clustering results easier to interpret.

Because text data can contain a large number of features, dimensionality reduction techniques can be applied to project the data into a lower-dimensional space for visualization.

The visualization helps examine:

* Cluster distribution
* Similarity between messages
* Separation between clusters
* Potential overlap between groups

## 💡 Key Insights

The clustering analysis provides an overview of how SMS messages can be grouped based on their textual characteristics.

The project demonstrates that text data can be transformed into numerical features and analyzed using unsupervised machine learning techniques.

Through this project, I practiced:

* Text data preprocessing
* Natural Language Processing (NLP)
* Feature extraction
* Unsupervised machine learning
* Clustering
* Data visualization
* Python-based data analysis

## 🛠️ Tools & Technologies

* **Python**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **NLTK** *(if used in the notebook)*

## 📁 Repository Structure

```text
sms-spam-clustering/
│
├── SMSSpamCollection_Clustering.ipynb
└── README.md
```

## 🚀 Future Improvements

Possible improvements for this project include:

* Comparing different clustering algorithms.
* Optimizing the number of clusters.
* Applying dimensionality reduction techniques such as PCA or t-SNE.
* Evaluating cluster quality using appropriate clustering metrics.
* Performing deeper analysis of words and phrases within each cluster.
* Developing an interactive visualization or dashboard.
* Building a text classification model as a supervised learning comparison.

## 📚 Learning Outcomes

This project provided practical experience in applying machine learning techniques to unstructured text data.

The main skills demonstrated include:

```text
Python
  ↓
Data Cleaning
  ↓
NLP / Text Preprocessing
  ↓
Feature Engineering
  ↓
TF-IDF
  ↓
Clustering
  ↓
Visualization
  ↓
Data Interpretation
```

## 👩‍💻 Author

**Agustina Sri Astuti, S.Kom., M.Kom.**

IT Business Analyst | Business Process & System Analysis

📍 Bandar Lampung, Indonesia

---

⭐ This project is part of my portfolio to demonstrate practical skills in **Python, Data Analysis, Natural Language Processing, and Machine Learning**.
