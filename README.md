# Classification of forest pile burn images into "fire vs nofire" using Convolution Neural Networks

### Dataset
* The dataset is downloaded on IEEE dataport. 

* This table shows the direcotry architecture of training data:
```bash
/Training
                    ├── Fire/*.jpg
                    ├── No_Fire/*.jpg
```
* The testing The direcotry looks like this:
```bash
Repository/frames/Test
                    ├── Fire/*.jpg
                    ├── No_Fire/*.jpg
```


<!--- ![Alt text](/Output/table.PNG) --->
<img src=/Output/table.PNG width="860" height="600"/>


### Model
* The binary fire classifcation model of this project is based on the simple CNN Network:

![Alt text](/frames/small_Xception_model.PNG)
<br/>
<br/>

* The fire segmentation model of this project is based on the U-NET:

![Alt text](/frames/u-net-segmentation.PNG)

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
This code is run and tested on Python 3.6 on Windows 10  machine with no issues. Download the 'Forest_fires.ipynb' file and run it in Jupyter notebook.



## Results
* Fire classification accuracy:

![Alt text](/Output/classification.PNG)

* Fire classification Confusion Matrix:

<img src=/Output/confusion.PNG width="500" height="500"/>
<!--- ![Alt text](/Output/confusion.PNG) --->

