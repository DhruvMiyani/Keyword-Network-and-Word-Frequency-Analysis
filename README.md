# Keyword-Network-and-Word-Frequency-Analysis
IE 6400 Project 

This File provides an overview of Project 3, which aims to perform keyword network analysis and word frequency analysis. The project involves several tasks to extract, process, and analyze data from a given dataset. The primary tasks include creating a weighted adjacency matrix from keyword data, generating a weighted network, computing node degree and strength, identifying top nodes based on degree and strength, finding the top node pairs by weight, and plotting average strength against node degree.

##Task Overview
Task 1: Data Extraction and Network Creation
Dataset Download: Obtain the dataset for the project from the provided link:
Project 3 Dataset.

![image](https://github.com/DhruvMiyani/Keyword-Network-and-Word-Frequency-Analysis/assets/54111873/dca7440b-0d49-4729-9238-1c26b6aaa169)


Python Code for Data Extraction: Write a Python script to extract keyword data from the downloaded spreadsheet. Convert this data into a weighted adjacency matrix based on the relationships between keywords.

Weighted Network Creation: Use the adjacency matrix to construct a weighted network, where nodes represent keywords and edges represent the relationships between them.

Task 2: Analysis and Visualization
Node Degree and Strength Calculation: Compute the degree and strength of each node in the weighted network.

Top Nodes by Degree and Strength: Identify the top 10 nodes based on their degree and strength within the network.

Top Node Pairs by Weight: Determine the top 10 pairs of nodes with the highest edge weights in the network.

Average Strength vs. Degree Plot: Create a plot where the y-axis represents the average strength of nodes, and the x-axis represents the degree of nodes. This will help visualize the relationship between node degree and strength.

Getting Started
To get started with the project, follow these steps:

Dataset Download: Download the dataset from the provided link.

Data Processing: Implement the Python code to extract keyword data from the spreadsheet and convert it into a weighted adjacency matrix.

Network Analysis: Use the adjacency matrix to create a weighted network, calculate node degree and strength, and identify top nodes and node pairs.

Visualization: Generate the plot for average strength against node degree.

Dependencies
Make sure you have the following dependencies installed:

Python (3.x recommended)
Libraries: numpy, pandas, networkx, matplotlib
Install the required libraries using the following command:

bash
Copy code
pip install numpy pandas networkx matplotlib
Usage
Run the Python script to perform data extraction, network creation, analysis, and visualization.

The script will generate outputs and plots related to node degree, strength, top nodes, and the average strength vs. degree plot.

Conclusion
Project 3 involves the extraction and analysis of keyword data to create a weighted network. By calculating node degree, strength, and identifying top nodes and node pairs, valuable insights can be gained from the data. The average strength vs. degree plot provides a graphical representation of the network's characteristics.

For detailed implementation and code, refer to the project files and the provided Python script.

