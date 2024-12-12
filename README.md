# ELM_based_IDS
Evaluation of ELM model for Intrusion Detection System(IDS) to improve cloud security.

- This repository provides the source code of the experiments conducted for evaluating and comparing extreme learning machine based IDS with other ML algorithms such as random forest, decision tree, naive bayes, artificial neural network and deep neural network.
- This experiment utilises the source code from ["Evaluation of Machine Learning Algorithms in Network-Based Intrusion Detection System"](https://github.com/tuanhong3498/Evaluation-of-Machine-Learning-Algorithm-in-Network-Based-Intrusion-Detection-System?tab=readme-ov-file) for the ML algorithms that to be compared.
- This work is done as part of practicum for Masters.

The following of this file provides information on instruction to execute the Jupyter Notebook.
## Instruction to run the notebook
The output of execution results are available in the notebook. In case some would like to run the notebooks on their own, please take note of the following:

1. In this experiment, CSE-CIC-IDS2018 dataset is used but has not been uploaded to this repository due to the size constrain.
   
   The dataset that are used for this work and its source are listed below (please note that the dataset are created by other studies and is not part of this work):
   ### CSE-CIC-IDS2018 dataset
   source: https://registry.opendata.aws/cse-cic-ids2018/
2. Make sure to update the path to load dataset.
3. The software environment that has been used for execution of the notebook is:

   - conda 24.5.0,
   - Python 3.12.4
   - scikit-elm 0.21a0
