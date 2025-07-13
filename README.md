# K-Means and Fuzzy C-Means Clustering from Scratch

## This repository contains the full implementation of K-Means and Fuzzy C-Means clustering algorithms, built from scratch using Python, without any machine learning libraries (no scikit-learn, tensorflow, etc.).

The goal of the assignment was to analyze flu-related knowledge among high school students using unsupervised clustering techniques. The dataset used is Flu.csv.

Features Implemented

✅ K-Means Clustering
	•	Works for any number of clusters (k)
	•	Uses Euclidean distance
	•	Visualized in 3D for selected features
	•	Dunn Index implemented for cluster validity

✅ Fuzzy C-Means Clustering
	•	Soft clustering with membership scores
	•	Supports hardening for comparison with K-Means
	•	Uses centroid values and Dunn Index for evaluation

✅ Analysis Workflow
	•	Cluster evaluation for different values of k (2 to 10)
	•	Comparison of cluster quality using Dunn Index
	•	Experiments with adding features like KnowlTrans, HndWshQual
	•	Feature impact analysis on cluster separation
	•	Comparison between K-Means and Fuzzy C-Means results


Dataset Used
	•	Flu.csv
A dataset representing students’ behavior and awareness regarding flu and flu prevention (e.g., handwashing, risk, knowledge, sick status).

How to Run
	1.	Requirements:
	•	Python 3.8+
	•	numpy, matplotlib, pandas (only for basic data I/O and plotting)
	2.	Steps:
         git clone https://github.com/yourusername/flu-clustering-assignment.git
        cd flu-clustering-assignment
        python kmeans.py         # or run via Jupyter Notebook
        python fuzzy_cmeans.py   # for FCM part

Outputs:
	•	3D plots of clusters
	•	Dunn Index values per experiment
	•	Print statements for cluster comparison
 
Notes
	•	All clustering logic is implemented from scratch, including centroid updates and membership calculations.
	•	No use of machine learning toolboxes was allowed as per assignment requirements.
	•	Relative paths are used to load the dataset (Flu.csv), ensuring portability.
