File Structure:
\project
	\train.py
	\test.py
	\cnn_model
	\README.txt
	\Report
	\Extra_credit

The project folder contains two sets of python files. One for easy data set and
other for the hard data set. The poject folder also contains the pre-trained model
that is required for the test file to run.

-----------------------------------------------------------------------------------------
Libraries and Packages:
sys, pickle, numpy, PIL, matplotlib, tenserflow, keras.
-----------------------------------------------------------------------------------------

Steps to run the code:

1. For training: $python train.py
Path to data and label file has been hardcoded


2. For testing: $python test.py <path_to_data_file> <path_to_labels_file>

Path to model has been hardcoded
cnn_model and test.py should be in the same folder

The file saves 2 variables
prediction - vector of predicted labels.
accuracy - The accuracy of the model on current data set.
