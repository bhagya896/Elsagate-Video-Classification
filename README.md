## Elsagate Content Classification in Cartoon Videos

This repository contains the code for the implementation of the paper Elsagate Content Classification in Cartoon Videos.

### Dataset
The dataset was downloaded from various websites which has a collection of cartoon videos. These videos were downloaded from youtube as well. Annotation files of all these videos were created which has classified every second of the video into four different categories namely Sexual, Violent, Both and None.

### Experiment Setup
- Downlaod the dataset and create the Annotation file of every video
- Use the notebook Dataset to extract the frames from the videos
- then use the notebook model to extract the VGG-19 feature from the extracted frames. Also this notebook contain code where the generated Annotation files would be used.
- Use the notebook Train so as the training of the model Bi-LSTM and Autoencoder can be done
- Visualize contain code for the final evaluation of the results
