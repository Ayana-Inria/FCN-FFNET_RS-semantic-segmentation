# FCN and Hierarchical PGM for Remote Sensing Image Classification


This repository contains the code related to the papers:  

M. Pastorino, G. Moser, S. B. Serpico and J. Zerubia, "Semantic Segmentation of Remote-Sensing Images Through Fully Convolutional Neural Networks and Hierarchical Probabilistic Graphical Models," in IEEE Transactions on Geoscience and Remote Sensing, vol. 60, pp. 1-16, 2022, Art no. 5407116, doi: [10.1109/TGRS.2022.3141996](https://ieeexplore.ieee.org/document/9676578).

M. Pastorino, G. Moser, S. B. Serpico and J. Zerubia, "Semantic Segmentation of Remote Sensing Images Combining Hierarchical Probabilistic Graphical Models and Deep Convolutional Neural Networks," 2021 IEEE International Geoscience and Remote Sensing Symposium IGARSS, 2021, pp. 8672-8675, doi: [10.1109/IGARSS47720.2021.9553253](https://ieeexplore.ieee.org/document/9553253).

M. Pastorino, G. Moser, S. B. Serpico and J. Zerubia, "Hierarchical Probabilistic Graphical Models and Deep Convolutional Neural Networks for Remote Sensing Image Classification," 2021 29th European Signal Processing Conference (EUSIPCO), 2021, pp. 1740-1744, doi: [10.23919/EUSIPCO54536.2021.9616179](https://ieeexplore.ieee.org/document/9616179).

MORE DETAILS ON THE LIB

## Content

### Context

Deep learning is currently the dominant approach to image classification and segmentation, but the performances of deep learning methods are remarkably influenced by the quantity and quality of the ground truth (GT) used for training. The main idea is to combine a specific type of deep convolutional neural networks (CNNs), namely, fully convolutional networks (FCNs), with probabilistic graphical models (PGMs). Our method takes advantage of the intrinsic multiscale behavior of FCNs to deal with multiscale data representations and to connect them to a hierarchical Markov model (e.g., making use of a quadtree). As a consequence, the spatial information present in the data is better exploited, allowing a reduced sensitivity to GT incompleteness to be obtained. The marginal posterior mode (MPM) criterion is used for inference in the proposed framework.

ADD IMG

### Architecture

ADD TEXT

### Data

The model is trained on the [ISPRS Vaihingen dataset](http://www2.isprs.org/commissions/comm3/wg4/2d-sem-label-vaihingen.html) and [ISPRS Potsdam dataset](http://www2.isprs.org/potsdam-2d-semantic-labeling.html). The two datasets consist of VHR optical images (spatial resolutions of 9 and 5cm, respectively), we used the IRRG channels. They can be downloaded on [Kaggle](https://www.kaggle.com/datasets/bkfateam/potsdamvaihingen) and should be inserted in the folder `/input`.


### How to run the code

Use the `FCN+MPM.ipynb` notebook using [Jupyter](https://jupyter.org/)!


## References

When using this work, please cite our IEEE TGRS Journal paper:

M. Pastorino, G. Moser, S. B. Serpico and J. Zerubia, "Semantic Segmentation of Remote-Sensing Images Through Fully Convolutional Neural Networks and Hierarchical Probabilistic Graphical Models," in IEEE Transactions on Geoscience and Remote Sensing, vol. 60, pp. 1-16, 2022, Art no. 5407116, doi: [10.1109/TGRS.2022.3141996](https://ieeexplore.ieee.org/document/9676578). 

```
@ARTICLE{pastorino_tgrs22,
  author={Pastorino, Martina and Moser, Gabriele and Serpico, Sebastiano B. and Zerubia, Josiane},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Semantic Segmentation of Remote-Sensing Images Through Fully Convolutional Neural Networks and Hierarchical Probabilistic Graphical Models}, 
  year={2022},
  volume={60},
  number={},
  pages={1-16},
  doi={10.1109/TGRS.2022.3141996}}
```

## License

The code is released under the GPLv3 license. See `LICENSE.md` for more details.

## Acknowledgements

ADD TEXT

The ISPRS 2D Semantic Labeling Challenge Datasets were provided by the German Society for Photogrammetry, Remote Sensing and Geoinformation (DGPF).


