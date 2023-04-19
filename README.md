## Machine Translation from Portuguese to English using Transformer Network
This project is an implementation of machine translation from Portuguese to English using a Transformer network. The Transformer network is a neural network architecture that was introduced in the paper "Attention Is All You Need" by Vaswani et al. It uses self-attention mechanisms to model the dependencies between different parts of the input sequence and has been shown to achieve state-of-the-art results on several natural language processing tasks, including machine translation.

## Dataset
The dataset used in this project is the ted_hrlr_translate/pt_to_en dataset, which contains over 600,000 sentence pairs of Portuguese and English translations. We split the dataset into 80% for training and 20% for validation.

##Requirements
Python 3.6 or later
PyTorch 1.8.0 or later
TorchText 0.9.0 or later
NumPy
Matplotlib

## Results
After training the Transformer network on the Portuguese-to-English translation task, we obtain a model that is able to accurately translate Portuguese sentences to English. Here are some example translations:

Portuguese sentence				         English translation

Eu gosto de comer pizza.			    I like to eat pizza.

O meu gato é preto e branco.			My cat is black and white.

Ele mora em São Paulo.				    He lives in São Paulo.

## Credits
This implementation of the Transformer network is based on the original paper by Vaswani et al., "Attention Is All You Need" (https://arxiv.org/abs/1706.03762). 
The ted_hrlr_translate/pt_to_en dataset was created by the TED organization and can be downloaded from https://www.tensorflow.org/datasets/catalog/ted_hrlr_translate.
