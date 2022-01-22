# genetic_music_CNN
MAIN IDEA:
Genetic algorithms for evolving the architecture of a deep convolutional neural network to address music genre classification

PREPROCESSING
(4__music_preprocessing.ipynb)
from the audio file to the MFCCs images (or to the spectrogram if selected). It saves the preprocessed images in a json file

PROGRAM
(8__GA_classif_tuner_segment)
il performs the genetic algorithm itself. At the beginning the GA try to find the best hyperparameters for the CNN, than it applies the best one to the classification task



