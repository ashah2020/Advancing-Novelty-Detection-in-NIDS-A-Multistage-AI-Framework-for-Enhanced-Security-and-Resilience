# RESNIDS 
Deep ResNIDS is a multistage AI framework for intrusion detection in network traffic. Deep ResNIDS can effectively identify zero-day and adversarial attacks. Keeping a human in the loop Deep ResNIDS can also be efficiently retrained to adapt to new attacks and benign data encountered by the network.

# Implementation Guide
We provide a comprehensive guide needed to implement the framework. We describe the functionality of each folder created in this repository. 

Baseline Training - Contains the necessary code to train different elements (malicious packet detector, anomaly detector, novelty detector) of the ResNIDS framework. The output of the posted .ipnyb files are the trained models.

Retraining- Contains the necessary code required to perform the retraining of the aforementioned elements to adapt to new distributions of attack and benign data.

Dataset - Contains the datasets used to provide the experimental results table provided in the paper. Which includes, the datasets used to perform the baseline training for different elements of the framework, retraining, and corresponding testing.

Trained Models- In the trained models we have shared the saved baseline models and retrained models used to obtain the results exhibited in the paper.
