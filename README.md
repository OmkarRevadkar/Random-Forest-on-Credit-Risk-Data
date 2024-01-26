Random Forest(RF) Algorithm is a supervised learning classification algorithm. It is a collection of multiple decision trees. Hence more chances of getting better predictions than Decision Tree (DT) algorithm as prediction will be done on each tree in RF unlike on single tree in DT.
Target variable is in classes or categories. Sampling is possible and we have performed it on Credit Risk Dataset. 

Following steps are involved:

1. Import the necessary libraries in Jupyter notebook.
2. Load the dataset.
3. Perform Data Cleaning -- fill missing values, standardization, normalization, etc.
4. Random Sampling by splitting data into train and test data.
5. Build the model with Random Forest Classifier on train (fit on train).
6. Predict on test data.
7. Build the confusion matrix to be able to evaluate/judge the performance of our model.
8. Evaluate the model using various parameters like accuracy, recall, precision and f1 ratio along with the AUROC Curve.
9. Hyper Parameter Tuning to get the best results.

Interesting part is Random Forest And Decision Tree support feature selection method. We can know which features are important and accordingly peform hyper parameter tuning. We can work with other hyper parameters in RF like class_weight, min_samples_split, max_depth, n (sample no.) etc and tune them while checking for the best model results.


