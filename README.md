# CS-439: Image Denoising Using a Chambolle Scheme with Isotropic and Anisotropic Total Variations

The goal of this project is to use the Chambolle dual algorithm with an isotropic and anisotropic total variation regularization to perform denoising on sample images. The results are then be compared according to the choices of the hyperparameters via analysis of some image quality metrics.

This repository includes :

- [final_notebook.ipynb](final_notebook.ipynb) : Main Python notebook including the algorithm, the test and experiences and the result that have been obtained.
- [background_notebooks](background-notebooks) : Include several notebooks that have been used as inspiration for the project as well some additional experiences.
  - [ForwardDualBackward.ipynb](background-notebooks/ForwardDualBackward.ipynb) : Original Chambolle dual algorithm with only isotropic total variation regularization.
  - [Discrete-d.ipynb](background_notebooks/Discrete-d.ipynb) : Define and present the discrete gradient operator used in the algorithm.
  - [background-work.ipynb](background-notebooks/background-work.ipynb) : Additionnal experiences that don't appear in the report.

### Prerequisites :

In order to run the notebook included you must have the following python packages installed :

- some package

### Contributors :

- Christopher Cherfan
- Lenny Del Zio
- Romain Rochepeau
