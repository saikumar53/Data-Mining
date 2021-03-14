All the datasets required to run the Knn, Decision tree, Random Forest and Naive Bayes are in the same folder
so, when you want to run the codes for these four classification algorithms, follow the below instructions.

1. K Nearest Neighbors
- Open the file name KNN.ipynb notebook in the Code folder.
- Run all the cells except the last cell which contain the main function.
- Give the dataset name in the file variable in the __main__() function. (file = 'project3_dataset1.txt')
- Then, run the last cell containing __main__() function.
- It will be prompted to enter the K value. Give the int value.
  ex - Enter the Number of Neighbors : 9
- Output will contain the accuracy, precision, recall an F1-score of the dataset calculated based on the algorithm.

2. Decision Tree
- Open the file name decision_tree.ipynb notebook in the Code folder.
- Run all the cells except the last cell which contain the main function.
- Give the dataset name in the file variable in the __main__() function. (file = 'project3_dataset1.txt')
- Then, run the last cell containing __main__() function.
- Output will contain the accuracy, precision, recall an F1-score of the dataset calculated based on the algorithm.

3. Random Forest
- Open the file name random_forest.ipynb notebook in the Code folder.
- Run all the cells except the last cell which contain the main function.
- Give the dataset name in the file variable in the __main__() function. (file = 'project3_dataset1.txt')
- Then, run the last cell containing __main__() function.
- It will be prompted to enter the number of tree and number of features to split value. Give the int values.
  ex - Enter the number of trees : 8
       Enter the number of features to split : 5
- Output will contain the accuracy, precision, recall an F1-score of the dataset calculated based on the algorithm.

4. Naive Bayes
- Open the file name Naive_Bayes.ipynb notebook in the Code folder.
- Run all the cells except the last cell which contain the main function.
- Give the dataset name in the file variable in the __main__() function. (file = 'project3_dataset1.txt')
- Then, run the last cell containing __main__() function.
- Output will contain the accuracy, precision, recall an F1-score of the dataset calculated based on the algorithm.



To run the Kaggle code, the datasets are placed in the Kaggle folder. Please navigate to the Kaggle folder and run the Kaggle
notebook by following the below instructions.

5. Kaggle Competition
- Open the folder 'Kaggle' and open the notebook kaggle.ipynb.
- In the third cell assign the file names to the variables train_features_file, train_label_file, test_features_file as below.
   train_features_file = "train_features.csv"
   train_label_file = "train_labels.csv"
   test_features_file = "test_features.csv"
- Run all the cells one by one and each cell containing classification algorithms defined in the comments.
  Knn, Decision Tree, Random Forest, Naive Bayes Bernoulli, Adaboost, Adaboost regressor, GridSearchCV, Bagging.
- Each classification algorithm will give the accuracy of training and validation set as the output.
- And the output '.csv' files will be generated and stored in the Kaggle folder.

References:
https://machinelearningmastery.com/train-test-split-for-evaluating-machine-learning-algorithms/
https://machinelearningmastery.com/implement-decision-tree-algorithm-scratch-python/
https://machinelearningmastery.com/implement-random-forest-scratch-python/
