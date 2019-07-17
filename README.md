# Street View House Numbers (SVHN)  

These notebooks use Convolutional Neural Networks to learn digit classifications from Google's Street View House Numbers dataset.  The 'parse_data.ipynb' notebook is used to extract data from the dataset matlab files, and convert them to Numpy arrays. The classification notebooks perform preprocessing on the arrays, and use Keras to define the hyperparameters of the model. The single digit classifier was able to correctly identify 89.695% of single digit testing data. The multi digit classifier was able to identify 90.207% of multi digit testing data.  

## Dataset  
Kaggle: https://www.kaggle.com/stanfordu/street-view-house-numbers/version/2  

## Multi Digit Samples  
![alt text](https://raw.githubusercontent.com/danielhallinan88/street-view-house-numbers/master/sample_predictions.png)  
