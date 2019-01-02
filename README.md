## PyTorch Exercises

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org)
- [PyTorch](http://pytorch.org)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

Recomend installing  [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Projects:

### 1. MNIST-Digits-Classifier:
- A machine learning model was created to predict label of hand-written digit.
- A number of epochs was choosen using "Model Validation" technique.
- Validation set was used to measure how well a model generalizes, during training.
- The model training was stopped when the validation loss stops decreasing (and especially when the validation loss starts increasing and the training loss is still decreasing).

### 2. Cat-Dog-Classifier  
- A machine learning model was trained on  a set of labeled images of  cats and dogs, was saved and used  to classify a new image as cats or dogs. The original data set can be downloaded [here](https://s3.amazonaws.com/content.udacity-data.com/nd089/Cat_Dog_data.zip).

- Google Colaboratory is used in order to be able to train model using GPU.
- pretrained model file "resnet50_1epoch.pth".
- fie for demonstration "Aza1.jpg"


