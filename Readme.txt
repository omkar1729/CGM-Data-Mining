Two files - 1. Training Models and 2. Testing have been submitted along with the required datafiles for this project.

- Training Models file is the file used to train the 4 different models with the extracted features from the dataset. 
- Testing file can be used to get the predictions of the model on a given dataset. 

Frameworks used:
- The project has been done on Python Notebooks.
- Following libraries have been used: Pandas, Matplotlib, scikit-learn, numpy, pickle

Running the code:
- Open in python notebooks (maybe using jupyter notebook) and run all blocks in a given file.
- The models have been saved in <*Name of student*>.pkl.
- PCA weights have been saved in PCA.pkl, scaling factors of different attributes is stored in DataScale.pkl.
- Testing uses these files to predict the entries.
- The second block of testing has two parameters - cgm_file_name (which is the filename of the testing data csv) and output_file_name (which is the file in which the predictions will be stored).
- The output is stored as a csv, with the first row indicating which student's model the particular prediction is from (So, the predictions will be shifted by a row).