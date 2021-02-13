# Simple Artificial Neural Network (ANN) 
<p align="Header">
  <a href="https://flame-engine.org">
    <img alt="flame" width="400px" src="https://www.stonebridge.uk.com/blog/wp-content/uploads/2019/10/neuron-animation-blog.gif">
  </a>
</p>


## About the Case Study
In this Case Study we predict the churning rate of the customers from the bank. In order to learn about bank's customers we will make use of one pf the Deep Learning techniques, the Artificial Neural Networks (ANN).From the millions of customers we have randomly selected 10K customers. We will use customer's characteristics to determine his/her probability of leaving the bank. In order to learn about bank's customers we will make use of one pf the Deep Learning techniques, the Artificial Neural Networks (ANN).
Moreover, we will use popular Python libraries such as Tensorflow, Keras and Machine Learning techniques such as Adam Optimizer to train the ANN model and predict the churn rates.

  - DATA: Customer data is stored in: Artificial_Neural_Network_Case_Study_data.csv
  - PAPER: ANN case study paper: Artificial_Neural_Networks_Case_Study.pdf
  - CODE: Artificial_Neural_Network_Case_Study.py 
  - SAMPLE_OUTPUT = ANN_Case_Study_Sample_Output_1.png
  - SAMPLE_OUTPUT = ANN_Case_Study_Sample_Output_2.png


## Model setting
The combination of the Rectifier and Sigmoid activation functions is quite popular and this exact combination will be used in this case study as well, given that our goal is to estimate the probability that the customer will leave the bank. Given that the output variable is binary we use cost function Binary Cross Entroopy. Following topics and technical are covered in the paper and in the rest of the files:
 - Activation function for Hidden Layer: Rectifier
 - Activation function for Output Layer: Sigmoid
 - Optimization method: Adam Optimizer
 - Cost function: Binary Cross Entropy
 - Number of epochs: 100
 - Batch size: 25
 - **ANN model training and testing:** Artificial_Neural_Network_Case_Study.py
      

## Sample outputs (screenshots)

**Training the ANN model**

<p align="left">
<img src="ANN_Case_Study_Sample_Output_1.png?raw=true"
  alt=""width="700" height="350">
</p>

**True versus Predicted values**

<p align="left">
<img src="ANN_Case_Study_Sample_Output_2.png?raw=true"
  alt=""width="700" height="350">
</p>


**References**
 - Glorot,  X.,  Bordes,  A.,  Bengio,  Y.  (2011).  Deep  Sparse  Rectifier  Neural  NetworksInternational Conference on Artificial  Intelligence and Statistics. Proceedings of the Fourteenth International Conference on Artificial Intelligence and Statistics, 15(15), 315 - 323
 - Rogerson, R. J. (2015). Adam:  A Method For Stochastic Optimization. 3rd Interna-tional Conference on Learning Representations (ICLR2015), 36(1), 1–13
 - LeCun, Y., Bengio, Y., Hinton, G., (2015). Deep learning.Nature, 521, 436 – 444
 -  Wiegerinck, W. and Komoda, A. and Heskes, T. (1999). Stochastic dynamics of learn-ing  with  momentum  in  neural  networks. Journal  of  Physics  A:  Mathematical  andGeneral, 27(13), 4425 – 4425


