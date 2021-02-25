# Classification of forest pile burn images into "fire vs nofire" using Convolution Neural Networks

### Dataset
* The dataset is downloaded from IEEE dataport and you can download datasets from [here](https://essexuniversity-my.sharepoint.com/:f:/g/personal/hr17576_essex_ac_uk/EplQh6rwA8pJhHP0jKfg6-kBVHyb1BE9TCAj4MVR0tyOEA?e=Uo6PLD).

* This table shows the direcotry structure of training data:
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
![BaseModel:Simple CNN](https://github.com/Jhansi-27/Forest_Fires_CNN/blob/main/Baseline_new.png?raw=true). 

## Requirements
* os
* cv2
* numpy
* Keras 
* Tensorflow
* matplotlib.pyplot
* scikitlearn
* PIL

## Code
This code is run and tested on Python 3.6 on Windows 10  machine with no issues.
Download the [Forest_fires.ipynb](https://github.com/Jhansi-27/Forest_Fires_CNN/blob/main/ForestFires.ipynb) file and run it in Jupyter notebook.
This is the main IPython Notebook, download the file and run it using Jupyter notebook or Google Collab.

## Results
* Fire classification accuracy and  Confusion Matrix:
### Accuracy
![Accuracy](https://github.com/Jhansi-27/Forest_Fires_CNN/blob/main/accuracy.PNG?raw=true)
### Confusion marix
![Confusion matrix](https://github.com/Jhansi-27/Forest_Fires_CNN/blob/main/cm.PNG?raw=true)


