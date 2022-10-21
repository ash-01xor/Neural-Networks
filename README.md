# <b>Neural-Networks</b>
Implementing Black and White Box Neural Networks for the same dataset and interpreting its results.

## <b>What are White and Black Box Neural Networks?</b>
Simply put

  White Box models:
  - White Box models are transparent regarding how it arrives at a conclusion or provides insights for a given dataset
  
  Black Box models:
  - These models provides insights to a given dataset but isnt really clear or rather we do not know the working of it.
  
  Refer for more:[Black-box vs White-Box models](https://towardsdatascience.com/machine-learning-interpretability-techniques-662c723454f3)
  
## <b>Description of the Dataset:</b>

This dataset is a  smaller subset of the dataset which was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

- Cleveland: 303 observations
- Hungarian: 294 observations
- Switzerland: 123 observations
- Long Beach VA: 200 observations
- Stalog (Heart) Data Set: 270 observations. 

It consists of 14 attribute , where 1 is the target feature which needs to be predicted.

The objective is to classify whether a given person has a heart disease or not

## <b>Activation Function Used:</b>

What is a Activation function?

- Activation function basically decides if the neuron needs to be activated or not. It derives output from a given set of input layers or nodes.
- Further Reading:[Activation Functions](https://towardsdatascience.com/activation-functions-neural-networks-1cbd9f8d91d6)

- I got to use Sigmoid as the activation function cause it is easier to calculate partial differential with respect to sigmoid function because of the presence of an exponential. 

## <b>Comparion of Black-Box and White Box results:</b>

- I choose <b>accuracy</b> as the metric on which both the models will be evaluated.While there are various others metrics on the basis of which the efficiency fo the model can be found it , Accuracy is the most simple and easy to understand metric. Hence it was chosen

- Black Box : 84.61
- White Box : 54.00

- The black box models simply performs way better than the white box model due to its more efficient and modular code.
