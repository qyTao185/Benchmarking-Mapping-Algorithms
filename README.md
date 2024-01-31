# Benchmarking-Mapping-Algorithms
The code for passage "Benchmarking Mapping Algorithms for Cell Type Annotating in Mouse Brain by Integrating Single-Nucleus RNA-seq and Stereo-seq Data"
![image](https://github.com/qyTao185/Benchmarking-Mapping-Algorithms/blob/main/workflow.png)
## Overview
Here, we benchmarked 7 mapping algorithms using 8 ST datasets from four mouse brain regions in two different resolutions and 24 pseudo-ST datasets from snRNA-seq. Both actual ST data and pseudo-ST data were mapped using snRNA-seq datasets from the corresponding brain regions as reference data. After comparing the performance across different areas and resolutions of the mouse brain, we have reached the conclusion that both RCTD and SpatialDWLS demonstrated superior robustness and accuracy in cell type annotation. Testing with publicly available snRNA-seq data from another sequencing platform in the cortex region further validated our conclusions. Altogether, we developed a workflow for assessing suitability of mapping algorithm that fits for ST datasets, which can improve the efficiency and accuracy of spatial data annotation.
## Datasets
· The 10X snRNA-seq data of the mouse cortex used in this study can be obtained here: https://drive.google.com/file/d/1kIoXlOwJk7IPljNZ-MzWRvvcOfEHDiFd/view?usp=sharing

· The raw data for the spatial transcriptome can be obtained here: https://doi.org/10.12412/BSDC.1699433096.20001
