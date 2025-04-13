# Kaggle Competition: GANs - I’m Something of a Painter Myself

This project is for the Kaggle competition:

<https://www.kaggle.com/competitions/gan-getting-started/overview>

The goal is to generate Monet style images from real photos.

To download data:

```
kaggle competitions download -c gan-getting-started
```

## Environment setup:

(This is the environment I personally use for the training, you can use other similar local setup or use the Kaggle online notebook)

- OS: Windows 11
- GPU: NVIDIA GeForce RTX 3060 Laptop GPU
- CUDA 11.2.2
- cuDNN 8.1.1

## Python related:

```
choco install pyenv-win
pyenv install 3.10.5

pyenv rehash
pyenv global 3.10.5

python -m venv tf
.\tf\Scripts\activate


pip install -r requirements.txt

# Or install the packages manually, and add any packages missing:
pip install "numpy<2"
pip install tensorflow==2.10.0
pip install matplotlib
# and more..
```


