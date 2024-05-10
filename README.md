# Deep Audio Detection for Capuchin Bird Call

The aim of this project is to create a deep/machine learning model that can analyse an audio clip and detect and count the density/number of Capuchin bird calls heard in it. The data for this project is available in kaggle in the following link: https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing?resource=download

This kaggle dataset was part of an Audio Recognition challenge that was posted by Hewlett Packard (HP).

The data contains the following:

101 Forest recordings\
218 Capuchin bird call short clips\
594 Non-Capuchin/other birds and animal call short clips

## Repository structure:
model > this folder contains the .ipynb file with the whole solution comprising of preprocessing, ML model, training and prediction. (Google Colab notebook)\
results > this folder contains a .csv file with the resulting density/number of Capuchin bird calls in each forest recording.


The idea is to learn from the above data to be able to distinguish the Capuchin Bird call from other sounds. The next further step is to then count the number of times these Capuchin bird calls are heard in a given recording.

This is my first experience with audio detection using deep learning methods. 

## Future Prospect:
Future ideas for this project would be to get more Capuchin bird calls data to balance out the high number of non-Capuchin bird call data. This would help in ensuring a more robust ad realistic model. I also plan to create a platform where new forest recording clips can be uploaded and analysed by this model to give the detection results. This would be helpful for the general public and ornithology enthusiasts to know about the presence of Capuchin birds.

This project can further be advanced to detect a variety of different animal calls altogether. Thus, expanding the scope of detection and increasing the capacity of the model. This would involve many advancements in the model architecture and pipeline.

This type of project is extremely helpful for biologists and biodiversity experts in order detect the availability and number of certain species of fauna. Such projects can be very useful in trying to preserve and manage endangered birds and animals.
