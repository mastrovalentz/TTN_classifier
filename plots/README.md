# TTN classifier plots

In this folder the Jupyter notebooks used to produce all the plots shown in the final report are contained.

The `plots.ipynb` notebook contains:
- plots of the dataset features
- plots of the comparison between "standard" and optimized TTN
- plots of the TTN characterization, in particular perfomance and time scaling dependence on
    - bond dimension
    - feature map and map order
    - batch size

The `plots_FinalModel.ipynb` notebook contains:
- plots of the training history of our best model
- performance evaluation and performance plots of the model
    - ROC curve and AUC score
    - Test accuracy and confusion matrix

#### CAREFULL!
The `plots_FinalModel.ipynb` notebook performs the loading and preprocissing of the whole dataset. This operation requires a lot of memory (at least 20GB RAM are suggested), but it can be reduced lowering the number of loaded sample (through the *__N__*, *__N_train__*, *__N_val__*, and *__N_test__*, variables)