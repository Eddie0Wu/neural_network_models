# Neural networks models and applications in imaging and natural language processing

This repository contains supervised and unsupervised deep learning models coded in Pytorch: feed forward neural network (FFNN), convolutional neural network (CNN), recurrent neural network (RNN) and its variations, generative models including variational autoencoder (VAE) and generative adversarial network (GAN). The codes can be readily adapted for various applications in many fields. The model structure and complexity can also be conveniently modified to cater to specific tasks. More details of each model can be find inside the notebooks, as well as how to run them.


## File structure

[`CNN_3D_medical_imaging.ipynb`](CNN_3D_medical_imaging.ipynb): this notebook contains the codes for predicting patient's age with brain MRI scan in two approaches. The first approach has two stages: neural network segmentation for feature calculation + regression. The second approach combines convolutional neural network and regression in a single pipeline.

[`CNN_structure.ipynb`](CNN_structure.ipynb): this notebook contains the codes for convolutional neural network layers written from scratch. It shows how each type of layer works under the hood. The self-written layers are compatible with the Pytorch framework.

[`generative_adversarial_network.ipynb`](generative_adversarial_network.ipynb): this notebook contains the codes for implementing a generative adversarial network in Pytorch. It also contains some visualisation and experimentations.

[`ResNet-18.ipynb`](ResNet-18.ipynb): this notebook implements ResNet-18 in Pytorch. It is trained on CIFAR10.

[`RNN_LSTM_GRU_structure.ipynb`](RNN_LSTM_GRU_structure.ipynb): this notebook contains the codes for writing RNN, LSTM and GRU from scratch. It demonstrates how these recurrent neural network structures work under the hood.

[`sentiment_analysis_BERT.ipynb`](sentiment_analysis_BERT.ipynb): this notebook implements BERT for sentiment analysis. It also compares BERT's performance to methods that do not use pre-trained representations. 

[`variational_autoencoder.ipynb`](variational_autoencoder.ipynb): this notebook contains the codes for implementing variational autoencoder in Pytorch. it also does numerous analysis on the latent space representation, as well as t-SNE visualisation.




