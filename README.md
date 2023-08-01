# OpenCampus_Kaggle_Contrails_PreProcessing
In this repository we consolidate the results from the the data-preprocessing group which is part of the OpenCampus Kaggle-Contrails Competition.

Our main focus was to identify the most relevant or informative spectral bands. We further tried to reduce to total amount of availabale data (450GB) in the competion to speed-up the modeling and training process.

One main approach was the usage of the spectral index. A method inspired from physics to compare and weight the signal or intensity versus background taken from images. By following this route we were able to distiguish the most promissing bands in the dataset - which have shown a high degree of dissimilarity. Hopefully leading to a better prediction and identification of the contrails from the surrounding clouds, vapor and water fragments.

Bharat came up with the first EDA draft. Kristian prepared a dataloader module for the pre-processing and a simplified version for the a spectral encoding. Later Katya and Anton introduced their spectral method code. Bharat merged and consolidated these code-snippets being supported by Anton and Katya. We all worked and discussed about parts of the presentation. Kristian was arranging/preparing meetings and communication.
