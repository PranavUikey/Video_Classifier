# Classifying 10 Types of Activity in Video

Following are the types of sports over which we are trying to classifying:

* Badminton
* Baseball
* Basketball
* Boxing
* Chess
* Cricket
* Fencing
* Formula 1
* Gymnastics
* Hockey
* Ice Hockey




![Github_video_classifer](https://user-images.githubusercontent.com/42734141/62006868-3c6af800-b164-11e9-8177-99ebe23f514c.png)




## Data Distribution

Data has been downloaded with the help of <https://github.com/PranavUikey/Bulk-Image-Downloader>

Training set: 3099

Validation set: 1033


## Model
Resnet 50

## Data Augmentations

ImageDataGenerator(Keras built-in)<https://www.pyimagesearch.com/2019/07/08/keras-imagedatagenerator-and-data-augmentation/>
we can obtain augmented data from the original images by applying simple geometric transforms, such as random:

1) Translations
2) Rotations
3) Changes in scale
4) Shearing
5) Horizontal (and in some cases, vertical) flips
## Accuracy
![Github_video_classifer1](https://user-images.githubusercontent.com/42734141/62007272-2dd30f80-b169-11e9-9dc3-3a273b9c0830.png)

## Reference 
<https://www.pyimagesearch.com/2019/07/15/video-classification-with-keras-and-deep-learning/>
<https://www.pyimagesearch.com/2019/07/08/keras-imagedatagenerator-and-data-augmentation/>
<https://colab.research.google.com>
