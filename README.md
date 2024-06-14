# CS-439: Image Denoising Using a Chambolle Scheme with Isotropic and Anisotropic Total Variations

The goal of this project is to use the Chambolle dual algorithm with an isotropic and anisotropic total variation regularization to perform denoising on sample images. The results are then be compared according to the choices of the hyperparameters via analysis of some image quality metrics.

## Repository Structure

This repository includes :

- [final_notebook.ipynb](final_notebook.ipynb) : Main Python notebook including our new implementation, the tests and the different experiments conducted, as well as the results obtained in the report. Also contains additional important elements not kept in the report due to space management, that follow the flow of the report.


- [background_notebooks](background-notebooks) : This folder includes several notebooks, that have been used as inspiration for the project as well some additional experiences.
  - [ForwardDualBackward.ipynb](background-notebooks/ForwardDualBackward.ipynb) : Implements the Chambolle dual algorithm with only isotropic total variation regularization. The original notebook can be found at [https://github.com/gnthibault/Optimisation-Python/blob/master/ForwardBackwardDual.ipynb], please refer to the references section for full detail.

  - [Discrete-d.ipynb](background_notebooks/Discrete-d.ipynb) : This noteboo presents and details the discrete gradient operator used in the algorithm, introduced from `ForwardDualBackward.ipynb`.

  - [background-work.ipynb](background-notebooks/background-work.ipynb) : Additionnal experiences that do not appear in the report.

## Prerequisites :

The project was coded and ran under the 3.10.8 version, but should run properly on other versions as well.

**The main packages to install for this project are** :
- **pyproximal** : This Python library provides all the needed building blocks for solving non-smooth convex optimization problems using the so-called proximal algorithms.

- **pooch** : Pooch is a Python library that can manage data by downloading files from a server (only when needed) and storing them locally in a data cache (a folder on your computer). It is needed in our project to load the 'Ascent' image.

In order to correctly install the latter and the rest of the more 'basic' dependencies, please refer to the `requirements.txt` file in the root folder of the repository. It contains the necessary dependencies to run our `final_notebook.ipynb`. 


## Run instructions

To run `final_notebook.ipynb`, clone the repository or download the file and run it from your prefered method. This repository does not contain any external `.py` or `ipynb` files needed for this notebook to run.


## Main references and inspiration for the project :


- A. Chambolle and T. Pock, “A first-order primal-dual algorithm for convex problems with applications to imaging,” Journal of Mathematical Imaging and Vision, vol. 40, pp. 120–145, 2011. [https://api.semanticscholar.org/CorpusID:261281173]

- A Weighted Difference of Anisotropic and Isotropic Total Variation Model for Image Processing Yifei Lou, Tieyong Zeng, Stanley Osher, and Jack Xin SIAM Journal on Imaging Sciences 2015 8:3, 1798-1823 [https://epubs.siam.org/doi/10.1137/14098435X]

- K. Bui, Y. Lou, F. Park, and J. Xin, “Difference of anisotropic and
isotropic tv for segmentation under blur and poisson noise,” 2023. [https://www.frontiersin.org/articles/10.3389/fcomp.2023.1131317/full]

### Code reference :

- `ForwardBackwardDual.ipynb`, found and obtainable at [https://github.com/gnthibault/Optimisation-Python]. This public repository contains several basic optimisation algorithms, ranging from Support Vector Machines to Image denoising. The notebooks it contains were made and modified by :
  -  Gabriel Peyré, CNRS, DMA, Ecole Normale Supérieure [https://scholar.google.fr/citations?user=KqA1dYcAAAAJ&hl=en]
  - Laurent Condat, Senior Research Scientist, King Abdullah University of Science and Technology (KAUST), Saudi Arabia. [https://scholar.google.com/citations?user=mfBA5f8AAAAJ&hl=fr]



## Contributors :

- Christopher Cherfan, Quantum Science and Engineering Section,
- Lenny Del Zio, Quantum Science and Engineering Section,
- Romain Rochepeau, Section of Life Sciences Engineering.
