# SeniorProject
Cal Poly Senior Project 2018-2019

Results of running oversampling, undersampling, and SMOTE sampling methods on various datasets using WEKA api.

**Guide to Files**

Each dataset has a folder. Within the folder, you will find the following files/directories:

  1. &lt;dataset name&gt;Undersampling - contains 100 result files from the dataset being undersampled
  
  2. &lt;dataset name&gt;Oversampling - contains 100 result files from the dataset being oversampled
  
  3. &lt;dataset name&gt;SMOTE - contains 100 result files from the dataset being sampled with SMOTE
  
  4. &lt;dataset name&gt;&#95;A.arff - the unsampled (no sample) file (for training)
  
  5. &lt;dataset name&gt;&#95;B.arff - the unsampled (no sample) file (for testing)
  
  6. &lt;dataset name&gt;.csv - the original dataset prior to sampling, column removal, and splitting into A and B.  
  
  7. &lt;dataset name&gt;&#95;A.csv - the dataset prior to sampling and non-featured column removal, but post splitting into A and B (for training)
  
  8. &lt;dataset name&gt;&#95;B.csv - the dataset prior to sampling and non-featured column removal, but post splitting into A and B (for testing)

