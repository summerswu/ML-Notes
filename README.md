# ML-Notes
This document is used to document my learning journey 

Learning to See(Welch Labs): 2 hours
-
https://www.youtube.com/watch?v=i8D90DkCLhI

1. The idea of machine learning itself is kind of ill posed
2. Assumptions must be made
3. How you find the data and how you arrive at the assumptions to optimize the model is the most important thing 

Bias - Variance Trade-off (Overfitting and Underfitting)

Decision Tree- a greedy algorithm - important thing is: Arriving at a impurity function that improve the accuracy of the classifier(this turns out to be a inverted parabolic function)

The Machine Learning Process: 

Using Pandas - import the dataframe
Labeling and cleaning using NumPy - split into training data and testing data.
From a high level, use Scikit Learn library to train a model (Parameter Adjustments must be made for specific cases)

Three Blue One Brown Machine Learning Serie - Deep Learning Introduction:
 - 
Convolutional Neural Network - good for image recognition 
Long-short term memory network - good for NLP

### Introduction Variant - Vanilla: Multilayer Perceptron
  - Includes 
    Neurons, neurons are activated by some input, each neuron path way have a weight - transform inputs by sigmoid(compressing the number line from one to zero)
  - Bias, a set value to offset the sigmoid activation function of each neuron, all this can be represented by a matrix multiplication as well as addition`
  Note: Sigmoid is kind of old school now, the new Industry standard is rectified linear unit(simplification)
  
### Gradient Descent
  
  - finding the minimum of the cost function is the key to how neural network works
  - finding the average cost would give you how wrong this network is (this is really complicated with all the parameters)
  
  Trying to approach the local minimum of this cost function by finding the slope at a given spot then move the direction of local minimum 
  - find the local minimum is not that hard, finding the global minimum is
  
  Gradient Descent is just doing this shit in the 3-D plane - gradient vector of a 3D space
  
### Backpropagation 

  - the way the gradient vector is calculated
  
   
  
  
  
   
  
  

