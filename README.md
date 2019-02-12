# AwesomeNER

## Introduction

The repository contains bidirectional LSTM-CRF for Named Entity Relationship on custom corpus using custom word embeddings using Tensorflow. It also contains an implementation of a state of the art Bi-directional LSTM-CNN-CRF architecture (Published at ACL'16. [Link To Paper](http://www.aclweb.org/anthology/P16-1101)) for Named Entity Recognition using Pytorch.

## Motivation

Even though the project as such focuses on implementing a Bidirecitonal Long Short Term Memory - Conditional Random Field model to help us label sentences. This notebook mostly focuses on exploring a new methodology inspired from the paper. The contrasting difference between a BiLSTM-CNN-CRF and our project is that it also makes use of a CNN layer which helps us generate character embeddings on our corpus versus using just the word embeddings in our other implementation. Upon satisfactory results, the implementation would be updates as a pip library available to be used for future purposes.

## Author

[Tarun Sudhams](https://github.com/sudhamstarun)
