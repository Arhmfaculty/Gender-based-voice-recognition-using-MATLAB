# Gender-based-voice-recognition-using-MATLAB
This project employs MATLAB as the principal tool for the processing and analysis of the data. 
MATLAB’s Fast Fourier transform, Butterworth function, as well its graphical user interface 
(GUI), makes it a more than suitable platform for analysing, testing, as well as simulating the 
outcome of the project. 

OBJECTIVES
1. Voice Gender Classification: The primary goal is to accurately classify audio samples as 
either male or female based on their acoustic features. 
Faculty of Engineering and Computer Science 
Department of Electrical and Electronics Engineering, Ashesi University 
Berekuso, Accra, Ghana 
2 . Accuracy Evaluation: Assess the accuracy and performance of the gender recognition 
system through testing and validation using a dataset with known gender labels. 
3. Optimization Evaluation: To compare and evaluate the accuracy and performance of the 
system to that of an in-built MATLAB function as a measure of optimization.

** Description of Project: **
This project is an automatic gender classification system based on a person’s voice using the 
fast Fourier transform (FFT). The project uses two main methods for classification. The first 
method is the built-in pitch function which extracts the fundamental frequency of an audio 
signal and directly compares it to a predetermined frequency to determine gender. This 
threshold frequency is 165Hz, below which is a male voice, and above which is a female. The 
user-defined function employs a user-defined Butterworth filter function to generate the 
relevant frequency components in the audio signal, analyzes the fundamental frequency, and 
classifies the voice as male or female based on a predefined threshold. The system is divided 
into a front-end and a back-end system, with the front-end responsible for feature extraction, 
including the use of the Fast Fourier Transform (FFT) algorithm to analyse the power spectrum 
and extract the required frequencies. Meanwhile, the back end, acting as the classifier, creates 
a gender model based on these extracted frequencies and compares them to known values for 
gender identification. 
