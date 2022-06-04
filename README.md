# Credit Card Fraud Detection

This notebook addresses one of the most relevant problems in the current years regarding e-commerce industry: Credit
Card Fraud. The approach to reach the solution of the problem will be pragmatic, covering from the data exploration
to the model evaluation and selection.

Several techniques are being considered to treat the imbalance of the dataset, such as Random Undersampling or SMOTE.
Regarding the models considered, we include Logistic Regression, tree-based models and state-of-the-art solutions, such
as XGBoost and Deep Learning.

## Installation of the environment

You can follow up this notebook in your machine by downloading Anaconda and then running the following command in the terminal:

```bash
conda env create --file fraud-detection.yml
```

This should have you prepared to run jupyter notebook in the terminal and then running the mentioned code using that familiar interface.

Please note that I've used a M1 Mac, so the installation might suffer from some problems if you are using a different CPU
architecture. In those cases do not hesitate to look up information on the official sources such as [Tensorflow](www.tensorflow.org)
or [PyPi](www.pypi.org) to solve your occasional errors during the installation.

## References

- [Reproducible Machine Learning for Credit Card Fraud detection - Practical handbook](https://fraud-detection-handbook.github.io/fraud-detection-handbook/Foreword.html)
- Deep Learning with Python - François Chollet
- Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems - Aurelien Geron
