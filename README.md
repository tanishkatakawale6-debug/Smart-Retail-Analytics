# Smart Retail Analytics Using Data Mining

A data-driven retail analytics project that applies machine learning and data mining techniques to analyze customer purchasing behaviour, identify shopping patterns, segment customers, and predict high-value customers.

## Project Overview

Retail businesses generate large amounts of transactional data. Analyzing this information helps businesses understand customer preferences, purchasing frequency, product relationships, and customer value.

This project uses the **UCI Online Retail Dataset** to explore customer behaviour through data preprocessing, exploratory data analysis, similarity analysis, clustering, association rule mining, and classification.

## Objectives

- Analyze retail transaction data and customer purchasing patterns.
- Segment customers based on purchasing behaviour.
- Identify relationships between frequently purchased products.
- Classify customers based on their purchasing value.
- Visualize analytical results for better interpretation.

## Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Development Environment | Google Colab / Jupyter Notebook |
| Data Processing | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Association Rule Mining | Mlxtend |
| Dataset | UCI Online Retail Dataset |

## Methodology

### 1. Data Preprocessing and Exploratory Analysis

The retail dataset is loaded, cleaned, and transformed into a suitable format for analysis.

Customer behaviour is analyzed using RFM metrics:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How frequently a customer purchases.
- **Monetary:** How much money a customer spends.

### 2. Similarity Analysis

Euclidean Distance and Jaccard Similarity are used to measure similarities and differences between customer records.

### 3. Customer Segmentation

**K-Means** and **DBSCAN** clustering algorithms are applied to group customers according to their purchasing behaviour.

The Elbow Method is used to help determine a suitable number of clusters for K-Means.

### 4. Association Rule Mining

**Apriori** and **FP-Growth** algorithms are used to discover relationships between products purchased together.

Association rules are analyzed using measures such as support, confidence, and lift.

### 5. Customer Classification

**Naive Bayes** and **Support Vector Machine (SVM)** algorithms are applied to classify customers based on purchasing behaviour.

Model performance is evaluated using suitable classification metrics.

## Dataset

**Source:** UCI Machine Learning Repository — Online Retail Dataset

The dataset contains retail transaction records with attributes including invoice number, product description, quantity, invoice date, unit price, customer ID, and country.

Dataset link: https://archive.ics.uci.edu/dataset/352/online+retail

## Project Structure

```text
Smart-Retail-Analytics/
├── Final Project.ipynb
├── Online_Retail.xlsx
├── Final Lab Project DM.docx
└── README.md
```

## How to Run

1. Download the repository or open the notebook in Google Colab.
2. Upload `Online_Retail.xlsx` to the notebook's working directory.
3. Install any missing Python libraries.
4. Open `Final Project.ipynb`.
5. Execute the notebook cells sequentially.
6. View the generated graphs, clustering results, association rules, and classification results.

## Applications

- Customer segmentation and targeted marketing
- Customer value analysis
- Product recommendation insights
- Retail sales analysis
- Customer purchasing behaviour prediction

## Conclusion

This project demonstrates how data mining techniques can transform retail transaction data into useful business insights. By combining clustering, association rule mining, and classification, the analysis supports better understanding of customer behaviour and retail purchasing patterns.


## Acknowledgment

This academic implementation is based on the open-source [Retail Intelligence Pipeline](https://github.com/Maira-Fatima/Retail-Intelligence-Pipeline). The original project and its contributors are acknowledged for the foundational implementation.

Dataset credit: UCI Machine Learning Repository.
