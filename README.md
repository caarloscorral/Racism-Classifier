# Racism-Classifier
Racism model made with Weka.
It classifies if a person was killed by a police agent with racist motivation, so there was abuse of authority.

Attributes:
- Armed {True, False} --> the person was armed.
- Flee {True, False} --> the person was fleeing.
- Body_camera {True, False} --> the police agent was wearing a body camera and it was ON.
- Threat {True, False} --> the person was threated in some way.
- Racism {True, False} --> indicates whether the assassination was a hate crime. Class to predict.

Files:
- racism-classifier.model --> model to use with Weka.
- police-shootings-data --> dataset used to train and test the model using 10-fold cross-validation.
- police-shootings-train --> dataset used to train the model.
- police-shootings-test --> dataset used to test the model.
- police-shootings-true-data --> dataset with instances whose Racism class is True.
- police-shootings-false-data --> dataset with instances whose Racism class is False
- police-shootings-new-data --> dataset with instances whose Racism class is unknown, and we want to predict them.
