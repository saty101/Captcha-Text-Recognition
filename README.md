# Captcha-Text-Recognition

### Dependances

numpy
pytorch 1.6

### Running

git clone https://github.com/saty101/Captcha-Text-Recognition
cd src
Download the dataset in this directory

### Train

python train.py
This will run 200 epochs, usually 96% accuracy is reached at 40 epochs.
The whole training process is written [here](https://github.com/saty101/Captcha-Text-Recognition/blob/main/notebooks/captcha.ipynb) which can be trained on Google Colab.

### Perform Recogition

python recognize.py  0.png
Refer [this notebook](https://github.com/saty101/Captcha-Text-Recognition/blob/main/notebooks/test.ipynb) for recognizing Captcha images.

### Dataset

Data taken from [link](https://www.kaggle.com/fournierp/captcha-version-2-images)

