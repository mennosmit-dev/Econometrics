# Nowcasting GDP using a nonlinear mixed-frequency factor approach

This code executes an optimisation program to nowcast GDP using nonlinear factors obtained using kernel PCA. The hyperparameter of the Machine Learning model is tuned based on the last two comparable quarters for which GDP figures are unknown within the vintage data at a specific month in the quarter. The code also includes Ridge hyperparameters which can be tuned manually. Finally, the model is optimised under the BIC.
