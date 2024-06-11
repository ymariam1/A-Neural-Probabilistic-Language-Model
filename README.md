# A-Neural-Probabilistic-Language-Model
This code takes a textfile as input, where each line is assumed to be one training thing (names, words, etc) and generates more things like it. Under the hood, it is an autoregressive character-level language model, with a wide choice of models from MLP all the way to a Transformer (exactly as seen in GPT).
Implementations follow a few key papers: 
* MLP, following Bengio et al. 2003
