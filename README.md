# deep-learning-challenge
A deep learning project using Python, Pandas, sklearn, TensorFlow, Google Colab
  
## Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. I will use my knowledge of machine learning and neural networks, using the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, I have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

## Steps Taken
* Data Preprocessing:
  * Our target variable is the IS_SUCCESSFUL column
  * The features for our model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
  * The EIN and NAME columns were removed because they are identification variables and not necessary.

* Compiling, Training, and Evaluating
  * Several models were tested, changing the number of hidden layers, nodes, epochs and activation functions.
  * The final model includes:
    * The first hidden layer with 8 nodes and the activation function relu
    * The second hidden layer with 5 nodes and the activation function relu
    * An ouput payer with the activiation function sigmoid
   * I was not able to reach th target performance. Each model tested would not get an accuracy rate higher than the final model displayed
     in this work. The model shown reflects the following: Loss: 0.5610789060592651, Accuracy: 0.7279300093650818
     
 ## Summary
 The models I worked on, before and after optimization, were only able to achieve around 73% accuracy. Several models were tested, changing 
 the number of hidden layers, nodes, epochs and activation functions. Making changes to optimize the model only made slight changes in the 
 accuracy; however, I found that adding too many layers hindered the performance. In order to solve this problem, I would need to continue to
 work on finding the optimal number of nodes and hiddenlayers, as well as the best activation function for each hidden layer.
 
 
 
