# FCN and Fully Connected NN for Remote Sensing Image Classification


This repository contains the code related to the papers:  

M. Pastorino, G. Moser, S. B. Serpico, and J. Zerubia, "Fully convolutional and feedforward networks for the semantic segmentation of remotely sensed images," 2022 IEEE International Conference on Image Processing, 2022, [https://hal.inria.fr/hal-03720693](https://hal.inria.fr/hal-03720693).

MORE DETAILS ON THE LIB

## Content

### Context

ADD FEW LINES

ADD IMG

### Architecture

ADD INFO
  
### Data

The model is trained on the [ISPRS Vaihingen dataset](http://www2.isprs.org/commissions/comm3/wg4/2d-sem-label-vaihingen.html) and [ISPRS Potsdam dataset](http://www2.isprs.org/potsdam-2d-semantic-labeling.html). The two datasets consist of VHR optical images (spatial resolutions of 9 and 5cm, respectively), we used the IRRG channels. They can be downloaded on [Kaggle](https://www.kaggle.com/datasets/bkfateam/potsdamvaihingen) and should be inserted in the folder `/input`.


### How to run the code

Use the `notebook.ipynb` notebook using [Jupyter](https://jupyter.org/) and refer to the file `requirements.txt`.

ADD REQUIREMENTS

## References

When using this work, please cite our IEEE TGRS Journal paper:

M. Pastorino, G. Moser, S. B. Serpico, and J. Zerubia, "Fully convolutional and feedforward networks for the semantic segmentation of remotely sensed images," in IEEE International Conference on Image Processing, Bordeaux, France, 2022. 

```
@ARTICLE{pastorino_icip22,
  author={Pastorino, Martina and Moser, Gabriele and Serpico, Sebastiano B. and Zerubia, Josiane},
  journal={IEEE International Conference on Image Processing}, 
  title={Fully convolutional and feedforward networks for the semantic segmentation of remotely sensed images}, 
  year={2022},
  volume={},
  number={},
  pages={},
  doi={}}
```

## License

The code is released under the GPLv3 license. See `LICENSE.md` for more details.

## Acknowledgements

This work was conducted during my joint PhD at [INRIA](https://team.inria.fr/ayana/team-members/), d'Université Côte d'Azur and at the [University of Genoa](http://phd-stiet.diten.unige.it/). 
The ISPRS 2D Semantic Labeling Challenge Datasets were provided by the German Society for Photogrammetry, Remote Sensing and Geoinformation (DGPF).
The code to deal with the ISPRS dataset derives from the GitHub repository [Deep learning for Earth Observation](https://github.com/nshaud/DeepNetsForEO).

