# Simple Artificial Neural Network (ANN) model
<p align="Header">
  <a href="https://flame-engine.org">
    <img alt="flame" width="400px" src="https://www.stonebridge.uk.com/blog/wp-content/uploads/2019/10/neuron-animation-blog.gif">
  </a>
</p>

# Case Study: Customer Churn Rate Prediction 
File names: 
 - Artificial_Neural_Networks_Case_Study.pdf
 - Artificial_Neural_Network_Case_Study_data.csv
 - Artificial_Neural_Network_Case_Study.py 
 - ANN_Case_Study_Sample_Output_1.png
 - ANN_Case_Study_Sample_Output_2.png

# About 
In this Case Study we predict the churning rate of the customers from the bank. In order to learn about bank's customers we will make use of one pf the Deep Learning techniques, the Artificial Neural Networks (ANN).
Moreover, we will use popular Python libraries such as Tensorflow, Keras and Machine Learning techniques such as Adam Optimizer to train the ANN model and predict the churn rates.  The data consists of 10K randomly selected customers. We will use customer's characteristics to determine his/her probability of leaving the bank. The data contains 13 variables characterizing 10L bank customers. These variables are CustomerId	Surname,	CreditScore, Geography	Gender, Age, Tenure	Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary and Exited. 
  
  - Customer data is stored in: Artificial_Neural_Network_Case_Study_data.csv

# Model setting
 - Activation function for Hidden Layer: Rectifier
 - Activation function for Output Layer: Sigmoid
 - Optimization method: Adam Optimizer
 - Cost function: Binary Cross Entropy
 - Number of epochs: 100
 - Batch size: 25

The combination of the Rectifier and Sigmoid activation functions is quite popular and this exact combination will be used in this case study as well, given that our goal is to estimate the probability that the customer will leave the bank. Given that the output variable is binary we use cost function Binary Cross Entroopy.
   - ANN model training and testing: Artificial_Neural_Network_Case_Study.py
   
 # Case study paper
   - ANN case study paper: Artificial_Neural_Networks_Case_Study.pdf
   
   
## References


@article{Xavier2011,
  title = {Deep Sparse Rectifier Neural Networks}, 
  author = {Xavier Glorot and Antoine Bordes and Yoshua Bengio}, 
  booktitle =  {Proceedings of the Fourteenth International Conference on Artificial Intelligence and Statistics}, 
  pages = {315--323}, 
  year = {2011},
  volume = {15}, 
  series = {Proceedings of Machine Learning Research}
  publisher = {JMLR Workshop and Conference Proceedings}, 
  pdf = {http://proceedings.mlr.press/v15/glorot11a/glorot11a.pdf}
}
 
