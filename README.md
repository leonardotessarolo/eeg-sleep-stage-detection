# eeg-sleep-stage-detection

Repository for code used in Sleep Stage Detection via Deep Learning. Code description:

 - Notebook 1 downloads the Sleep-EDFX dataset, and also creates and selects features from EEG Signals.
 - Notebook 2 creates the dataset which will be used for model training and validation. TFRecord files are exported to a proc_dataset/ directory. Total size of dataset is about 2.2 GB.
 - Notebook 3 trains and evaluates three architectures using 5-fold CV. Folds are built by creating groups of subjects.
 - Notebook 4 analyzes performance metrics logged in notebook 3.

All Notebooks export artifacts into an artifacts/ directory.
