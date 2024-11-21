# Network Intrusion Detection with Machine Learning

## Project Description

This project aims to develop a robust Network Intrusion Detection System (NIDS) by leveraging machine learning algorithms. The system is trained using the KDD Cup 1999 dataset, a widely recognized benchmark for network intrusion detection. By analyzing network traffic patterns, the NIDS classifies connections as either normal or malicious (attack).

## Key Features

- **Data Preprocessing:** Handles missing values, removes duplicates, and transforms categorical features for optimal model performance.
- **Exploratory Data Analysis:** Provides insights into data distribution, feature relationships, and potential outliers through visualizations like histograms, scatter plots, and boxplots.
- **Feature Engineering:** Enables the creation of new features that may improve the model's ability to identify intrusions.
- **Machine Learning Models:** Utilizes a variety of classification algorithms, including Logistic Regression, Support Vector Machines, and Random Forest, for intrusion detection.
- **Model Evaluation:** Assesses the performance of the trained models using metrics like accuracy, precision, recall, and F1-score.
- **Scalability:** Designed to handle large datasets and potentially real-time network traffic analysis.

## Dataset

The project relies on the KDD Cup 1999 dataset, a publicly available dataset from the UCI Machine Learning Repository. This dataset contains a diverse range of network intrusion scenarios, making it suitable for training and evaluating intrusion detection models.

## Technologies Used

- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

## Installation

1. Clone the repository: `git clone [repository URL]`
2. Install required libraries: `pip install -r requirements.txt`
3. Download the KDD Cup 1999 dataset and place it in the designated data directory.

## Usage

1. Execute the Jupyter Notebook `intrusion_detection.ipynb` to run the project.
2. Modify parameters and experiment with different models as needed.

## Author

Nafis Emran Khan, Dipalok Sen, Anik Kanti Bormon
