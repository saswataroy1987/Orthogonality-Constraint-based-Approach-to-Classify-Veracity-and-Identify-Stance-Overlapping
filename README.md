# Towards an Orthogonality Constraint-based Feature Partitioning Approach to Classify Veracity and Identify Stance Overlapping of Rumors on Twitter
## Authors : __Saswata Roy, Manish Bhanu, Sourav Dandapat, Joydeep Chandra__

## Installation

### Prerequisite
----------------------
Python >= 3.6.

Anaconda 3

### Create Environment
Type the following command to create the environment "man" which contains all the required packages.

* conda env create -f man.yml

-----------------------

## Details

### Details of SeNoCe folder
 * The main model is kept inside the folder "SeNoCe". Neural network model is written in "rumour_Loss.py".
 * Execute "trainTestModel_Fast.py" file inside this folder.
 * Results and required files will be saved under "repo_Fast" folder.
 * Then Execute "resCal.py" file to get the Accuracy and Macro F score.
 * Use hyperopt to tune the hyperparameters of the provided model.

### Details of SeNoCe~(A-FeAg) folder
 * This folder contains the variant "SeNoCe~(A-FeAg)" which does not contain A-FeAg module.
 * Follow the similar steps of SeNoCe model to execute this variant

### Details of SeNoCe~(C-FePOr) folder
 * This folder contains the variant "SeNoCe~(C-FePOr)" which does not contain C-FePOr module.
 * Follow the similar steps of SeNoCe model to execute this variant

### Details of SeNoCe~(Source) folder
 * This folder contains the variant "SeNoCe~(Source)" which does not contain Source module.
 * Follow the similar steps of SeNoCe model to execute this variant

### Results
 * Additional Results are kept inside the "Results" folder.
 






## SeNoCe Architecture

![](SeNoCe.png)
