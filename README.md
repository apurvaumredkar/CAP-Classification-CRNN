# CAP-Classification-CRNN
A deep learning model based on Inception modules paired with gated recurrent units (GRU) for the classification of CAP phases (A/B). 

Dataset source: https://physionet.org/content/capslpdb/1.0.0/

The samples extracted from the raw dataset consists mainly of C4-A1 or C3-A2 EEG channels of duration 2s. Of total 16 subjects available in the dataset, 6 of them have an original sampling frequency of 512 Hz while 8 of them have been sampled using 128-1000 Hz (data for remaining 2 subjects is unavaiable). A balanced dataset was generated with the 6 subjects initially, consisting 9306 samples, later extended by adding the resampled data of the other 8 subjects making a total of 21984 samples.

The DL model was tested with various validation methods (70-15-15 HoV & 5/10-fold stratified CV) resulting an accuracy of 74.64% on the smaller dataset, along with a A-phase sensitivity of 83.4%. The same model resulted an accuracy of 68.07% on the extended dataset.

PS: Check out our research paper draft if you wish to learn more about the CAP theory or about the details of my neural network architecture and it's performance metrics :)
