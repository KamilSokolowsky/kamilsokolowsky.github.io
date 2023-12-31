# Kompendium wiedzy - ScikitLearn

# Modules

## sklearn.cluster

### KMeans
This algorithm computes the centroids and iterates until it finds optimal centroid. It requires the number of clusters to be specified that’s why it assumes that they are already known. The main logic of this algorithm is to cluster the data separating samples in n number of groups of equal variances by minimizing the criteria known as the inertia. The number of clusters identified by algorithm is represented by ‘K.
#### from sklearn.cluster import KMeans
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- random_state - Determines random number generation for centroid initialization. Use an int to make the randomness deterministic.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

#### Code Example 
```py
  kmeans = KMeans (n_clusters = 10, random_state = 0) #building the model
  kmeans.fit(X_train) #fitting the model to the dataset
  ```

## sklearn.datasets

### * OpenML

#### from sklearn.datasets import fetch_openml
Fetch dataset from openml by name or dataset id

### * Classification datasets

#### from sklearn.datasets import load_wine
#### from sklearn.datasets import load_iris
#### from sklearn.datasets import load_brest_cancer

### * Regression datasets

#### from sklearn.datasets import load_diabetes
#### from sklearn.datasets import fetch_california_housing

<details>
  <summary>sklearn.dummy</summary>

### from sklear.cluster import KMeans
- X - The observation to cluster.
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

</details>
<details>
  <summary>sklearn.feature_selection</summary>

### from sklear.cluster import KMeans
- X - The observation to cluster.
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

</details>
<details>
  <summary>sklearn.linear_model</summary>

### from sklear.cluster import KMeans
- X - The observation to cluster.
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

</details>
<details>
  <summary>sklearn.metrics</summary>

### from sklear.cluster import KMeans
- X - The observation to cluster.
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

</details>
<details>
  <summary>sklearn.model_selection</summary>

### from sklear.cluster import KMeans
- X - The observation to cluster.
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

</details>
<details>
  <summary>sklearn.neighbors</summary>

### from sklear.cluster import KMeans
- X - The observation to cluster.
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

</details>
<details>
  <summary>sklearn.neural_network</summary>

### from sklear.cluster import KMeans
- X - The observation to cluster.
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

</details>
<details>
  <summary>sklearn.preprocessing</summary>

### from sklear.cluster import KMeans
- X - The observation to cluster.
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

</details>
<details>
  <summary>sklearn.tree</summary>

### from sklear.cluster import KMeans
- X - The observation to cluster.
- n_clusters - The number of clusters to form as well as the number of centroids to generate.
- init - Method for initialization (k-means++, random).
- n_init - Number of times the k-means algorithm is run with different centroid seeds.
- max_iter - Maximum number of iterations of the k-means algorithm for a single run.

</details>




