# ML journey

Notebooks I wrote while going through Andrew Ng's Machine Learning and Deep Learning courses. Built mostly while first learning ML/Deep Learning — this repo is a recent reorganization of that older work, uploaded here so it's all in one place.

These aren't polished tutorials. They're implementations I worked through to actually understand the math — gradient descent from scratch, backprop by hand, that kind of thing.

---

## What's here

### Regression
| Notebook | What it covers |
|---|---|
| `linear_regression.ipynb` | Gradient descent + Normal Equation |
| `locally_weighted_regression.ipynb` | Non-parametric regression with kernel weighting |

### Classification & Unsupervised
| Notebook | What it covers |
|---|---|
| `logistic_regression.ipynb` | Binary classification, sigmoid, cross-entropy — optimized with Newton's method |
| `SVM.ipynb` | Support vectors, margin maximization, kernels |
| `K-means&EM.ipynb` | K-means clustering + Expectation-Maximization |

### Neural Networks
| Notebook | What it covers |
|---|---|
| `NN.ipynb` | Feedforward network, backpropagation from scratch |

### Reinforcement Learning
| Notebook | What it covers |
|---|---|
| `discreteRL.ipynb` | Tabular Q-learning, Bellman equations |

---

## Notes

Most of the math is implemented with NumPy rather than high-level libraries — the goal was understanding, not production code. Some notebooks use sklearn or similar for comparison/validation.

---

## Related

If you want to see where this RL stuff led: **[snake-RL](https://github.com/ZiadMohamedElsayed/snake-RL)** — a Snake game agent trained with Deep Q-Learning (PyTorch).