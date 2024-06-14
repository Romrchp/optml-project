# CS-439: Image Denoising Using a Chambolle Scheme with Isotropic and Anisotropic Total Variations

The goal of this project is to use the Chambolle dual algorithm with an isotropic and anisotropic total variation regularization to perform denoising on sample images. The results are then be compared according to the choices of the hyperparameters via analysis of some image quality metrics.

## Repository Structure

This repository includes :

- [final_notebook.ipynb](final_notebook.ipynb) : Main Python notebook including our new implementation, the tests and the different experiments conducted, as well as the results obtained in the report. Also contains additional important elements not kept in the report due to space management, that follow the flow of the report.


- [background_notebooks](background-notebooks) : This folder includes several notebooks, that have been used as inspiration for the project as well some additional experiences.
  - [ForwardDualBackward.ipynb](background-notebooks/ForwardDualBackward.ipynb) : Implements the Chambolle dual algorithm with only isotropic total variation regularization. The original notebook can be found at [https://github.com/gnthibault/Optimisation-Python/blob/master/ForwardBackwardDual.ipynb], please refer to the references section for full detail.

  - [Discrete-d.ipynb](background_notebooks/Discrete-d.ipynb) : This noteboo presents and details the discrete gradient operator used in the algorithm, introduced from `ForwardDualBackward.ipynb`.

  - [background-work.ipynb](background-notebooks/background-work.ipynb) : Additionnal experiences that do not appear in the report.

### Prerequisites :

In order to run the notebook included you must have the following python packages installed :

- some package

### Contributors :

- Christopher Cherfan
- Lenny Del Zio
- Romain Rochepeau
