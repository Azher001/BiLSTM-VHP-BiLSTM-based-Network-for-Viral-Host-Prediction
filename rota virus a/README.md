1) The first file is the 'Creating rota virus A dataset from NCBI Virus data.ipynb' file. The file contains the code for creating the rotavirus A dataset. Using the codes of this file, the dataset was generated from the curated rotavirus A data from NCBI Virus Database.

2) After creating the dataset, preprocessing of the data was done to resize the sequences to 400 bases and to replace the unknown characters with 'N'. The codes are in 'rota virus A Dataset Preprocessing.ipynb' file.

3) After preprocessing, Five fold validation data was generated. The code is in 'Generate 5 fold from preprocessed rota virus A train dataset.ipynb'.

4) Finally, 'BiLSTM_VHP Rota Virus A model training and testing.ipynb' file contains the code of creating, training and testing the model.
