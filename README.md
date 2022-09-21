# project-code-birdsong-recognition[Read Me]

# Author Shaela Khan, 2022, Summer 

This project explores and implements a bird detection system based on bird-songs, using machine learning algorithms.

Datasets:
train:
./small-Xeno Canto
./img_data
./img_data2

test:
./datasets.
voices --> only for testing purposes , in increments not part of the original bird-songs.But instead holds songs , sounds from the outer space , human voices for research and devemopment purposes only.

Audio data conversion to spectrograms:
birdsong visualizations.ipynb
audio-conversion.ipynb

Do Not run - as these will overwrite the resulting images created that are used for training the models. Can be run separate , if a separate folder for datasets and just this notebook is saved. 

Helper functions:
helper-functions.ipynb

Models:
./models-
- resnet50 saved weights.

Initial phase : Architecture testing. different formations of layers, hidden layers. 

song_recognizer.ipynb
song_recognizer2.ipynb

Implementation and testing phase:
birdy.ipynb
birdy2.ipynb
birdy3.ipynb


- Testing increments hyperparameter tuning, different optimizers, changing learning rates, changing regularizers to improve and train the model and increase efficiency.

To Run - 
Please follow folder hierarchy- folder paths are absolute for debugging purposes and have been hard-coded. 
Make sure to use Python 3.7 
Tensorflow 2.2 as backend.
And make space of approax 8 GB on harddrive.
