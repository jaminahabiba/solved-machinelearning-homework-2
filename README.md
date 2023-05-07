Download Link: https://assignmentchef.com/product/solved-machinelearning-homework-2
<br>
Implement the linear perceptron using stochastic gradient descent (SGD) or  gradient descent (GD). Download the dataset “data3.mat”. Use the whole data  set as trainmg, where each row consists of the feature vector x followed by the  label y e { l, l} (last column). Show with figures the resulting linear decision boundary on the 2d x data. Show the evolution of binary classification error  and the perceptron error with time (or number of iterations) from random  Initialization until convergence on a successful run (some random inits may not  converge or may require many iterations). For GD, discuss the convergence behavior as you vary the step size (n).

Problem 2

Consider the following network, where denotes output units, y denotes hidden  units, and z denotes input units.

Consider:

<ol>

 <li>a) [8 points] The cross-entropy error for a single example is:</li>

</ol>

— ti) log(l — Ti)),

where t is the target, and the logistic activation function for the output

units is:

1

where Si =

yjWji,

1 e¯Si

where u;j, denotes the weight of the edge between the jth hidden unit  and the ith output unit. Assume hidden layers also use logistic activation

function.

<ol>

 <li>b) [7 points] The modified cross-entopy error for a single example is:</li>

</ol>

E = <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="b09df5c49edcdfd7f0d9">[email protected]</a>)

and a softmax activation function for the output units is:

EST’

where m is the number of outputs and the summation is taken over all  outputs. Assume hidden layers use logistic activation function.

Derive the back propagation updates in both cases (use the above error functions defined with respect to a single training example for your derivations rather than  the sum Of errors over the entire training dataset).

Problem 3

Consider the discrete distribution {Pklk = 1, 2, , N}. The entropy of this  distribution is given as H = — log Pk. What is the distribution (hat maximizes this entropy? Show formal derivations using the method of Lagrange multipliers.

Problem 4

What is the VC dimension of axis-aligned squares? Justify your answer.