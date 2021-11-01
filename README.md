# Neural_Network_Charity_Analysis
![img](https://github.com/Edgarhv/Neural_Network_Charity_Analysis/blob/3437127621d08738e7d1d9087d7650f064703893/AdeptMessyBass-mobile.gif)

###### Resource : https://gfycat.com/adeptmessybass-three-blue-one-brown-machine-learning

# Overview

For this challenge, I used Machine Learning and Neural Networks. The reason for this challenge was to create a binary classifier that will help to predict the future applicants that will be funded by a Charitable organization called Alphabet Soup. For this project, we had a dataset that contain various measures of different organizations that have been funded by Alphabet Soup.

# Results

-	What variable(s) are considered the target(s) for your model? 

*IS_SUCCESSFUL* 

- What variable(s) are considered to be the features of your model?

*Every Column except for IS_SUCCESSFUL*

- What variable(s) were neither targets nor features for the dataset?

*EIN and NAME because they will have no impact on our outcome*

### Compiling, Training, and Evaluating the Model

-How many neurons, layers, and activation functions did I select for my neural network model?

For my neural network model, I chose :

*2 hidden layers and the first layer had 80 neurons.*

*the second layer has 30 there is also an output layer.* 

![img](https://github.com/Edgarhv/Neural_Network_Charity_Analysis/blob/061bf4a22363e18a753988afb1ab81b193d74f94/Resources/Images/Neurons1.png)

- Was the model able to achieve the target model performance?

*No, the accuracy for my model was 53.3%.*

- What steps did you take to try and increase model performance?


Attempt 1: Removed additional feature, that is the USE_CASE column. The rest of the model components stayed the same, and model accuracy went  up to 70%

![img](https://github.com/Edgarhv/Neural_Network_Charity_Analysis/blob/65c7307b520954650676cd0bae32ff84bb6dffcb/Resources/Images/Neurons2.png)

Attempt 2: Adding Additional neurons to hidden layers and additional hidden layers are added. The accuracy went down, this time it was 53.3%.

Attempt 3: Changing activation function of output layer from "sigmoid" to "tanh." The accuracy of the model went down even more to 46.6%

![img](https://github.com/Edgarhv/Neural_Network_Charity_Analysis/blob/c5d8763f7a50adc685bba7a6f738b9ebe2aa6520/Resources/Images/Neurons3.png)
