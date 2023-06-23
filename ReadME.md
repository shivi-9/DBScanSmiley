# DBScan Smiley
This project implements the DBSCAN (Density-Based Spatial Clustering of Applications with Noise) algorithm to cluster a dataset representing smiley face points. It aims to identify the eyes and mouth regions within the dataset and assign cluster labels accordingly.

## Problem Statement
The goal of this project is to demonstrate the use of the DBSCAN algorithm for clustering smiley face points and visualize the clustering results.

## Dependencies
* numpy
* PIL (Python Imaging Library)
* matplotlib
* scikit-learn

## Requirements
To run this project, you need to have Python 3.x installed on your system. Install the required dependencies using the following command:
```
pip install numpy pillow matplotlib scikit-learn
```

## Installation Instructions/Usage
1. Clone or download the project repository.
2. Navigate to the project directory.
3. Make sure you have installed the required dependencies as mentioned above.
4. Run the IPython Notebook or execute the Python script to see the clustering results and visualize the smiley face clusters.
```
python dbscan_smiley.py
```
6. The program will display a scatter plot showing the clustering results of the smiley face points.
7. Additionally, an animated GIF (dbscan.gif) will be generated, showing the snapshots of the clustering process.