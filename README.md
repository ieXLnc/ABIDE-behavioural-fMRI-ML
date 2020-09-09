# ABIDE-behavioural-fMRI-ML
Predicting autism using behavioural and fMRI data

---- README ----

ABIDE2_EDA_BEHAVIOURAL: in this notebook I explore the behavioural data of the ABIDE 2 dataset. I look at the differences that exist between sites of acquisition, the features and their usefulness to classify ASD. I create 3 sub-datasets to perform my models, each one with different features from different psychological tests used to detect ASD:

Behavioural_df1_abide2 : notebook with the models of the first dataset with the SRS/BRIEF/IQ tests
Behavioural_df2_abide2 : notebook with the models of the second dataset with the SRS/RSBR tests
Behavioural_df3_SRS_only : notebook with the models of the third dataset with the SRS test
Each of these three notebooks is composed of a short exploration, decision tree, random forest, kNN and SVM models.

fMRI_ABIDE1_download_transform: is where I download the data and transform them to use them in the EDA and the models part. 

ABIDE1_EDA_fMRI: Exploration of the fMRI data.

fMRI_Models: The models of the datasets created in the download_transform notebook. Its composed of linearSVC/SVM models.
