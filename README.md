 Building a Recurrent Neural network implementing LSTM cells in order to generate new Simpsons TV script. The Simpsons dataset of scripts from 27 seasons was used. The Neural Network generates a new TV script for a scene at Moe's Tavern. The RNN was trained on GPU using FloydHub.

In order to run it, setup Conda, then activate an environment:
```
$ conda env create -f environment.yaml
```
Setup floyd hub and launch it in GPU mode:
```
$ floyd login
$ floyd init
$ floyd run --mode jupyter --gpu
```

### Take a look
You can open the jupyter notebook directly in github 
 [TV script generation with RNN](https://github.com/sbatururimi/tv-script-generation/blob/master/dlnd_tv_script_generation.ipynb)

 ## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/sbatururimi/tv-script-generation/blob/master/LICENSE)