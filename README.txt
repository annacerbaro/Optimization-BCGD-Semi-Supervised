This project consists in the implementation of different gradient descent methods in semi-supervised learning for binary classification.
We randomly generated 3000 data points, labeling only 0.1% of them. The aim of the model is to exploit both labeled and unlabeled examples to achieve a good performance. 
We used different versions of gradient descent algorithms:
- Standard gradient descent:
  - with fixed learning rate
  - with Armijo rule
  - with exact line search
- Block Coordinate Gradient Descent (BCGD) with Randomized Rule:
  - with uniform sampling
  - with non uniform sampling
- Block Coordinate Gradient Descent with Gauss-Southwell rule:
  - with different fixed learning rates


Cerbaro  Anna	2087619
d'Addario 	Alessia	2086506
Papadopulos	Eleni	2079423
Ronzoni		Alice	2076675

File explaination:
Cerbaro_dAddario_Papadopulos_Ronzoni.ipynb              => contains the main code
Cerbaro_dAddario_Papadopulos_Ronzoni_Real_Dataset.ipynb => contains the problem applied on a real dataset
data_banknote_authentication.txt                        => contains the real dataset
Cerbaro_dAddario_Papadopulos_Ronzoni.pdf                => contains the report
