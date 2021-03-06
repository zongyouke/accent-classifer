# accent-classifer
A CNN classifier for Chinese accents, developed by Zong-You Ke, Dahn Cho and Chenyu Li.
Final Project for "Neural Network for Speech Recognition" course at Universit√© Sorbonne Nouvelle.

Project objective: Classify and predict speakers from Beijing, Canton and Taipei through CNN model training with audio recordings.

Raw data: Audio recordings from Chinese and Taiwanese speakers on Mozilla Common Voice

Tools: SPPAS, Praat, Keras 

Instructions:
1. Please download raw datasets from the links given in the data folder. These are zipped audio files. 
   - "spectro" series: classic spectrogram image files of speakers in Beijing, Canton and Taipei.
   - "MFCC" series: Praat-generated MFCC images from the spectrogram dataset.
   - "pitch" series: Praat-generated pitch curves generated from the spectrogram dataset.
   - "formant" series: Praat-generated formant curves generated from the spectrogram dataset.

2. Make sure that you create a shortcut to the file folders in your own Google drive, so that the code can retrieve all the data correctly. 
