# PytorchGeometricTutorial

Course completion. Don't fork this!

- [Youtube](https://www.youtube.com/user/94longa2112/featured)
- [site](https://antoniolonga.github.io/Pytorch_geometric_tutorials/index.html)
- [PyG tutorial](https://antoniolonga.github.io/Pytorch_geometric_tutorials/index.html)

## Tutorials

- Tutorial1: [What is Geometric Deep Learning?](https://youtu.be/JtDgmmQ60x8) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial1/Tutorial1.ipynb)
- Tutorial2: [PyTorch basics.](https://youtu.be/UHrhp2l_knU) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial2/Tutorial2.ipynb)
- Tutorial3: [Graph Attention Network GAT.](https://youtu.be/CwsPoa7z2c8) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial3/Tutorial3.ipynb)
- Tutorial4: [Convolutional Layers - Spectral methods.](https://youtu.be/Ghw-fp_2HFM) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial4/Tutorial4.ipynb)
- Tutorial5: [Aggregation Functions in GNNs.](https://youtu.be/tGXovxQ7hKU) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial5/Aggregation%20Tutorial.ipynb)
- Tutorial6: [Graph Autoencoders and Variational Graph Autoencoders.](https://youtu.be/qA6U4nIK62E) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial6/Tutorial6.ipynb)
- Tutorial7: [Adversarially regularized GAE and VGAE.](https://youtu.be/hZkLu2OaHD0) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial7/Tutorial7.ipynb)
- Tutorial8: [Graph Generation.](https://youtu.be/embpBq1gHAE)
- Tutorial9: [Recurrent Graph Neural Networks.](https://youtu.be/v7TQ2DUoaBY) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial9/Tutorial9.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial9/RecGNN_tutorial.ipynb)
- Tutorial10: [DeepWalk and Node2Vec (Theory).](https://youtu.be/QZQBnl1QbCQ)
- Tutorial11: [DeepWalk and Node2Vec (Practice).](https://youtu.be/5YOcpI3dB7I) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial11/Tutorial11.ipynb)
- Tutorial12: [Edge analysis.](https://youtu.be/m1G7oS9hmwE) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial12/Tutorial12%20GAE%20for%20link%20prediction.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial12/Tutorial12%20Node2Vec%20for%20label%20prediction.ipynb)
- Tutorial13: [Metapath2vec.](https://youtu.be/GtPoGehuKYY) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial13/Tutorial13.ipynb)
- Tutorial14: [Data handling in Pyg (part 1)](https://youtu.be/Vz5bT8Xw6Dc) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial14/Tutorial14.ipynb)
- Tutorial15: [Data handling in Pyg (part 2)](https://youtu.be/Q5T-JdyVCfs) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial15/Tutorial15.ipynb)
- Tutorial16: [Special guest talk - Matthias Fey](https://youtu.be/MA6VH7Vwtb4)
- Tutorial17: [Special guest talk - Sergei Ivanov](https://youtu.be/hX297pr1RHE)
- Tutorial18: [Graph pooling: DIFFPOOL.](https://youtu.be/Uqc3O3-oXxM) - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntonioLonga/PytorchGeometricTutorial/blob/main/Tutorial16/Tutorial16.ipynb)

## Dependencies

- poetry
- pyenv

1. Create VSCode project with `code .`
2. Install poery dependencies and add environment for python linting. Use `poetry config virtualenvs.in-project true` for creation env folder inside project. Then `poetry install --with dev --no-root`.

Or use pyenv to create env inside project and `poetry install --with dev --no-root`

```txt
# .python-version

3.12.5
```

```toml
# poetry.toml

virtualenvs.create = true
virtualenvs.prefer-active-python = true
# ... some other variables
```
