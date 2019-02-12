# AwesomeNER

## Introduction

The repository contains bidirectional LSTM-CRF for Named Entity Relationship on custom corpus using custom word embeddings using Tensorflow. It also contains an implementation of a state of the art Bi-directional LSTM-CNN-CRF architecture (Published at ACL'16. [Link To Paper](http://www.aclweb.org/anthology/P16-1101)) for Named Entity Recognition using Pytorch.

## Motivation

Even though the project as such focuses on implementing a Bidirecitonal Long Short Term Memory - Conditional Random Field model to help us label sentences. This notebook mostly focuses on exploring a new methodology inspired from the paper. The contrasting difference between a BiLSTM-CNN-CRF and our project is that it also makes use of a CNN layer which helps us generate character embeddings on our corpus versus using just the word embeddings in our other implementation. Upon satisfactory results, the implementation would be updates as a pip library available to be used for future purposes.

## References

1. Sequence Tagging with Tensorflow using bi-LSTM + CRF with character embeddings for NER and POS by Guillaume Genthial [Link](https://guillaumegenthial.github.io/sequence-tagging-with-tensorflow.html)
2. End-to-end Sequence Labeling via Bi-directional LSTM-CNNs-CRF . In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 1: LongPapers). Association for Computational Linguistics, Berlin, Germany [Link](https://arxiv.org/pdf/1603.01354.pdf)
3. Bidirectional LSTM-CRF and ELMo for Named-Entity Recognition, Part-of-Speech Tagging and so on. An implementation by Hironsan Nakayama [Link](https://github.com/Hironsan/anago)

## Author

[Tarun Sudhams](https://github.com/sudhamstarun)
