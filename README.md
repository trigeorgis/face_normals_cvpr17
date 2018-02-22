# Face Normals `in-the-wild' using Fully Convolutional Networks"


If you use this codebase in your experiments please cite:

> [Face Normals “in-the-wild” using Fully Convolutional Networks
G. Trigeorgis, P. Snape, I. Kokkinos, S. Zafeiriou. IEEE Conference on Computer Vision and Pattern Recognition (CVPR). July 2017.
]

## 1. Installation
We highly recommended to use [conda](http://conda.pydata.org/miniconda.html) as your Python distribution.
Once downloading and installing [conda](http://conda.pydata.org/miniconda.html), this project can be installed by:

**Step 1:** Create a new conda environment and activate it:
```console
$ conda create -n normals python=3.5
$ source activate normals
```

**Step 1:** Install [TensorFlow v1](https://www.tensorflow.org/install/) following the 
official installation instructions. For example for the gpu enabled version of TensorFlow 
```console
(normals)$ pip install --upgrade tensorflow-gpu
```


**Step 2:** Install [Menpo](https://menpo.org) following the 
official installation instructions. This is not mandatory, but makes importing and
visualisation of images a breeze.
```console
(normals)$ conda install -c menpo menpo
```

Disclaimer:
The pretrained models can only be used for non-commercial academic purposes.
