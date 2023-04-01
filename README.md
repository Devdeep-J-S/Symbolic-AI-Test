Name : Devdeep Shetranjiwala  
Email ID : devdeep0702@gmail.com

****

# GSoC Symbolic Calculation Project - 2023
# ML4Sci

---
Common Task 1. Dataset preprocessing 
> Description: Use Sympy or Mathematica to generate datasets of functions with their Taylor expansions up the fourth order. Tokenize the dataset.
---
Common Task 2. Use LSTM model

> Description:  Please train an LSTM model to learn the Taylor expansion of each function.
You can use a deep learning algorithm of your choice (in Keras/TF or Pytorch).

> In this example, we first define the function we want to approximate (func) and its Taylor expansion up to a certain degree (taylor). We then generate training data by evaluating func on a grid of points, and computing the corresponding Taylor approximation. </br>
We reshape the training data for the LSTM model, using a sequence length of seq_len = 10, and then define the LSTM model itself. We use a single LSTM layer with 128 units, followed by a dense layer with a single output.</br>
We compile the model using mean squared error as the loss function and the Adam optimizer, and then fit the model on the training data.</br>
After training, we can evaluate the model on a test set and compare its predictions to the true Taylor expansion of the function. Note that the quality of the approximation will depend on the degree of the Taylor expansion and the size of the training set.</br>
---
Specific Task 3: Use Transformer model
> Description: Please train a Transformer  model to learn the Taylor expansion of each function.
> To train a Transformer model to learn the Taylor expansion of each function, we'll need to prepare a dataset of input-output pairs, where the input is a function and the output is its Taylor expansion.
Here's an example of how you could prepare such a dataset:

> Input (function): sin(x) Output (Taylor expansion): x - x^3/3! + x^5/5! - x^7/7! + ... </br>
Input (function): cos(x) Output (Taylor expansion): 1 - x^2/2! + x^4/4! - x^6/6! + ... </br>
Input (function): exp(x) Output (Taylor expansion): 1 + x + x^2/2! + x^3/3! + ... </br>
Input (function): tan(x) Output (Taylor expansion): x + x^3/3 + 2x^5/15 + 17x^7/315 + ... </br>

## Colab link
> task 1 : https://colab.research.google.com/drive/17LRZZyG8vUHCH1PrxwtLNICDPKcHQ13i?usp=sharing </br>
> task 2 : https://colab.research.google.com/drive/1tAvAexircJimMbDkTH0-_QAqCu1n5SVb?usp=sharing </br>
> task 3 : https://colab.research.google.com/drive/1MGZSBqEZ0_DBkM7hkToQnHzfbxaSTYBk?usp=sharing

## Pdf of output link:
> link : 
