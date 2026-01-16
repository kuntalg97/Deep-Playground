# Deep-Playground

This repository contains various neural network–based codes, ranging from graph neural networks (GNNs) for molecular property prediction to recurrent neural networks (RNNs). The examples and implementations are based on material I studied in the ML in Chemistry course at UChicago (Spring 2025), as well as from online tutorials and books by Raschka, Murphy, Goodfellow, and Bishop, along with Andrew White’s blog.

GNN_QM9 - Implementation of graph neural networks (GNNs) with invariance/equivariance for predicting molecular properties using the QM9 dataset.

NN for trig - Design and implementation of a very simple neural network for approximating an analytical trigonometric function.

Recurrent NN - Simple tutorial on how to design and implement recurrent neural networks (RNNs). RNNs are known for being able to process sequential data (and capture temporal dependencies). A small illustration with a toy model is also shown.

inverse_design - This implements a conditional variational autoencoder (cVAE) to learn from a given dataset (represented by SMILES) and train the cVAE conditioned on cohesive energies. The cVAE is then deployed to generate new structures corresponding to some values of the cohesive energy. In other words, this is a small illustration of inverse design of molecular structures.
