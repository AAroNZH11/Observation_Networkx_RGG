# Graph Generation Time Analysis with Networkx

This repository contains an analysis of the execution time required for generating graphs using various models in the [Networkx](https://networkx.org/) Python package. The models evaluated include:

1. Erdős-Rényi (ER)
2. Watts-Strogatz (WS)
3. Barabási-Albert (BA)
4. Random Geometric Graph (RGG)

## Methodology

The execution time for generating graphs is measured for different numbers of nodes (ranging from 1000 to 8000) and various parameters specific to each model. Each configuration is run multiple times to get a reliable estimate of the execution time.

## Key Findings

It is observed that the time taken to generate a graph using the Random Geometric Graph model can be abnormally long under certain conditions. Specifically, when the number of nodes is large (up to 8000 nodes) and the radius is relatively high (0.8), the execution time is more than five times the estimated time.

## Data and Visualizations

The data for this analysis is included in the repository in CSV format. Additionally, for each graph generation model, execution time plots with various parameters have been created and included in this repository.

## Environment

The analysis was performed on a MacBook Air M1 2021 using Python and the Networkx package.

## Sharing

This finding is shared with the community in the hope of enhancing our understanding of the performance characteristics of the Networkx package. Contributions, insights or suggestions are welcomed. Please feel free to create an issue or a pull request.