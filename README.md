The purpose of this repository is to provide didactic examples of numerical solutions of a Gray-Scott reaction-diffusion system and Belousov-Zhabotinsky Simulation. The codes included here were implemented in Python available on "gray_scott_simulation.py" and "belousov-zhabotinsky_simulation.py".

# Gray-Scott Reaction

Simulation colab link: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ABenatti/Gray-Scott-Simulation/blob/master/Gray_Scott_simulation.ipynb)

The ray-Scott reaction-diffusion system can be mathematically expressed by following differential equation:


![](https://latex.codecogs.com/gif.latex?\frac{\partial&space;u}{\partial&space;t}&space;=&space;D_u&space;\nabla^2&space;u&space;-&space;uv^2&space;&plus;&space;F(1-u))


![](https://latex.codecogs.com/gif.latex?\frac{\partial&space;v}{\partial&space;t}&space;=&space;D_v&space;\nabla^2&space;v&space;&plus;&space;uv^2&space;-&space;(F&plus;k)v)

![](./images/GE.png)

# Belousov-Zhabotinsky Simulation

Simulation colab link: [![Open In Colab](link????)

A comun simplification of Belousov-Zhabotinsky reaction is expressed by following differential equation:

![](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Cpartial%20X%7D%7B%5Cpartial%20t%7D%20%3D%20D_X%20%5Cnabla%5E2%20X%20&plus;%20X%28k_1Y%20-%20k_3Z%29%2C)

![](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Cpartial%20Y%7D%7B%5Cpartial%20t%7D%20%3D%20D_Y%20%5Cnabla%5E2%20Y%20&plus;%20Y%28k_2Z%20-%20k_1X%29)

![](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Cpartial%20Z%7D%7B%5Cpartial%20t%7D%20%3D%20D_Z%20%5Cnabla%5E2%20Z%20&plus;%20Z%28k_3X%20-%20k_2Y%29)

![](./images/BZ.png)

## License

This Deep Learning Tutorial is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 (CC BY-NC-ND 4.0) International License.

## Acknowledgments
Alexandre Benatti thanks Coordenação de Aperfeiçoamento de Pessoal de Nível Superior - Brasil (CAPES) - Finance Code 001. Luciano da F. Costa thanks CNPq (grant no. 307085/2018-0) and NAP-PRP-USP for sponsorship. This work has been supported also by FAPESP grants 11/50761-2 and 2015/22308-2.
