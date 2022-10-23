# Artificial Neural Network [ANN]
An attempt to build a whitebox and blackbox implementation of Artificial Neural Networks to undersatnd how ANN learns.

# Data

  | $x_{1}$ | $x_{2}$ | y |
  | -- | -- | - |
  | 1  | 0  | 1 |
  | 1  | 1  | 1 |
  | 0  | 1  | 0 |
  | 0  | 0  | 0 |
  
  relation : y = $x_{1}$
  
  2 Input variables $x_{1}$ , $x_{2}$<br>
  1 Output variable y

# Neural Net Design
  
  Hidden layers : 1 (2 Neurons)  

  ### Activation Function Used
  * Hidden Layer : Sigmoid
  * Output Layer : Sigmoid
  
 # Results 
 
  As expected the blackbox results were more accurate than whitebox. Whitebox results were biased towards output 1 even though it seemed to be learing and updating its    weights through back propagation.
