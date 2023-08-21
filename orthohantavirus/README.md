1) The first file is the 'Creating Orthohantavirus dataset from NCBI Virus data.ipynb' file. The file contains the code for creating the orthohantavirs dataset. Using the codes of this file, the dataset was generated from the curated orthohantavirus data from NCBI Virus Database.

2) After creating the dataset, preprocessing of the data was done to resize the sequences to 400 bases and to replace the unknown characters with 'N'. The codes are in 'Orthohantavirus Dataset Preprocessing.ipynb' file.

3) After preprocessing, Five fold validation data was generated. The code is in 'Generate 5 fold from preprocessed orthohantavirus train dataset.ipynb'.

4) Finally, 'BiLSTM_VHP_Orthohantavirus model training and testing.ipynb' file contains the code of creating, training and testing the model.
