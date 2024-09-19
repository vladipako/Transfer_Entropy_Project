# Transfer Entropy Project

This work pursues the goal of creating an open-source implementation of transfer entropy methodology based on Shannon entropy concept. Rényi entropy might potentially be added later. 

A Python based implementation of the Transfer Entropy method. 

Includes or shall include:

1. A standard cumulative TE implementation, similar to RTransferEntropy by Dr. Dimpfl.
2. A PCF-like individual lag TE implementation for each lag in any direction of dependence.
3. Shuffle based p-value test, incorporating parallelisation to the extent allowed by hardware.
4. Calibration and comparisons to CopulaEntropy python package and RTransferEntropy R package.
5. Calibration against MINE package based on the Datasaurus package.  
6. A multi-dimensional processor for an input dataframe.
7. Directional graph model visualisation based on specific inputs.
8. ?.. 
