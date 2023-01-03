# unsupervised-machine-learning-challenge

### Part 1: Prepare the Data

1. Read myopia.csv into a pandas DataFrame
1. Remove the "MYOPIC" column from the dataset
1. Standardise the dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values

### Part 2: Apply Dimensionality Reduction

1. Perform dimensionality reduction with PCA
1. Further reduce the dataset dimensions with t-SNE
1. From the scatter plot created, it appeared to be 7 clusters

### Part 3: Perform a Cluster Analysis with K-means

1. Use a for loop to determine the inertia for each k between 1 through 10.

1. From the elbow point of the plot, it seemed that the best k value was 5.

### Part 4 : Recommendation

Based on my findings, it appeared that the patients can be clustered into 5 groups.
