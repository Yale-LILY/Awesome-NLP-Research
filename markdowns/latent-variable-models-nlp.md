# Latent Variable Models for NLP

## Keywords 
Autoencoders, Neural Networks, Bayesian Inference

## Overview
### [Variational Inference: A Review for Statisticians (2018)](https://arxiv.org/pdf/1601.00670.pdf)
A go-to to get an intuition for variational inference, written by David Blei, the go-to researcher in variational inference for NLP.

## Previous Work
### [Latent Dirichlet Allocation (2003)](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)
A great example of early variational inference where we rely on a conjugate prior to make intractable evidence integrals computationally tractable.

### [Sequence to Sequence Learning with Neural Networks (2014)](https://arxiv.org/pdf/1409.3215.pdf)
First introduces using LSTMs to model sentences, a technique used by pretty much all of the papers that follow to do the initial encoding required to turn sentences into vectors.

## Current Papers
### [Auto-encoding Variational Bayes (2014)](https://arxiv.org/pdf/1312.6114.pdf)
The original paper that proposes neural variational inference via an autoencoder. It's quite dense and hard to understand, so I would start with a blog post for laymen before diving into this paper.

### [Neural Variational Inference for Text Processing (2016)](https://arxiv.org/pdf/1511.06038.pdf)
Use an autoencoder for variational inference in approximating the total posterior integral. The autoencoder serves to learn how to represent a latent variable, which is then used as the parameters of a diagonal Gaussian to represent a region of the posterior.

### [Discovering Discrete Latent Topics with Neural Variational Inference (2017)](https://arxiv.org/pdf/1706.00359.pdf)
Topic modeling but you don't have to pick the number of topics! Rather than using a Dirichlet prior, we teach a neural network to model the distribution of document vector distribution parameters. In addition, we can also use a recurrent neural network to dynamically adjust the number of topics in our corpus.

### [Generating Sentences from a Continuous Space (2016)](https://arxiv.org/pdf/1511.06349.pdf)
Main problem with RNNs: models sentences word by word rather than an overall sentence level view. It also doesn't
give interpretable representations of global features like topic or syntax. If you treat the entire sentence as an observed variable drawn from a latent space, then you can draw vectors from it that incorporate better kinds of features and preserve more structure, like style, topic and syntax.

### [Language as a Latent Variable: Discrete Generative Models for Sentence Compression (2016)](https://arxiv.org/pdf/1609.07317.pdf)
It's like an autoencoder for sentences, but instead of using a vector to represent the latent sentence, we use another sentence! This has the result of summarizing sentences.

### [Spherical Latent Spaces for Stable Variational Autoencoders (2018)](https://arxiv.org/pdf/1808.10805.pdf)
In a loss function like ELBO, KL often becomes overvalued. The model tries to compensate for the spike by ignoring how well the latent variable can encode information. Instead of using Gaussian priors for p(z) in the KL term of a likelihood function, we use von Mises-Fisher distributions, which prevent KL collapse, thereby ensuring the use of the latent variable.

Another good paper that looks at KL collapse is Bowman, 2016 (above).

## Blog Posts
### [Applications of Autoencoders in Natural Language Processing](https://www.doc.ic.ac.uk/~js4416/163/website/nlp/)
Some applications of autoencoders in various NLP tasks.

### [Blackbox and Approximate (Variational) Neural Inference](http://akashgit.github.io/Neural-Variational-Inference/)
Good primer on variational inference, but a little too heavy on the equations for laypeople.