# CAP-Classification-CRNN
A deep learning model based on Inception modules paired with gated recurrent units (GRU) for the classification of CAP phases (A & B). 

Database source: [Physionet.org](https://physionet.org/content/capslpdb/1.0.0/#:~:text=The%20CAP%20Sleep%20Database%20is,Ospedale%20Maggiore%20of%20Parma%2C%20Italy.&text=The%2016%20healthy%20subjects%20included,affecting%20the%20central%20nervous%20system.)

The model is tested with various validation methods (HoV & k-fold stratified CV) resulting an accuracy of 74.64% on a balanced dataset consisting of data of 6 subjects (total 9306 EEG samples), further tested on a dataset extended to 14 subjects (21984 EEG samples) achieving an accuracy of 68.07%.