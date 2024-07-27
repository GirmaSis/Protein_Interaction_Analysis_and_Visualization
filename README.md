# Protein interaction analysis and visualization

This repository provides a set of Python scripts for analyzing and visualizing protein-protein interactions using data from the STRING database API. The scripts offer customizable workflows for researchers to explore protein interactions and perform enrichment analysis.

**Note**
You can download and visualize `network.html` file to view the interactive network using a browser.

## Main functionalities:

### 1. Network Analysis and Visualization

- Fetch interaction data from the STRING database.
- Visualize the interaction network using `networkx` and `matplotlib`.
- Create interactive network visualizations with `pyvis`.

### 2. Functional Enrichment Analysis

- Perform enrichment analysis on the interacting proteins using `g:Profiler`.
- Save and display enrichment analysis results.

## How to Run

   ```bash
   git clone https://github.com/GirmaSis/Protein_Interaction_Analysis_and_Visualization.git
   cd Protein_Interaction_Analysis_and_Visualization
   pip install requests pandas networkx matplotlib pyvis gprofiler-official
   ```
