# Introduction and Definitions

## Definitions

- **Supervised Learning:** ML algorithms learn through direct supervision by a human. Speicifically the various features (x) are _labeled_ (to pre-determined output) by the human. <a href="https://github.com/stall84/ml-basics-exercises-notes/blob/main/notes/definitions.md#description">more here</a>
- **Unsupervised Learning:** ML algorithms learn through making sense of the features themselves, to determine relevant labels. No output is pre-determined or used in the training data.
- **Reinforcement Learning:** An ML algorithm that utilizes an _Agent_, to move through an _Environment_ (toward a goal) by utilizing _Rewards_. (more later)
- [**Tensor:**](https://www.tensorflow.org/guide/tensor) "A tensor is a generalization of vectors and matrices to potentially higher dimensions. Internally, [_TensorFlow_](https://www.tensorflow.org) represents as n-dimensional arrays of base datatypes."

### TensorFlow Basics

- Google maintained ML library.
- Based on a _Graph_ and _Session_ model which allows parts of the graph to be evaluated in a session instead of all evaluated at once.

#### Common Tensor Types (In TensorFlow)

- **Variable:** Of these 4, Variable is the only mutable type. We'd use Variable when we think the value of the tensor might need to change during runtime
- **Constant:**
- **Placeholder:**
- [**SparseTensor:**](https://www.tensorflow.org/guide/tensor#sparse_tensors): When your data might be sparse
