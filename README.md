# Pennylane_quantum-classifier
 This project implements variational quantum circuit for supervised classification in PennyLane+PyTorch. It uses patient diagnosis as a test subject for the proof-of-concept. The goal of the classification is to identify the proper drug to give for a specific patient. Dataset containing 200 patients is obtained from [Drug Classification on Kaggle](https://www.kaggle.com/prathamtripathi/drug-classification).

 The code follows closely on the tutorial [Multiclass margin classifier](https://pennylane.ai/qml/demos/tutorial_multiclass_classification.html) from PennyLane, in which the architecture of the variational circuit is inspired by [Farhi and Neven (2018)](https://arxiv.org/abs/1802.06002) as well as [Schuld et al. (2018)](https://arxiv.org/abs/1804.00633).

## Outlook
 - Reorganized code to encapsulate the multiclass variational classifier (with margin loss) in a module
 - Expand the collection of models in more modules
 - Compare the performance of different circuit in classification
