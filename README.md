# Credit Card Fraud Detection

## Project Overview
This project implements various machine learning algorithms to detect fraudulent credit card transactions using a highly unbalanced dataset. The dataset contains 284,807 transactions made by European cardholders in September 2013, with only 492 frauds, accounting for 0.172% of all transactions.

### Problem Definition & Goals
The primary goal of this project is to develop a machine learning model that can accurately identify fraudulent transactions and minimize financial losses to credit card companies and customers. Given the highly imbalanced nature of the dataset, the Area Under the Precision-Recall Curve (AUPRC) is recommended as a performance metric.

### Data Exploration and Preprocessing Techniques
- Explored the dataset using visualizations such as histograms, box plots, and scatter plots to understand the relationship between different variables and the target variable (fraudulent transactions).
- Cleaned and preprocessed the data by removing duplicates, handling missing values, and selecting relevant features.
- Addressed the imbalance in the dataset using oversampling, undersampling, and weighted models.

### Experimental Results
Trained several machine learning models including:
1. KNN and KNN with SMOTE
2. SVM (Linear) and SVM (Linear) with SMOTE
3. SVM (Radial)
4. Random Forest
5. Gradient Boosted Model
6. Extreme Gradient Boosted Model
7. Neural Network Model
8. Neural Network Model with Class Weight

### Conclusion
Based on the analysis and model training, Random Forest achieved the highest accuracy of 99.99%.

## Dataset
The dataset used in this project is available on Kaggle: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## References
- Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi. Calibrating Probability with Undersampling for Unbalanced Classification. In Symposium on Computational Intelligence and Data Mining (CIDM), IEEE, 2015
- Dal Pozzolo, Andrea; Caelen, Olivier; Le Borgne, Yann-Ael; Waterschoot, Serge; Bontempi, Gianluca. Learned lessons in credit card fraud detection from a practitioner perspective, Expert systems with applications,41,10,4915-4928,2014, Pergamon
- Dal Pozzolo, Andrea; Boracchi, Giacomo; Caelen, Olivier; Alippi, Cesare; Bontempi, Gianluca. Credit card fraud detection: a realistic modeling and a novel learning strategy, IEEE transactions on neural networks and learning systems,29,8,3784- 3797,2018,IEEE
- Dal Pozzolo, Andrea Adaptive Machine learning for credit card fraud detection ULB MLG PhD thesis (supervised by G. Bontempi)

## Usage
1. Clone the repository.
2. Install the necessary dependencies (Python libraries).
3. Run the provided Jupyter Notebook or Python script to train and evaluate the machine learning models.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.