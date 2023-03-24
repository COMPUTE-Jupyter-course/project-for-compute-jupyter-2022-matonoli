[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/COMPUTE-Jupyter-course/project-for-compute-jupyter-2022-matonoli/main?labpath=matonoha.ipynb)

# Looking at particles detected at ALICE with Jupyter Notebooks

_© 2023, Oliver M_

_This project was created as a final project submission in the course Reproducible and Interactive Data Science taught at Lund University._

## Abstract:

The aim of this Jupyter Notebook is to introduce high-school level students to particle physics data and their analysis. We illustrate basic concepts of High Energy Physics (HEP) and Machine Learning (ML). Specifically, an Artificial Neural Network (ANN) is built and trained. ANNs, computational models inspired by human brains, have been receiving enormous attention in the last years. Along with their popular usage in e.g. image recognition or text prediction, they are also used extensively in physics analyses. In this work, we demonstrate a very simple example of an ANN usage to solve a basic classification problem -- identifying the pion and kaon particles. We utilise Python toolkits Pandas, NumPy, and Seaborn, which greatly facilitate presenting data and its analysis in a transparent and reproducible way. Open dataset from collisions of protons detected with the ALICE experiment at the Large Hadron Collider (LHC) in CERN is used.

## How to use:

In order to run the the notebook, `jupyter` as well as the other required libraries specified in environment.yml need to be installed. It can be ran online using mybinder.org (or just press the **"launch binder"** button at the beginning of this text). The initial build might take a couple of minutes, since we're using `tensorflow` as well.

Once in the Notebook, you can run the selected cells either by pressing **"Run > Run all cells"** or selecting the cells one by one and pressing Shift+Enter. The interactive widgets are used, which means that some content will not be displayed until you first run the cells.
