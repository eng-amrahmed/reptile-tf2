### Reptile
Reptile is a simple meta-learning(learning how to learn) optimization algorithm similar to the amazing [MAML](https://arxiv.org/abs/1703.03400) algorithm which i recommend to read it.
Both of MAML and Reptile are **model-agnostic** so they work with any model that learns through gradient descent
Reptile is more comutational efficient than MAML algorithm that require to calculate the second derivative

How does it works ?

![Algorithm](https://github.com/eng-amrahmed/reptile-tf2/tree/master/images/algorithm.jpg)


### Dependencies
This code requires the following:

- Python 3.5.2+
- TensorFlow 2.0.0-beta0

### References
- [Original Paper:](https://arxiv.org/abs/1803.02999) Alex Nichol, Joshua Achiam, John Schulman. "On First-Order Meta-Learning Algorithms".
- [OpenAI blog post:](https://blog.openai.com/reptile) Check it out, they have an online demo running entirely in Javascript!

### Contact
To ask questions or report issues, please open an issue on the [issues tracker](https://github.com/eng-amrahmed/reptile-tf2/issues)
