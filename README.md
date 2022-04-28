# malicious-domain-classification

This project explores the application of supervised learning techniques to the problem of classifying malicious domains that are used by threat actors for phishing, malware distribution, etc.

## Requirements

This project has the following dependencies: sklearn, pandas, and Jupyter Notebooks/IPython

These requirements can be met by installing Anaconda: https://www.anaconda.com/products/distribution

## Dataset

The dataset used for this project (dataset.csv) can be found here: https://data.mendeley.com/datasets/623sshkdrz/5

The dataset contains 90,000 datapoints and is balanced such that 50% of the domains are benign and 50% are malicious.

The dataset features include information from DNS and WHOIS records, lexical features of the domains, and data gathered from other sources including domain/IP reputation databases.

## Usage

The results of this project can be replicated by opening and running each of the provided notebook files.
Each notebook contains comments explaining each procedure and considering the results.

### preprocessing.ipynb

In this notebook the original dataset (dataset.csv) is preprocessed and the file preprocessed.csv is produced.

### mlpclassification.ipynb

In this notebook a multi layer perceptron (MLP) classifier is created and analyzed.

### randomforest.ipynb

In this notebook a random forest (RF) classifier is created and analyzed. 
