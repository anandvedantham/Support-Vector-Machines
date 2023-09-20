# Support-Vector-Machines

 Support Vector Machine (SVM) is a supervised machine learning algorithm used for classification and regression tasks. It is a powerful and versatile algorithm that works well for both linear and non-linear data separation. SVMs are particularly popular in the field of machine learning and have been widely used in various applications, including image classification, text classification, and bioinformatics. At its core, an SVM aims to find the optimal hyperplane that best separates data points into different classes. In a two-dimensional space, this hyperplane is a simple line, while in higher dimensions, it becomes a hyperplane.

 The margin is the distance between the hyperplane and the nearest data point from each class. SVM tries to maximize this margin because it provides a larger buffer zone and, in turn, better generalization to unseen data.Support vectors are the data points that are closest to the hyperplane and influence its position and orientation. These are the most critical data points in SVM, and they determine the margin.Support Vector Machines have several advantages, including their effectiveness in high-dimensional spaces, robustness against overfitting (especially in the case of a well-chosen kernel), and the ability to handle both linear and non-linear data. However, they may not scale well to very large datasets, and selecting the right kernel and tuning hyperparameters can be challenging.

 ## Implementation
 
- Importing the required Libraries
- Reading the dataset
- Performing EDA on the dataset
- Applying Visualizations on the data
- Data Preprocessing
- Splitting the data into Train and Test data
- Standardization of the data
- Building SVM Classifier Model and finding the Accuracy
  - using Kernel - *'rbf'*
  - using Kernel - *'linear'*
  - using Kernel - *'poly'*
  - using Kernel - *'sigmoid'*
- Conclusion
  

## Packages Used

- pandas
- numpy
- seaborn
- matplotlib.pyplot
- warnings
- from sklearn import svm
- from sklearn.svm import SVC
- from sklearn.preprocessing import StandardScaler, LabelEncoder
- from sklearn.model_selection import GridSearchCV, train_test_split, cross_val_score
- from sklearn.metrics import accuracy_score, confusion_matrix, classification_report
