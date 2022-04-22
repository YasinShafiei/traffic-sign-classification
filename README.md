# traffic sign classification 

## by Yasin Shafiei 

This is a project which will classify 43 classes of road signs . The project uses a CNN model to classify images.

### data:
  The project uses the GTSRB dataset which is available in https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign . The dataset has 43 classes .
  This is the plot for train and validation data split: 
  
  ![train_val_data](https://user-images.githubusercontent.com/91404054/164709443-bb608851-7da0-4d8b-9e05-255a1da12e89.png)

### model:
  The CNN model architected in this project is created using `pytorch` library. The model has 5 convolution layers, 3 max pool layers and 2 hidden layers.
  
### model Training:
  This CNN model trained on 22 epochs. The accuracy and loss is pretty good. You can see the training final accuracy and loss as follow:
  
```
Epoch-21: 
-----------------------------------------------------------------------------------------------------------------------
Training loss : 0.007853914980257944 |======| Training  accuracy : 0.9975546239837398
validation loss : 0.01502371459097166 |======| validation accuracy : 0.9957635787225538
-----------------------------------------------------------------------------------------------------------------------
```
  
  
  ![accuracy-loss](https://user-images.githubusercontent.com/91404054/164709831-546c0970-b860-4d53-8ea5-cea58a972f9e.png)
