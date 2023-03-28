# Implementing hierarchical clustering and dendrograms from scratch in python
This repository contains code for a problem related to implementing and investigating the hierarchical clustering algorithm in pattern recognition. The problem involves clustering based on genes.

## Course Information
This problem is related to a *Statistical Pattern Recognition* course taught by Professor Mohammad Rahmati (<rahmati@aut.ac.ir>) in the Computer Engineering department at Amirkabir University of Technology (AUT) in Tehran, Iran. The course was offered in the Fall of 2021.

## Problem Description
The problem at hand was to have hierarchical clustering performed on a dataset containing 40 tissue samples with measurements on 1000 genes. The first 20 samples were from healthy patients, while the second 20 were from diseased patients. To solve the problem, a hierarchical clustering algorithm was implemented from scratch in Python.

Firstly, the data was loaded, and a matrix of pairwise distances between the samples was created using Euclidean distance. Then, this distance matrix was used to perform agglomerative hierarchical clustering with single/complete linkage (implemented from scratch to obtain dendrograms).

After clustering was completed, dendrograms were created to visualize the results. The dendrograms were plotted using scipy's dendrogram function, which showed the hierarchical relationship between the samples.


![Output](/output.png)


## Repository Contents

The repository contains Python code for the problem described above, as well as a Jupyter notebook that explains the problem and provides a step-by-step cells for running the code.

## Feedback

If you have any feedback or suggestions for improving this code, please feel free to open an issue in the repository as well as send an email to Mohsen Ebadpour (<m.ebadpour@aut.ac.ir> , <mohsenebadpour@outlook.com>).





