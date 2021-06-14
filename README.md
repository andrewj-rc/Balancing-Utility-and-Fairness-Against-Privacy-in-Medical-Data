# Balancing-Utility-and-Fairness-Against-Privacy-in-Medical-Data
This repositiry contains the .csv files with the raw data as well as the outputs from the expermients performed in chapters 3, 4, and 5. 
Additionally the notebooks are included with the experimental procedures included. 
Certain base files in the python sci-kit learn package were altered in order to perform these experiments.  These 

These files contain the raw results from testing preformed on real world open source data.  Included are the standard deviations for the various measures from running 10 random train test splits.

Files here are organised by: 

The dataset the results are from the UCI Adult Dataset or the German Credit Dataset or the MEPS dataset: AdultData, GermanData, or MEPS
The method of deidentification differenetial privacy or k-anonymity: DifPriv or kAnon
The dataset the classifier was tested against either deidentified or original: TestDeid or TestOrig
