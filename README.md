# MLTSA_FinalProject
Machine Learning Application in Epilepsy Diagnosis and Seizure Detection

Members: Janina Boecher, Kristina Rainich, Ilia Tiagin

Abstract: Epilepsy is a disorder of the central nervous system that affects approximately 1% of the population worldwide. Seizure detection constitutes the first steps towards accurate diagnosis and seizure warning mechanisms are critical to patients’ quality of life and safety. Electroencephalogram (EEG) is the most commonly used clinical tool to observe patterns of brain electricity and to assess changes associated with epilepsy. Manual inspection of EEG is time-consuming, error-prone, and dependent on the clinician’s choice of parameters. Recently, there has been great interest in developing machine learning (ML) algorithms to optimize diagnosis and seizure detection. Here, we implementer random forest classifier and convolution neural network to distinguish between seizure and non-seizure epochs in the EEG signal taken from the patients suffering from epilepsy.

In the main repository, there are the finalised files that we used for the project. In the 'tryouts' folder, there are draft Python notebooks for experiments. Most of our calculations and processing steps were performed on server because of the limited resourses in Collab. So, some of the files are the function for certain processing steps performed for a subset of data samples. The details for each of the notebooks are explained below. 

1. Edf_collection.ipynb and edf_tse_opening.ipynb - contains the code for extracting different filenames, .edf, and .tse files themselves for further analysis. The collection of data from the server where the data was stored originally was performed on the UD server.
2. Preprocess_pipeline.ipynb - contains the example of the function of how the data was preprocessed. The preprocessing itself was performed on the server because it was computationally too expensive and required a lot of memory.
3. Slicing_and_labeling.ipynb - contains the exmpla of the functions for segmentation and labeling of the data. Both of the steps were performed on the whole dataset on the server for the same reasons. 
4. Feature_extraction.ipynb - contains the function and the example of features that we extracted for further classification using random forest.
5. Random_Classifier.ipynb - the code for the random forest classification.
6. cnn_classifier.ipynb - the code for the CNN model.

Dr. Bianco, given that we ran practically all of our analysis on the server, our code is not exactly reproducible. We posted all the code like this, but if you would like it to be presented differently, please let us know we will try to make the changes asap. 


