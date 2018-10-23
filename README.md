## EC601_project_2<br/>
Build model based on Keras with part of dataset cifar-10.

## DataSet<br/>
Download data from [CIFAR-10-python](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz) and run read_data_jupyter.ipynb in jupyter notebook to extract trainning data.(Just use Car and Truck images and labels to train the model)

## Model
Run classfication_net.ipynb cell by cell to train and test the model

## Result
Two models are tried.<br/>
Simple CNN with dropout has an acc at 94%<br/>
Larger model with Resnet Short Cut has an acc at 90.6%<br/>
The larger network performs worse than smaller one. I guess that's because the images in CIFAR are very small (32x32) and the large network encountered with overfitting.
