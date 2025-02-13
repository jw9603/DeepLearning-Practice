# Deep Learning Basic

This repository focuses on Deep Learning basic. It can be applied to everything from the basic MNIST dataset to custom datasets.

I developed this in a practical, deployable form, rather than simply in a Jupyter Notebook.

## Usage
### 0. Dependencies

```
pip install matplotlib
pip install numpy
pip install torch
pip install pytorch-ignite
```

### 1. Directory

```plain

├── README.md
├── mnist_classification/
    ├── resut_model/                 (model_file)
    ├── model.py/
    ├── trainer.py/
    ├── train.py/
    ├── utils.py/
    └── run.sh/
├── autoencoder/
    ├── autoencoder.ipynb/                 
    ├── model.py/
    ├── trainer.py/
    ├── utils.py/
├── manifold/
    ├── manifold.ipynb/                 
    ├── model.py/
    ├── trainer.py/
    ├── utils.py/
├── pytorch_dataset/
    ├── custom_dataset.ipynb/
├── pytorch_ignite/
    ├── data/
    ├── result_model/                
    ├── data_loader.py/
    ├── model/
        ├── cnn_model.py/
        ├── fc_model.py/
        ├── rnn_model.py/
    ├── run_train.sh/
    ├── test.py/
    ├── train.py/
    ├── trainer.py/
├── 딥러닝 왕기초
    ├── 2-1.ipynb/
    ├── 2-2.ipynb/ 
├── ... (I plan to upload it later.)
```

