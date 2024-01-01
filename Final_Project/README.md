# Machine learning models on the MNIST dataset

* The MNIST dataset is a widely-used collection of 28x28 pixel grayscale images of handwritten digits (0 to 9), commonly used for training and testing image processing systems. It consists of 60,000 training images and 10,000 testing images, making it a benchmark dataset for developing and evaluating machine learning models, particularly in the field of digit recognition.

* There are several steps involving the project:
  1. Apply PCA to the training data to find the transformation into a lower dimensional space. How many dimensions do we need to explain 90% of the total variation in the data? Apply the SAME centering and projection to the test data, What dimension did we embed into?
  2. Run K-NN on the original data and the reduced dimension data from PCA, Using 10-fold cross-validation repeated 4 times to tune K • Consider K = 1, 2, 3, 4, 5 in the repeated CV. Including a running time evaluation.
* Comparing across classifiers:
  1. The specified classifiers for this analysis include Linear SVM, Radial Basis SVM, Random Forest, LDA, and QDA.
  2. Utilize 10-fold cross-validation repeated 5 times to fine-tune the parameters. Compare the models based on both test accuracy and running time.
* Clustering
  1. Download the Mall Customer Segmentation Data from our GitHub repo, determine the optimum "k" value using the elbow method, and visualize the determined categories with a 3D plot (Age vs. Income vs. Spending Score). Play with view angles to see the two groups of high-income people (making more than $80k).
     * GitHub Repo Link: https://raw.githubusercontent.com/ekacar1/Data_for_Lectures/main/Mall_Customers.csv
* Create a new set of toy datasets for regression problems. Come up with your ideas on different datasets of varying difficulty, that would help you compare the pros & cons of different algorithms. Use these datasets to visualize LinearRegression, Support Vector Regression, Nearest Neighbor Regression, and Decision Trees
     
