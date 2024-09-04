# AI5-Customer_Segmentation
## K-Means Clustering of Customer Data

This project demonstrates the use of K-Means clustering to segment customers based on their annual income and spending score. The dataset used is `Avm_Customers.csv`, which contains information about customers' annual income and their spending score.

## Project Overview

1. **Data Exploration**: 
   - Load the dataset and preview the data.
   - Visualize the distribution of customers based on annual income and spending score.

2. **Data Preprocessing**:
   - Rename columns for simplicity.
   - Normalize the data using `MinMaxScaler`.

3. **Clustering**:
   - Determine the optimal number of clusters using the Elbow Method.
   - Apply K-Means clustering with the optimal number of clusters.
   - Analyze and visualize the clustering results.

4. **Visualization**:
   - Plot the clustered data points and cluster centroids.

## Files

- `Avm_Customers.csv`: The dataset used for clustering.
- `K-MeansClustering-Customer_Segmentation.ipynb`: The Python script implementing the K-Means clustering algorithm and visualizations.

## Installation

To run this project, you will need Python and the following libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`

You can install the required libraries using pip:


pip install numpy pandas scikit-learn matplotlib

## Usage

1. **Clone this repository:**

    ```bash
    git clone https://github.com/Semssolak/repository.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd repository
    ```

3. **Run the Python script:**

    ```bash
    python K-MeansClustering-Customer_Segmentation.ipynb
    ```

## Results

- **Elbow Method Plot**: This plot shows the distortion value (inertia) for different numbers of clusters, helping to determine the optimal number of clusters.
- **Clustered Data Plot**: A scatter plot visualizing the clusters, with different colors representing different clusters. The centroids of the clusters are marked with blue 'X' markers.
