# Deep Learning Challenge Report

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing
    What variable(s) are the target(s) for your model?

    A: The target variable for this model is the 'IS_SUCCESSFUL' value.

    What variable(s) are the features for your model?

    A: The features contain every other column from the original dataset minus the unnecessary values.

    What variable(s) should be removed from the input data because they are neither targets nor features?

    A: 'EIN' and 'NAME' were not beneficial in tuning the model and were dropped from the original dataset as a result.

Compiling, Training, and Evaluating the Model
    How many neurons, layers, and activation functions did you select for your neural network model, and why?

    A: After optimizing the model I chose to stick with a similar number of nodes as the first run but added an additional layer ending up with 3 layers consisting of 80, 50, and 30 nodes.

    Were you able to achieve the target model performance?

    A: I was not able to achieve the target model performance as many changes and optimizations made seemed to have little to no effect on the result.


    What steps did you take in your attempts to increase model performance?

    A: I added the extra layer to the model, adjusted the activation functions associated with said layers, and decreased the nunmber of epochs the model was run with.


Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

A: In both the initial creation of the model as well as the final version after attempting to optimize the accuracy of the model stands just under 73%, ranging anywhere from 72.5% to 72.8%. While additional testing and iterations can be done to find just the right amount of layers, nodes, and epochs that could lead to the target accuracy, my recommendation for a new model would include adjusting the original data. More cleanup with the data to eliminate outliers and/or adding additional data that the model can use to train with should allow for a higher accuracy.

