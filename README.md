# NeuralNetworks
## Background 
The purpose of the project was to create a machiene learning model that could accurately predict, whether or not an applicant will be successful if funded by Alphabet Soup. The criterion of accuracy set for the model was >75%.
## Process 
The maximum accuracy achieved was approx 75%. The model with the best outcome was a basic neural network with one hidden layer which deployed ;(3x)162 neurons with input x=54, activation =relu, and epoch =50. The activation used for ouptut layer was sigmoid.For details see [AlphabetSoupChallenge2](https://github.com/Muzznah/NeuralNetworks/blob/master/AlphabetSoupChallenge-2.ipynb)

Steps taken to improve the accuracy of the model were:

  - preprocessing the data and changing the feature elements.("Name" feature, initially removed was added back in the second attempt to increase accuracy)
  - increasing epochs(but that had a negative impact on the accuracy in most cases)
  - changing the activation function (see first attempt [AlphabetSoupChallenge](https://github.com/Muzznah/NeuralNetworks/blob/master/AlphabetSoupChallenge.ipynb)
  - increasing the hidden layers
  - increasing the number of neurons in a layer
  
## Notes and Recommendations 

It was noted that the model preformed better with a simple neural network with one hidden layer as opposed to a deep neural network. For deep neural network the model's perfomance dropped with increasing epoch. It seems that the data responds much better with a simpler model hence, other options to explore for increased accuracy could be used of logistic regression models like Easy Ensemble AdaBoost, Random Forest and Support Vector Machine.

## Resources
### Data
### Software
Python 3.7.7, Jupyter Notebook 6.1.1, tensorflow 1.14.0, scikit-learn 0.23.1, and pandas 1.1.0

