# Signature-based-IDS
A host-based, signature-based intursion detection system utilizing Threat Hunter Playbook and Security-Datasets.

This is a 4th-year final project of UoA. To meet the requirements of school, a [report](https://github.com/L-yue-0112/Signature-based-IDS/blob/main/SIDS%20using%20imbalanced%20datasets.pdf), 
a [poster](https://github.com/L-yue-0112/Signature-based-IDS/blob/main/Poster.pdf), and a [code listing](https://github.com/L-yue-0112/Signature-based-IDS/blob/main/Code_listings.pdf) are also provided.

The results of this study are presented in the form of 5 different scenarios, and thus codes are structured into
the 5 scenarios. Which are:
Scenario 1. Using decision trees to classify the original datasets.
Scenario 2. Using decision trees to classify the oversampled datasets.
Scenario 3. Using DNN to classify the oversampled datasets.
Scenario 4. Using decision trees to classify the synthetic datasets.
Scenario 5. Using DNN to classify the synthetic datasets.

![workflow](/Images/workflow.png)


Since we used Jupyter Notebook in this project, there is no specific input, and outputs are all in the files.
However, you may need to make sure that you have the correct datasets in the correct file paths if you want to run the notebook.
- Specifically, all the files under the file "Hunting" with the name "hunt.ipynb" are codes for utilizing the Threat Hunter Playbook for different datasets.
- To get the results of Scenario 1, you should run "Scenario 1.ipynb".
- To get the results of Scenario 2, you should run "Scenario 2.ipynb".
- To get the results of Scenario 3, you should run "Scenario 3.ipynb".
- To get the results of Scenario 4, you should run all the files prefixed with "CTGAN_" under "Synthetic Data".
- To get the results of Scenario 5, you should run "Scenario 5.ipynb".

The original and generated datasets are available to simplify the reproduction of results, if necessary. 
While the models for CTGAN are recorded, they cannot be included due to size limitations. If you do not want to train your own models to generate synthetic datasets, 
please contact me for access to the recorded models.
Additionally, decision tree graphs are presented under the file "DecisionTree" for reference.
