# Tree Tensor Netowrk Classifiers

In this repository we presente the code needed to implement a classifier for High Energy Physics events using a Tree tensor Network architecture.

## Dataset
The dataset utilized is the so-called Baldi HIGGS dataset. The dataset is not included due to its dimensione but can be [downloaded here](https://archive.ics.uci.edu/ml/datasets/HIGGS).

 In order to run the code the dataset should downloaded from the previous link and positioned in the ` data/` folder (the folder has to be created inside the main folder).

 ## Structure of the repository

The repository is organized as follows:
- **src**: this folder contains the code needed to implement a TTN classifier alongside with an example of its implementation and some script that can be used to tune the model and/or train a model with specific parameter
- **plot**: this folder contains the code needed to realize all the plots shown in the final report of the project
- **report**: this folder contains a PDF report showing the results of the project
- **model**: this folder contain some trained architectures including the one presented as the best model in the project report
- **json**: this folder contains the history of some of the trained model and the results of the tuning procedure we conducted
- **references**: this folder contains some of the literature we utilized

For more detailed information please refer to the dedicated README file of each folder.