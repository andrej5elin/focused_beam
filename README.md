# Focused beam

[![Build and Deploy](https://github.com/andrej5elin/focused_beam/actions/workflows/deploy.yml/badge.svg)](https://github.com/andrej5elin/focused_beam/actions/workflows/deploy.yml)
[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://andrej5elin.github.io/focused_beam/lab/?path=focused_scalar_beam.ipynb)
[![DOI](https://zenodo.org/badge/1045530499.svg)](https://doi.org/10.5281/zenodo.17292340)


A discrete FFT-based technique to compute electromagnetic field in the vicinity of the focal plane of a high NA objective lens. The technique is explained in [[1]](https://doi.org/10.1364/OE.565420). The technique is a discrete numerical implementation of the Debye-Wolf integral [2], combined with a numerical field propagator based on modal decomposition, which allows one to compute the field within a small distance from the focal plane, in the near field. 

## Usage notes

Implementation is done in python for the jupyter lab IDE. The notebooks are located in the *content* folder. You can download them and use [jupyter lab](https://jupyter.org/install) to run them. The notebook was used to create plots in [3]. 

You can also use the browser-based [jupyter lite](https://jupyterlite.readthedocs.io/) by clicking **try lite now** badge above or use the [following link](https://andrej5elin.github.io/focused_beam/lab/) and open the notebook.

Note that because of memory restrictions when running the code in a cloud, the above online tools are meant for testing and solving small problems. If you want to solve larger problems, please install jupyter lab as explained below:

## Installation 

I recommend using anaconda to build [jupyter lab](https://jupyter.org/install).

```console
$ conda create --name beam
$ conda activate beam
$ conda install numpy scipy matplotlib
$ conda install jupyter
$ jupyter lab
```

Download the notebooks and open in jupyter lab.

## References

[[1]](https://doi.org/10.1364/OE.565420) Petelin, A. & Muševič, I. , Focused beam propagation in cholesteric
liquid crystals. *Opt. Express* **33**, 32955–32975.

[2] Richards, B. & Wolf, E. Electromagnetic diffraction in optical systems, II. Structure of the image field in an aplanatic system. *Proceedings of the Royal Society of London. Series A. Mathematical and Physical Sciences* **253**, 358–37.

[3] Petelin, A., Fokusiran Gaussov snop, *Obzornik za matematiko in fiziko*. 
