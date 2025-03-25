# Keras-hyperparameter-tunning

Hyperparameter tuning is the process of finding the optimal set of parameters for a neural network to maximize performance. Keras provides built-in support for hyperparameter tuning via Keras Tuner, a library that automates the search for the best hyperparameters.

What is Hyperparameter Tuning?
Hyperparameters are settings that control the training process of a neural network, such as:

Learning rate (how fast the model learns)

Number of layers & neurons (architecture)

Batch size (how many samples per gradient update)

Activation functions (ReLU, sigmoid, etc.)

Dropout rate (to prevent overfitting)

Optimizers (Adam, SGD, RMSprop)

Unlike model weights (learned during training), hyperparameters must be set before training and significantly impact performance.

Keras Tuner: Key Features
Keras Tuner automates hyperparameter search with different strategies:

Random Search (Randomly samples hyperparameters)

Hyperband (Speeds up search via early stopping)

Bayesian Optimization (Uses probability to find optimal params)

Grid Search (Brute-force checks all combinations, rarely used)
