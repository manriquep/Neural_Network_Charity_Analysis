# **Neural\_Network\_Charity\_Analysis**

**Overview**

Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

**Results**

**Data Preprocessing**

- What variable(s) are considered the target(s) for your model? 
    I consider that the target for my model is the &quot;IS\_SUCCESSFUL&quot; column.

- What variable(s) are considered to be the features for your model? 
     EIN, NAME, APPLICATION\_TYPE, AFFILIATION, CLASSIFICATION, USE\_CASE, ORGANIZATION, STATUS, INCOME\_AMT, SPECIAL\_CONSIDERATIONS, ASK\_AMT, IS\_SUCCESSFUL.

- What variable(s) are neither targets nor features, and should be removed from the input data? EIN, NAME.

**Compiling, Training, and Evaluating the Model**

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

    I ran through different models, trying hidden layers of three, four and five. I also increased the neurons for each hidden layer which although a potential for overfitting,       was showing slight improvement.

- Were you able to achieve the target model performance?

    The base model of 0.7297 was slightly improved to 0.7350 but did not reach the target of 0.750.

- What steps did you take to try and increase model performance?

    Additional neurons were added to the hidden layers, additional hidden layers were added to the model, and the activation function of the hidden layer was changed from relu to     tanh.
