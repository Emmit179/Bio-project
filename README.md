# Balancing Gene Homogeneity and Spatial Proximity in Spatial Transcriptomics Data With a Multi- Objective Evolutionary Clustering Approach

This code outlines basic clustering of spatial transcriptomics data first using k-means, then using a novel multi-objective approach with NSGA-II.

## Installation

Run ```pip install pymoo numpy matplotlib sklearn scipy ```

## Data

```DLPFC_spot_expression.npy```: Data containing the first 50 principal components of the gene expressions.

```DLPFC_spot_location.npy```: Data containing the physical location of the spots.

## Usage

Run the notebook ```project.ipynb``` and it will generate the plots.
