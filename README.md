 # Perceptron
 
 What is a perceptron?
    A perceptron is a single layer neural network. It is a binary classifier (i.e, linear classifier) which helps to classify the given    input data.
 
 *  Perceptron can represent basic logic gates such as OR, AND, NOT gates as well as NAND, NOR gates.
 *  Perceptron can be usefull in classifying any data that is linearly separable. It may not be well suitable for non-linear classification.
 
 A perceptron consists of 4 parts:
 1. Input values
 2. Weights and bias
 3. Summation
 4. Activation Function
 
 Perceptron Training Rule
 1. Initialize with random weights(w).
 2. For each example(x) in training data D, perform the following steps:
    a.  Calculate the actual output
        y(t) = w0.x0 + w1.x1 + ... + wn-1.xn-1
    b.  Update the weights
        w = w + (y(t) - O)
        where, 
              y(t) = actual output
              O = class output
                        
 Activation Function:
   Various activation functions that can be used are:
   1. Unit step.
   2. Linear.
   3. Sigmoid or Logistic.
   4. Hyperbolic tangent.

 For more information:
   * https://nptel.ac.in/courses/106105078/pdf/Lesson%2038.pdf
   * https://www.youtube.com/watch?v=5g0TPrxKK6o
