# A Physicist's View of Machine Learning: The Thermodynamics of Machine Learning

url: <https://towardsdatascience.com/a-physicists-view-of-machine-learning-the-thermodynamics-of-machine-learning-6a3ab00e46f1> \
tags: ml, physics, complex systems, thermodynamics

Analogy:

- ML models = dynamically System of smaller constituents (think particles)
- data = thermal bath (source of randomness/uncertainty)
  
Consequences:

- input perturbs/excites the model, output is the Model response
- minimizing model loss = minimizing energy of the System
- regularization terms = extra energy terms
- training = reorganization of the system into a lower state of energy

Entropy and the second law:

- entropy is maximized, System goes into most likely configuration 
- Training a model doesn't lead to the lowest energy state, but into the most likely configuration
- questionable if the ml model fulfills ergodicity

Thermal equilibrium:

- state of maximum entropy
- macroscopic behavior does not change anymore
- history of the dynamical system is completely forgotten
- overall model performance should not be sensitive to choice of data
