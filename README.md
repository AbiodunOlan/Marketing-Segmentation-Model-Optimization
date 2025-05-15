# Marketing-Segmentation-Model-Optimization

Machine Learning Optimization Assignment: Otomoto Marketing Campaigns
Project Overview
This project aims to optimize an existing Artificial Neural Network (ANN) model for Otomoto’s marketing segmentation. Various optimization algorithms, including SGD, Adam, RMSprop, and Optuna, were evaluated to improve model performance and marketing campaign effectiveness.


#### Project Structure

/Otomoto-Marketing-ANN
│

├── data/                 # Dataset files (preprocessed)

├── models/               # Model definitions and saved models

├── notebooks/            # Jupyter notebooks for EDA, training, optimization

├── results/              # Evaluation metrics, graphs, and reports

├── optimization/         # Optuna optimization scripts

├── README.md             # Project overview and instructions

└── requirements.txt      # Python package dependencies


#### Optimization Algorithms Used

SGD (Stochastic Gradient Descent): Baseline optimizer.

Adam (Adaptive Moment Estimation): Popular adaptive optimizer (Kingma and Ba, 2015).

RMSprop: Optimizer suitable for recurrent data and noisy gradients (Tieleman and Hinton, 2012).

Optuna: Bayesian hyperparameter optimization framework (Akiba et al., 2019).


Recommendations

SGD slightly outperforms other optimizers in terms of accuracy and macro F1-Score.

Consider applying class imbalance mitigation techniques like SMOTE (Chawla et al., 2002) or class weighting for future improvements.

Further hyperparameter tuning beyond optimizer selection is recommended.

Future Work

Experiment with advanced techniques like Focal Loss for imbalance handling.

Evaluate ensemble methods combining ANN with decision trees.

Deploy model for real-time campaign segmentation on Otomoto’s platform.

- References
- 
Kingma, D.P. and Ba, J.L., 2015. Adam: A method for stochastic optimization. ICLR. Available at: https://arxiv.org/abs/1412.6980

Tieleman, T. and Hinton, G., 2012. RMSProp. COURSERA. Available at: https://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf

Akiba, T. et al., 2019. Optuna: A next-generation hyperparameter optimization framework. KDD '19. Available at: https://doi.org/10.1145/3292500.3330701

Chawla, N.V. et al., 2002. SMOTE: Synthetic Minority Over-sampling Technique. JAIR, 16, pp.321-357.

Goodfellow, I., Bengio, Y. and Courville, A., 2016. Deep Learning. Cambridge: MIT Press.
