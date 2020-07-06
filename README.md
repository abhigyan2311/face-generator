# Face Generator
> Generative Adversarial Networks(GANs)

This project aims at successfully generating human faces using Generative Adversarial Networks(GANs)

## Installing / Getting started

A quick introduction of the minimal setup you need to get the classifier up &
running.

```shell
git clone https://github.com/abhigyan2311/face-generator.git
cd face-generator
conda env create -f environment.yml
conda activate deeplearning
jupyter notebook dlnd_face_generation.ipynb
```

## Features

The classifier notebook implements the following methods:
* Successfully generates faces based on the following celebrity dataset: [Celeb-DS](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip)

## Hyperparameters

* Batch Size - 128
* Number of epochs - 30
* Learning Rate - 0.0002
* Beta 1 - 0.5
* Beta 2 - 0.999
* Discriminator convolution dimension - 64
* Generator convolution dimension - 64
* Latent vector size(Z) = 100

## Contributing

"If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome."


## Licensing

"The code in this project is licensed under Apache 2.0 license."
