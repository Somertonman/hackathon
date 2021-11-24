# Age group detection regardless of face mask during pandemic using Tensorflow/ResNet

## Team members:
* Anastasiya Spirova
* Aleksandr Krainov
* Veselina Zatsepina
* Nikita Tsintsov
* Konstantin Kozhemyakov

## Dataset

### Description

The dataset represents huge number of images of people wearing face masks or not to be used extensively for train/test splitting. Selected files were double-checked to avoid data collection bias using common sense.

### Sources

The dataset obtained and combined from various open data sources, including following:
* https://www.kaggle.com/frabbisw/facial-age
* https://www.kaggle.com/nipunarora8/age-gender-and-ethnicity-face-data-csv
* https://www.kaggle.com/arashnic/faces-age-detection-dataset
* https://www.kaggle.com/andrewmvd/face-mask-detection
* manually obtained under-represented observations using Google search engine

### Structure

The dataset curated and structured into three age groups (under 18, 18-65 and 65+) without initial test/train selection, which is achieved programmatically to allow manipulations with original data.

## Model 

### References

*   Activation

https://towardsdatascience.com/7-popular-activation-functions-you-should-know-in-deep-learning-and-how-to-use-them-with-keras-and-27b4d838dfe6

* Loss

https://neptune.ai/blog/keras-loss-functions

* Epochs

https://towardsdatascience.com/epoch-vs-iterations-vs-batch-size-4dfb9c7ce9c9

* Optimization

https://towardsdatascience.com/neural-network-optimization-7ca72d4db3e0

https://machinelearningmastery.com/recommendations-for-deep-learning-neural-network-practitioners/
