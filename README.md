Charity Analysis
----------------

Overview
--------
The purpose of this analysis was to use machine learning and neural networks to creat a binary classifier that is capable of predicting whether applicants will be successful in their funding jouney. 

Results
-------
* Target variable(s): Is_Successful
* Feature(s): The following columns were replaced with their one-hot encoded values - Application Type, Affiliation, Classification, Use_Case, Organization, Income_Amt, and Special_Considerations
![image](https://user-images.githubusercontent.com/82548977/131270067-a4735b74-6d74-4833-8437-723d85a8d9bc.png)

* Variable(s)/Feature(s) to be removed: EIN and Name
![image](https://user-images.githubusercontent.com/82548977/131270031-b82537d7-0894-4d86-a9f5-21a1e1fbf73d.png)


* Neurons, layers, and activation functions: The goal was to use a function that would test the relu, tanh, and sigmoid activation functions to find the best performing model. I initialized the model to have 75 layers in the first neuron and 25 layers in the second neuron.
* Was target performance achieved?: Unfortunately the model would error out when I was attempting to use kerastuner to search for the best hyperparameters - the error message stated that it "Failed to create a NewWriteableFile" and I was unable to successfully address this issue. 
* What steps were taken to try and increase model performance?: The step that was taken was to use a function to find the best hyperparameter to use but unfortunately this step errored out. Had this worked, however, I believe that I would have achieved target performnance of 75% or greater predictive accuracy. 

Summary
-------
Unfortunately since I was unable to successfully optimize the model, I am unable to recommend a different model setup to achieve optimal results. 
