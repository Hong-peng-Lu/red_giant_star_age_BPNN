
RG_spectra_Age.xlsm --- Our reseach sample: the stellar parameters corresponding to the 5349 LAMOST spectra.

random.xlsm --- When we use the BP neural network to train the model, it is used to randomly assign the random numbers of the training data and the test data.

Modeling.m --- This is a program to build a red giant star age estimation model using BP neural network training data, which uses (1:Teff,2:logg,3:[Fe/H],4:��max, 5:delta ��) as input parameters.

Optimal_model.mat --- This is the best red giant age estimation model structure obtained when using (1:Teff,2:logg,3:[Fe/H],4:��max, 5:delta ��) as input parameters.

Call_best_structure_to_estimate_age.m --- This is a MATLAB program that calls 'Optimal_model.mat' to predict the age of red giant stars.




