# Tree Tensor Network Classifiers

In this repository we present the code needed to implement a classifier for High Energy Physics events using a Tree tensor Network architecture.


<center>
    <img src="./workflow.png" alt="Drawing" style="width: 500px"/>
</center>


## Dataset
The dataset employed is the so-called Baldi `HIGGS` dataset. It is not included here due to its dimensions but it can be downloaded [here](https://archive.ics.uci.edu/ml/datasets/HIGGS).

In order to run the code, the dataset should be downloaded from the previous link and positioned in the `data/` folder (which has to be created inside the main folder of this repository).



## Structure of the repository

The repository is organized as follows:
- **`src`**: this folder contains the code needed to implement a TTN classifier alongside with an example of its implementation and some script that can be used to tune the model and/or train a model with specific parameter;
- **`plot`**: this folder contains the code needed to realize all the plots shown in the final report of the project;
- **`report`**: this folder contains a PDF report showing the results of the project;
- **`model`**: this folder contain some trained architectures including the one presented as the best model in the project report;
- **`json`**: this folder contains the history of some of the trained model and the results of the tuning procedure we conducted;
- **`references`**: this folder contains some of the literature we used as reference.

For more detailed information, it is possible to refer to the dedicated README file of each folder.



## Requirements

The packages required to correctly execute the code in this repository are contained in the **`requirements.txt`** file.

Instead of directly installing all the required packages we suggest the creation of a dedicated environment using the Anaconda (or pip) package manager, if you already have it installed you can create the environment by running

```
conda install --name tn-env --file requirements.txt
```
