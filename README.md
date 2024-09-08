# Improved and Interpretable Prediction of Cytochrome P450-Mediated Metabolism by Molecule-level Graph Modeling

## Data

The original data comes from Zaretzki's dataset and is stored in the merged.sdf file.

## Feature
The processing of atom-types, atom-based, and topol-based features is handled in the atom_topo_feature.py file.

## Models
Machine learning experiments ML were conducted on three datasets composed of features from different characteristics.
The trained model is saved in the model folder via train.ipynb.

## Interpretability
The explanatory files are located in the explain folder, including the interpretability analysis in explainer.py, rdkit_cluster.ipynb for clustering analysis of the original molecules, and rdkit_cluster1.ipynb for clustering analysis of subgraphs composed of important second-order neighbor nodes.

