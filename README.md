# Benchmarking-Mapping-Algorithms
The code for passage "Benchmarking Mapping Algorithms for Cell Type Annotating in Mouse Brain by Integrating Single-Nucleus RNA-seq and Stereo-seq Data"
![image](https://github.com/qyTao185/Benchmarking-Mapping-Algorithms/blob/main/workflow.png)
## Abstract
Limited gene capture efficiency and spot size of spatial transcriptome (ST) data pose significant challenges in cell type characterization. The heterogeneity and complexity of cell composition in the mammalian brain make it more challenging to accurately annotate ST data from brain. Many algorithms attempt to characterize subtypes of neuron by integrating ST data with single-nucleus RNA sequencing (snRNA-seq) or single-cell RNA sequencing (scRNA-seq). However, assessing the accuracy of these algorithms on Stereo-seq ST data remains unresolved. Here, we benchmarked 7 mapping algorithms using 8 ST datasets from four mouse brain regions in two different resolutions and 24 pseudo-ST datasets from snRNA-seq. Both actual ST data and pseudo-ST data were mapped using snRNA-seq datasets from the corresponding brain regions as reference data. After comparing the performance across different areas and resolutions of the mouse brain, we have reached the conclusion that both RCTD and SpatialDWLS demonstrated superior robustness and accuracy in cell type annotation. Testing with publicly available snRNA-seq data from another sequencing platform in the cortex region further validated our conclusions. Altogether, we developed a workflow for assessing suitability of mapping algorithm that fits for ST datasets, which can improve the efficiency and accuracy of spatial data annotation.
## Datasets

