Using the gene expression profiling data from both cervical cancer patients with tumour and matched normal samples, I would like to find out which genes are the key components in causing cancer to distinguish between affected vs unaffected and further to use this finding to predict who will be classified as with or without tumour. 

This gene analysis is important in many health care nowadays where we can easily and quickly can find the genetic variability on a patient.  Using proposed model, many people can be prognosed of cervical cancer in earlier age and pharmaceutical companies can make drugs that will effectively target certain genes.  Moreover physicians would know which drugs to prescribe to target more accurately instead of blindly selecting cervical cancer drugs using traditional method of diagnosing cancer patients. 

The data is available at https://www.kaggle.com/thomasnelson/cervical-cancer-tumor-vs-matched-control and have gene expression of 29 normal and 29 tumour patients.  

With a quick look at the data, rows and columns could be rearranged to make gene expression as features.  Since we are classifying which is tumour and which is normal, I would use either a tree or clustering technique.  I think support vector machine might be a good way since there could be multiple dimensionality associated with this data set.   Also, I would consider using PCA to find the best suited genes.  

After finding which genes and which models work the best in predicting cervical vs normal, I will make a presentation slide and my code available for pharmaceutical companies. 
