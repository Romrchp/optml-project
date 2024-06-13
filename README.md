# CS-439: Image Denoising Using a Chambolle Scheme with Isotropic and Anisotropic Total Variations

The goal of this project is to use the Chambolle dual algorithm with an isotropic and anisotropic total variation regularization to perform denoising on sample images. The results are then be compared according to the choices of the hyperparameters via analysis of some image quality metrics.

This repository includes :

- [final_notebook.ipynb](final_notebook.ipynb) : Main Python notebook including the algorithm, the test and experiences and the result that have been obtained.
- [background_notebooks](background_notebooks) : Include several notebooks that have been used as inspiration for the project as well some additional experiences.
  - [ForwardDualBackward.ipynb](ForwardDualBackward.ipynb) : Original Chambolle dual algorithm with only isotropic total variation regularization.
  - [Discrete-d.ipynb](Discrete-d.ipynb) : Definition and présentation of the discrete gradient operator used in the algorithm.
  - [background-work.ipynb](background-work.ipynb) : Additionnal experiences that don't appear in the report.
