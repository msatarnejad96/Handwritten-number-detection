# Handwritten-number-detection
An OCR project to decet persian hand written number trained on HODA dataset.
In the first phase the data is processed to change images to binary dataset. 
Afterwards features for each entry is extracted by histogram of  Local Binary Pattern.
Several Machine Learning algorithms have been applied and compared in the code such as Support Vector Machine(RBF and LInear kernels) and Desition Tree.
Hyper parameters like c in SVM are regulate by cross validation.
SVM approach with RBF kernel results in 98% accuracy which is the best among all.
