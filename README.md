# Focused beam

[![Build and Deploy](https://github.com/andrej5elin/focused_beam/actions/workflows/deploy.yml/badge.svg)](https://github.com/andrej5elin/focused_beam/actions/workflows/deploy.yml)
[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://andrej5elin.github.io/focused_beam/lab/?path=focused_scalar_beam.ipynb)

A discrete FFT-based technique to compute electromagnetic field in the vicinity of the focal plane of a high NA objective lens. Technique is explained in [[1]](https://doi.org/10.1364/OE.565420). The technique is a discrete numerical implementation of the Debye-Wolf integral [2], combined with a numerical field propagator based on modal decomposition, which allows one to compute the field within a small distance from the focal plane, in the near field. Implementation is done in python for the jupyter lab IDE. The notebook was used to create plots in [3]. 

## Usage notes

The notebooks are located in the *content* folder. You can download them an install ad use [jupyter lab](https://jupyter.org/install) to run them.

You can also use the browser-based [jupyter lite](https://jupyterlite.readthedocs.io/) by clicking **try lite now** badge above or use the [following link](https://doi.org/10.1364/OE.565420]https://andrej5elin.github.io/focused_beam/lab/) and open the notebook.

## References

[[1]](https://doi.org/10.1364/OE.565420) Petelin, A. & Muševič, I. , Focused beam propagation in cholesteric
liquid crystals. *Opt. Express* **33**, 32955–32975.

[2] Richards, B. & Wolf, E. Electromagnetic diffraction in optical systems, II. Structure of the image field in an aplanatic system. *Proceedings of the Royal Society of London. Series A. Mathematical and Physical Sciences* **253**, 358–37.

[3] Petelin, A., Fokusirani snopi svetlobe, *Obzornik za matematiko in fiziko*. 
