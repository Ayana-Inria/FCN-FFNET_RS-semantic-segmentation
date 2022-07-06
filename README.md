# FCN and Hierarchical PGM for Remote Sensing Image Classification


This repository contains the code related to the papers ADD IGARSS21 IGARSS22 TGRS22 EUSIPCO21  
Pytorch
## Content

### Context

Deep learning is currently the dominant approach to image classification and segmentation, but the performances of deep learning methods are remarkably influenced by the quantity and quality of the ground truth (GT) used for training. The main idea is to combine a specific type of deep convolutional neural networks (CNNs), namely, fully convolutional networks (FCNs), with probabilistic graphical models (PGMs). Our method takes advantage of the intrinsic multiscale behavior of FCNs to deal with multiscale data representations and to connect them to a hierarchical Markov model (e.g., making use of a quadtree). As a consequence, the spatial information present in the data is better exploited, allowing a reduced sensitivity to GT incompleteness to be obtained. The marginal posterior mode criterion is used for inference in the proposed framework. 

ADD IMG

### Architecture

ADD TEXT

### Data

Our example models are trained on the [ISPRS Vaihingen dataset](http://www2.isprs.org/commissions/comm3/wg4/2d-sem-label-vaihingen.html) and [ISPRS Potsdam dataset](http://www2.isprs.org/potsdam-2d-semantic-labeling.html). We use the IRRG tiles (8bit format)



### How to run the code

Use the `FCN+MPM.ipynb` notebook using [Jupyter](https://jupyter.org/)!


## References

When using this work, please cite our IEEE TGRS Journal paper:

M. Pastorino, G. Moser, S. B. Serpico and J. Zerubia, "Semantic Segmentation of Remote-Sensing Images Through Fully Convolutional Neural Networks and Hierarchical Probabilistic Graphical Models," in IEEE Transactions on Geoscience and Remote Sensing, vol. 60, pp. 1-16, 2022, Art no. 5407116, doi: [10.1109/TGRS.2022.3141996](https://ieeexplore.ieee.org/document/9676578). 

@ARTICLE{9676578,
  author={Pastorino, Martina and Moser, Gabriele and Serpico, Sebastiano B. and Zerubia, Josiane},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Semantic Segmentation of Remote-Sensing Images Through Fully Convolutional Neural Networks and Hierarchical Probabilistic Graphical Models}, 
  year={2022},
  volume={60},
  number={},
  pages={1-16},
  doi={10.1109/TGRS.2022.3141996}}


## License

Code (scripts and Jupyter notebooks) are released under the GPLv3 license. See `LICENSE.md` for more details.

## Acknowledgements

ADD TEXT

The ISPRS 2D Semantic Labeling Challenge Datasets were provided by the German Society for Photogrammetry, Remote Sensing and Geoinformation (DGPF).


