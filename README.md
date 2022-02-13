# Wildfire predictions 🔥🌳🛰️🪄

[![Open in SageMaker Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/javichur/wildfires/blob/main/wildfire-predictions.ipynb)

## Predict future wildfires. This novel tool finds past wildfires, crops pre-fire satellite images, and then creates an image dataset of locations that will be burned after the image is taken.

## This dataset is then used to train a neural network. This neural network will try to classify satellite images between "potential future fire location" and "no future fire location".

## The objective is to be ready for the response to disasters, thanks to the fact that the most potentially fire-prone places will be known in advance.

![upload file and predict](./assets/upload-file-and-predict.png)

![Interactive map](./assets/interactive-map-in-jupyter.png)

![Fullscreen map](./assets/map-fullscreen+popup+burnedzone-red.png)

![Generating dataset with crops pre-fire places automatically](./assets/generating-dataset-before-fires.png)

![before fire vs before no fire](./assets/fire-vs-nofire-gray.png)

![You can predict from Latitude/Longitude clicking on map](./assets/predict-from-lat-lon-for-now.png)