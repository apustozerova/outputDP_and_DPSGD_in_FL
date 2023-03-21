# Differentially Private Federated Learning

This Repository contains the code used for running the experiments for the paper "Differential Privacy in Federated Learning: An analysis of Output
Perturbation and differentially-private SGD"

Files

    'algo.py': This script implements a logistic regression algorithm, which can be trained with DP-SGD. 
    
    'attack.py' : contains methods allowing to perform memberhsip inference attack
    
    'federated.py' : contains methods allowing to execute federated learning
    
    'scripts.py' : contains methods allowing to perform output perturbetion
    
    'main.py' : allows training logistic regression in centralised setting with DP SGD and Output Perturbation
    
    'fl_main.py' : allows training logistic regression in federeated setting with DP SGD and Output Perturbation
    
    
Usage

To use these scripts, you will need to have Python3.10 installed on your system. You can recreate conta environment from 'newenv.yml', containing all necessary libraries and frameworks.
