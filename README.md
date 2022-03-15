# Life Saving Decision Support System
I developed a Decision Support System using a Bayesian Network to decide the best life-saving procedure based on user inputs and wearable technology

## Code and Resources
* **Python version:** 3.7
* **Packages:** pgmpy, numpy, networkx, matplotlib

## Project Overview
* Developed a Decision Support System (DSS) that can determine whether a person needs resuscitation using user inputs into an app and live data from wearable devices.
* Set Objective, Task and Constrains
* Create a Conseputal Design of the DSS
* Implementation of the DSS using Bayesian Network as a knowledge model in python
* Query the DSS to obtain the best decision in different scenarios

### Project Objective
Develop a Decision Support System that can determine whether a person needs
resuscitation using basic inputs into an app and live data from wearable devices.
The background knowledge for the DSS will be designed as a Bayesian Network and
will be implemented in python.

### DSS Task:
Give advice if resuscitation is required in an emergency case and if it needs to be
cardiopulmonary resuscitation (CPR) or mouth-to-mouth only.
 
### Constrains: 
The number of network nodes is limited to 6 as per recommended guidelines.
Based on live data collected from a smartwatch and people around him, the DSS will
be able to decide whether a person needs resuscitation. Therefore, it may not be
suitable for resuscitation of babies, toddlers, and small children for whom wearable
devices have yet to be developed.

### Graphical representation and associated probabilities:
![alt text](https://github.com/CarolinaKra/LifeSavingDSS/blob/main/graph.png)

### Initial Probabilities of Output Node based only on Prior Probabilities (no further evidence)
![alt text](https://github.com/CarolinaKra/LifeSavingDSS/blob/main/InitialProbabilities.png)

### Example of Quering the Network giving evidence
My friend is has drown in the swimming pool and I managed to take him out. He is unconcious, his smartwatch detects a low saturation value but detects heart rate, what should I do?

![alt text](https://github.com/CarolinaKra/LifeSavingDSS/blob/main/m2mprobabilities.png)




