Adaptive Neural Operator Control for a Transport PDE with Nonlinear Recirculation

The source code for the paper titled Adaptive Neural-Operator Backstepping Control of a Benchmark Hyperbolic PDE (TODO: Add link).

## Sysetm Requirements
All of the code is written in Python 3 and relies on standard packages such as numpy, Pytorch, Scipy, and the 
deep learning package [DeepXDE](https://github.com/lululxvi/deepxde). Additionally, all code
in this work is nicely formatted in a jupyter-notebook. A basic installation
will require the installation of Python, jupyter along with DeepXDE and PyTorch. Please see the 
import statements in the Jupyter-notebooks to make sure all files are included. Versions for each package is given at the first block of the jupyter-notebook and is included in the requirements.txt file. 

## Demos

### Dataset and Models
All precomputed datasets and models are available here [Google Drive](https://drive.google.com/drive/folders/16bztrIFXy700_37LBvdguyTOf8EP0MQy?usp=sharing)

### Adaptive Control Simulations
- Please see the jupyter-notebook `adaptiveControl.ipynb`. All the datasets are available in the drive, but if one ones to make their own data, the generation code is commented out in the notebook. Likewise to compute one's own models, please comment out the `load_dict` in the notebook.

## Cite this work
TODO

## Questions
Feel free to leave any questions in the issues of Github or email the author Luke at lbhan@ucsd.edu

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.


