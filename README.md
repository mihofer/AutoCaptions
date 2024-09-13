# A little test repo for automatic videocaptioning

Playing around with automatic image captioning using a CNN-RNN model and the Microsoft COCO dataset.
Taken from <https://github.com/Garima13a/Automatic-Image-Captioning>

## Setup

Tested with Python 3.11

1. Install packages with `pip install -r requirements.txt`
2. Get the COCO 2014 dataset from <https://cocodataset.org/#home> and store in a `data` folder (folder is defined at the top of the notebooks as `datapath`)
3. Then run in following order 
   1. `check_coco.ipynb` [![GoogleColab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mihofer/AutoCaptions/blob/master/check_coco.ipynb)
   2. `preliminaries.ipynb` [![GoogleColab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mihofer/AutoCaptions/blob/master/preliminaries.ipynb)
   3. `training.ipynb` [![GoogleColab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mihofer/AutoCaptions/blob/master/training.ipynb)
   4. `inference.ipynb` [![GoogleColab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mihofer/AutoCaptions/blob/master/inference.ipynb)
