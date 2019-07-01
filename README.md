# Parameter-Tuning-ML
Parameter Tuning for Better Accuracy for All Algorithms in Machine Learning
Machine learning involves predicting and classifying data and to do so, you employ various machine learning models according to the dataset. Machine learning models are parameterized so that their behavior can be tuned for a given problem. These models can have many parameters and finding the best combination of parameters can be treated as a search problem. But this very term called parameter may appear unfamiliar to you if you are new to applied machine learning. But don’t worry! You will get to know about it in the very first place of this blog, and you will also discover what the difference between a parameter and a hyperparameter of a machine learning model is. This blog consists of following sections:

What are a parameter and a hyperparameter in a machine learning model?
Why hyperparameter optimization/tuning is vital in order to enhance your model’s performance?
Two simple strategies to optimize/tune the hyperparameters
A simple case study in Python with the two strategies
Let’s straight jump into the first section!

What is a parameter in a machine learning learning model?
A model parameter is a configuration variable that is internal to the model and whose value can be estimated from the given data.

They are required by the model when making predictions.
Their values define the skill of the model on your problem.
They are estimated or learned from data.
They are often not set manually by the practitioner.
They are often saved as part of the learned model.
So your main take away from the above points should be parameters are crucial to machine learning algorithms. Also, they are the part of the model that is learned from historical training data. Let’s dig it a bit deeper. Think of the function parameters that you use while programming in general. You may pass a parameter to a function. In this case, a parameter is a function argument that could have one of a range of values. In machine learning, the specific model you are using is the function and requires parameters in order to make a prediction on new data. Whether a model has a fixed or variable number of parameters determines whether it may be referred to as “parametric” or “nonparametric“. 

Some examples of model parameters include:
The weights in an artificial neural network.
The support vectors in a support vector machine.
The coefficients in a linear regression or logistic regression.
What is a hyperparameter in a machine learning learning model?
A model hyperparameter is a configuration that is external to the model and whose value cannot be estimated from data.

They are often used in processes to help estimate model parameters.
They are often specified by the practitioner.
They can often be set using heuristics.
They are often tuned for a given predictive modeling problem.
You cannot know the best value for a model hyperparameter on a given problem. You may use rules of thumb, copy values used on other issues, or search for the best value by trial and error. When a machine learning algorithm is tuned for a specific problem then essentially you are tuning the hyperparameters of the model to discover the parameters of the model that result in the most skillful predictions. 

According to a very popular book called “Applied Predictive Modelling” - “Many models have important parameters which cannot be directly estimated from the data. For example, in the K-nearest neighbor classification model … This type of model parameter is referred to as a tuning parameter because there is no analytical formula available to calculate an appropriate value.” 

Model hyperparameters are often referred to as model parameters which can make things confusing. A good rule of thumb to overcome this confusion is as follows: “If you have to specify a model parameter manually, then it is probably a model hyperparameter. ” Some examples of model hyperparameters include:

The learning rate for training a neural network.
The C and sigma hyperparameters for support vector machines.
The k in k-nearest neighbors.
