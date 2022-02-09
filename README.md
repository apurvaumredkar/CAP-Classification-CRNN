# CAP-Classification-CRNN
A deep learning model based on Inception modules paired with gated recurrent units (GRU) for the classification of CAP phases (A/B). 

Database source: https://physionet.org/content/capslpdb/1.0.0/

The model is tested with various validation methods (70-15-15 HoV & 5/10-fold stratified CV) resulting an accuracy of 74.64% on a balanced dataset consisting of data of 6 subjects (total 9306 EEG samples), further tested on a dataset extended to 14 subjects (21984 EEG samples) achieving an accuracy of 68.07%.
