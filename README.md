### The task
predicting a random sine wave from just 10 (x,y) pairs

### What is Reptile algorithm
Reptile is a simple meta-learning(learning how to learn) optimization algorithm similar to the amazing [MAML](https://arxiv.org/abs/1703.03400) algorithm which i recommend to read the [MAML](https://arxiv.org/abs/1703.03400) paper.
Both of MAML and Reptile are **model-agnostic** so they work with any model that learns through gradient descent.
Reptile is more simple and comutational efficient than MAML algorithm.

How does it works ?

![Alt text](images/algorithm.png?raw=true "Title")

### The Reptile works by repeatedly:
1) sampling a task,
2) training on it by multiple gradient descent steps,
3) and then moving the model weights towards the new parameters.

### Intuitively, 
![Alt text](images/figure.png?raw=true "Title")

The Reptile algorithm find a parameter **theta** that is close to all the optimal manifolds of all tasks

### Dependencies
This code requires the following:

- Python 3.5.2+
- TensorFlow 2.0.0-beta0
- Numpy
- Matplotlib

### References
- [Reptile Paper:](https://arxiv.org/abs/1803.02999) Alex Nichol, Joshua Achiam, John Schulman. "On First-Order Meta-Learning Algorithms".
- [OpenAI blog post:](https://blog.openai.com/reptile) Check it out, they have an online demo running entirely in Javascript!
- [MAML Paper:](https://arxiv.org/abs/1703.03400) Chelsea Finn, Pieter Abbeel, Sergey Levine. "Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks".

### Contact
To ask questions or report issues, please open an issue on the [issues tracker](https://github.com/eng-amrahmed/reptile-tf2/issues)
