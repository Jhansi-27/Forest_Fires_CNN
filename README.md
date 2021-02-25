# Classification of forest pile burn images into "fire vs nofire" using Convolution Neural Networks

### Dataset
* The dataset is downloaded from IEEE dataport and you can download datasets from [here](https://essexuniversity-my.sharepoint.com/:f:/g/personal/hr17576_essex_ac_uk/EplQh6rwA8pJhHP0jKfg6-kBVHyb1BE9TCAj4MVR0tyOEA?e=Uo6PLD).
* Training/Validation dataset: This dataset has 39,375 frames that are resized to 254x254 and the image format is JPG. This data is in a directory called training, which contains 2 sub-directories, one per class.
* Test dataset : Test datset has 8,617 frames that are labeled.This data is in a directory called test, which contains 2 sub-directories, one per class.

* This table shows the directory structure of training data:
```bash
/Training
        ├── Fire/*.jpg
        ├── No_Fire/*.jpg
```
* The test direcotry looks like this:
```bash
/Test
    ├── Fire/*.jpg
    ├── No_Fire/*.jpg
```

### Model
* The binary fire classifcation model of this project is based on the simple CNN Network:
* The CNN model has 3 convolutional layers followed by a max-pooling layers.
* A dropout layer is added after 3rd maxpool operation to avoid overfitting.

![BaseModel:Simple CNN](https://github.com/Jhansi-27/Forest_Fires_CNN/blob/main/Baseline_new.png?raw=true). 

## Requirements
* os
* cv2
* numpy
* Keras 
* Tensorflow
* scikitlearn
* matplotlib.pyplot
* Seaborn
* pathlib
* PIL

## Code
This code is run and tested on Python 3.6 on Windows 10  machine with no issues.
Download the [Forest_fires.ipynb](https://github.com/Jhansi-27/Forest_Fires_CNN/blob/main/ForestFires.ipynb) file.
This is the main IPython Notebook, run it using Jupyter notebook in your local system or it can be run using [Google Collab](https://colab.research.google.com).

## Results
* The following are the classification accuracy and Confusion Matrix of the baseline model:
### Accuracy
![Accuracy](https://github.com/Jhansi-27/Forest_Fires_CNN/blob/main/accuracy.PNG?raw=true)
### Confusion marix
![Confusion matrix](https://github.com/Jhansi-27/Forest_Fires_CNN/blob/main/cm.PNG?raw=true)


