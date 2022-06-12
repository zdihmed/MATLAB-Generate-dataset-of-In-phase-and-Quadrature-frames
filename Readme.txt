Run the following file 'GeneratingDatasetOfFrames.m' in MATLAB to generate dataset of frames composed of in-phase and 
Quadrature commponent of the signal. This code generates frames of the following modulation types:

modulationTypes = categorical(["BPSK", "QPSK", "8PSK", ...
  "16QAM", "64QAM", "PAM4", "CPFSK"]);
  
 Update this above list to personalize your data generation, for example:  modulationTypes = categorical(["BPSK", "QPSK", "8PSK", "16QAM"]);
 
 

A part of this code is imported from https://www.mathworks.com/help/deeplearning/ug/modulation-classification-with-deep-learning.html

