# Protein Interaction Analysis and Visualization

This repository provides a set of Python scripts for analyzing and visualizing protein-protein interactions using data from the STRING database API. 
The scripts offer customizable and automated workflows for researchers to explore protein interactions and perform enrichment analysis.

## Main functionalities

### 1. Network Analysis and Visualization

- Fetch interaction data from the STRING database.
- Visualize the interaction network using `networkx` and `matplotlib`.
- Create interactive network visualizations with `pyvis`.

### 2. Functional Enrichment Analysis

- Perform enrichment analysis on the interacting proteins using `g:Profiler`.
- Save and display enrichment analysis results.

## How to Run

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   pip install requests pandas networkx matplotlib pyvis gprofiler-official
