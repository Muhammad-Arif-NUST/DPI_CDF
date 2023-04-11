# DPI_CDF
DPI_CDF: Druggable Protein Identifier using Cascade Deep Forest


##Pipeline

###DPI_CDF uses the following dependencies:
* MATLAB2018a
*blast-2.6.0+
* python 3.7
* numpy
* scipy
*pandas
* scikit-learn 
* gc_forset
*xgboost-1.5.0


###Guiding principles:

**The data contains training dataset and testing dataset.
   Training dataset includes TR_DPI_CDF_pos and TR_DPI_CDF_neg
   Testing dataset includes TS_DPI_CDF_pos and TS_DPI_CDF_neg

**Feature extraction:
   CPSR is the implementation of component protein sequence representation.
   NQLC is the implementation of normalized qulitative characteristics of amino acid composition.
   HOG-PSSM cantain PSI-BLAST file and HOG (histogram of oriented gradient )descriptor to convert the extracted PSSM into (HOG-PSSM)
  
   

** Classifier:
  DPI_CDF.py is the implementation of proposed method to predict drugable proteins.
  
  
