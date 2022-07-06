# FCN and Hierarchical PGM for Remote Sensing Image Classification


This repository contains the code related to the papers 

## Content

### Context

Deep learning is currently the dominant approach to image classification and segmentation, but the performances of deep learning methods are remarkably influenced by the quantity and quality of the ground truth (GT) used for training. The main idea is to combine a specific type of deep convolutional neural networks (CNNs), namely, fully convolutional networks (FCNs), with probabilistic graphical models (PGMs). Our method takes advantage of the intrinsic multiscale behavior of FCNs to deal with multiscale data representations and to connect them to a hierarchical Markov model (e.g., making use of a quadtree). As a consequence, the spatial information present in the data is better exploited, allowing a reduced sensitivity to GT incompleteness to be obtained. The marginal posterior mode criterion is used for inference in the proposed framework. 

### Architecture



### Data

 





### How to run the code

Use the `FCN+MPM.ipynb` notebook using [Jupyter](https://jupyter.org/)!


## References



## License

## Acknowledgements

The ISPRS 2D Semantic Labeling Challenge Dataset were provided by the German Society for Photogrammetry, Remote Sensing and Geoinformation (DGPF).


