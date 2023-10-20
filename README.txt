This project consists in the implementation of different gradient descent methods variants in semi-supervised learning for binary classification. This offers the opportunity to make a comparison among different optimization algorithms used for the minimization of the defined loss function.
We randomly generated 3000 data points, labeling only 0.1% of them. Being an instance of semi-supervised learning, the aim of the model is to exploit both labeled and unlabeled examples to achieve a good performance. 
We used the following gradient descent alternatives:
- Standard gradient descent:
  - with fixed learning rate
  - with Armijo rule
  - with exact line search
- Block Coordinate Gradient Descent (BCGD) with Randomized Rule:
  - with uniform sampling
  - with non uniform sampling
- Block Coordinate Gradient Descent with Gauss-Southwell rule:
  - with different fixed learning rates

Lastly, we applied the developed models on a real public dataset (Banknote authentication dataset) achieving an oustanding accuracy of 92% with all the optimization algorithms.

Cerbaro Anna	
d'Addario Alessia	
Papadopulos	Eleni	
Ronzoni	Alice	

File explaination:
Cerbaro_dAddario_Papadopulos_Ronzoni.ipynb              => contains the main code
Cerbaro_dAddario_Papadopulos_Ronzoni_Real_Dataset.ipynb => contains the problem applied on a real dataset
data_banknote_authentication.txt                        => contains the real dataset
Cerbaro_dAddario_Papadopulos_Ronzoni.pdf                => contains the report
