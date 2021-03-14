
How to run each algorithm, please follow the steps of each algorithm heading below to run them
All the required datasets are in the code folder

K-Means Execution
- Open the python notebook with name 'K-means.ipynb'
- In the first cell, give the file as the required dataset path you want to run the algorithm (ex : file = 'new_dataset_1.txt')
- Next, Run the first cell
- Similarly run all the cells except the last cell that contains '__main__()', this is the starting point of the execution of algorithm
- Once you run all except Main function, Finally run the last cell '__main__()'
- You will prompted to enter the number of clusters, give the int value and type enter.
  ex:  Enter the number of clusters
        3
- Next, you will be prompted to enter the number of iterations, give the int value and type enter.
  ex: Enter the number of iterations
        10
- Last, you will prompted to enter the initial centroid indices, give each value and type enter
  ex: Enter centroid gene data indices: 3
      Enter centroid gene data indices: 5
      Enter centroid gene data indices: 9
- Finally, the output will be generated and it contains a plot and values of both rand index and jaccard coefficient

Hierarchical Clustering Execution
- Open the python notebook with name 'Hierarchial clustering.ipynb'
- In the first cell, give the file as the required dataset path you want to run the algorithm (ex : file = 'new_dataset_2.txt')
- Next, Run the first cell
- Similarly run all the cells except the last cell that contains '__main__()', this is the starting point of the execution of algorithm
- Once you run all except Main function, Finally run the last cell '__main__()'
- You will prompted to enter the number of clusters, give the int value and type enter.
  ex:  Enter the number of clusters
        3
- The output of the cell will be a plot and a dendogram of how it forming a single large clusters and values of both rand index and jaccard Coefficient

Density based Execution
- Open the python notebook with name 'dbscan.ipynb'
- In the first cell, give the file as the required dataset path you want to run the algorithm (ex : file = 'dbscan.txt')
- Next, Run the first cell
- Similarly run all the cells except the last cell that contains '__main__()', this is the starting point of the execution of algorithm
- Once you run all except Main function, Finally run the last cell '__main__()'
- You will prompted to enter the epsilon value of clusters, give the float/int value and type enter.
  ex: Enter the epsilon value
      0.2
- Next, you will be prompted to enter the minimum number of points, give the int value and type enter.
  ex: Enter the minimum number of points
      3
- Final, output will display a plot and values of the rand index and jaccard coefficient.

GMM clustering Execution
- Open the python notebook with name 'GMM.ipynb'
- In the first cell, give the file as the required dataset path you want to run the algorithm (ex : file = 'GMM.txt')
- Next, Run the first cell
- Similarly run all the cells except the last cell that contains '__main__()', this is the starting point of the execution of algorithm
- Once you run all except Main function, Finally run the last cell '__main__()'
- You will prompted to enter the number of clusters, give the int value and type enter.
  ex:  Enter the number of clusters
        2
- Next, you will be prompted to enter the number of iterations, give the int value and type enter.
  ex: Enter the maximum number of iterations
        10
- Similarly in next two steps, you will be prompted to enter the smoothing_value and convergence thershold, give the float values for each and type Enter.
  ex: Enter the smooth_value
      1e-9
  ex: Enter the Convergence thershold
      1e-9
- At last, you will prompted to enter mu, sigma and pi list values, give each value and type Enter
- Final output will contain the plot, values of rand index and jaccard coefficient and after the iteration values of mu, sigma and pi.

Spectral Clustering execution
- Open the python notebook with name 'GMM.ipynb'
- In the first cell, give the file as the required dataset path you want to run the algorithm (ex : file = 'GMM.txt')
- Next, Run the first cell
- Similarly run all the cells except the last cell that contains '__main__()', this is the starting point of the execution of algorithm
- Once you run all except Main function, Finally run the last cell '__main__()'
- You will prompted to enter the number of clusters, give the int value and type enter.
  ex:  Enter the number of clusters
        2
- Next, you will prompted to enter the sigma value, give a float/int value and type Enter.
  ex: Enter the sigma value:
        2
- Later, you will have the choice to a. enter the initial choice centroids, b. randomly chose indices or c. use the eigen gap values
- if you type a and enter. you will be asked to enter both initial ids same as the number of clusters you have given above. B will directly prompt the
  output and c will also directly prompt the output but used eigen number as the number of clusters.
- Type a and Enter. You will prompted to enter both point indices.
    ex: Enter the point :1
      2
    ex: Enter the point :2
      3
- The output will contain the plot, Lapalcaian matrix and values of both rand index and jaccard coefficient. 
