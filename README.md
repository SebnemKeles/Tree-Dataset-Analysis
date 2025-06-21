# Tree-Dataset-Analysis
This project contains the analysis of a tree dataset collected on the University of Lincoln's Riseholme campus. The primary focus is to evaluate whether the Diameter at Breast Height (DBH) of a tree is influenced by the DBH of its nearest neighbouring tree within a 5-meter radius across four distinct woodland areas.


#🌳 Tree Neighbourhood Influence on DBH


##📌 Project Overview

Research Question:
Does the DBH of a tree show a statistically significant relationship with the DBH of its nearest neighbouring tree?

Hypothesis:
Null (H₀): There is no statistically significant relationship between a tree’s DBH and its neighbour’s maximum DBH.
Alternative (H₁): There is a statistically significant relationship between a tree’s DBH and its neighbour’s maximum DBH.

Key Finding:
The analysis found no statistically significant relationship between a tree's DBH and its neighbouring tree’s DBH in any of the four forest sites, with p-value = 0.8936, confirming the null hypothesis.


##📊 Methods Summary

Study Sites:
Young Wood
Ancient Wood
Old Wood B
Mid Wood

Sample Size:
54 trees randomly selected

Data Collected:
DBH of each target tree
Maximum DBH of any neighbouring tree within 5 meters

Analytical Method:
Simple Linear Regression
Site-wise and aggregate scatterplot visualization
Analysis of slopes, R² values, and outliers

Tool and Package Used:
R Studio
ggplot2


##📈 Results Overview

Regression Output Summary:
Coefficient: 0.01462
Standard Error: 0.10878
p-value: 0.8936 → Not statistically significant

Visual Observations:
Weak correlations across all sites: R² = 5% to 47%
Most scatterplots were non-linear

