
# WaterBottleNNClassifiers

The aim of this project was to build three different types of neural network classifiers, which will help classify the most popular water bottle brands in Albania. The classifiers models I focused consist of:

-	Only Dense layers.
-	Convolutional and Dense layers.
-	Pre-trained neural network.

These models were trained by the custom dataset that I made , which consist of three diferent sizes as 0.5l, 1.5l and 2l of a total number of 324 photos and three different categories called: 

-	Qafshtama
-	Lajthiza
-	Tepelena

## Environment and Development 

The environment where we built our classifiers was Jupyter Notebook powered by Anaconda 24.1.2  running with python version 3.11.7 . 

Modules used were:

- TensorFlow 2.16.1
- Keras 3.3.3
- NumPy 1.26.4
- CV2 4.10.0
- Pickle 4.0
- Matplotlib 3.8.0

## Documentation

In this repository, you will find three Jupyter notebooks containing my Data Science project. Each notebook includes comment lines that explain the purpose and details of the code implementation.

Additionally, a comprehensive project report in Word document format is provided. This report documents the entire development process of the Data Science project, detailing its inception, methodology, and outcomes.


## Models Performance

- Convolutional and Dense Layers Model

The first two diagrams are about the convolutional and dense layers. Here the validation accuracy has reached a value of 99.15% , reaching the expected results. Overfitting has been prevented and the model works perfectly. Both accuracies of the training and validation have reached peak performance. For the second graph we can see that the validation loss is dropping slower than the training loss but the overfitting is not that high that can prevent the accuracy of the whole model.

![Convolutional and Dense Layers Model Diagrams](https://github.com/rigelHadushiDev/WaterBottleNNClassifiers/raw/main/documentation/Conv%26DenseModelDiagram.png)


- Only Dense Layers Model

The diagrams showed below are from the only dense layers model. It is clearly shown that the accuracy of the training data is way higher that the accuracy of the validation data. This is the reason why the accuracy of this model unfortunately was a bit lower than the expected accuracy. 

In the second diagram  which is about the training and validation loss, if the training loss decreases while the validation loss plateaus or decreases at a slower rate, it suggests the model may be overfitting. The two different lines below at the second graph at some of its part show exactly this, which can be later translated into an increase of the overfitting and a decrease on the total accuracy of the model.

![Only Dense Layers Model Diagrams ](https://github.com/rigelHadushiDev/WaterBottleNNClassifiers/raw/main/documentation/onlyDenseLayerModelDiagram.png)

- Pre-trained Neural Network Model

The last two diagrams I  have are for the final model which is the pre-trained neural network. The first graph shows that the overfitting problem has been resolved perfectly and both accuracies of the training data and validation data are really high. In the end the accuracy of the model is really high and also has reached the expected result. About the second graph we can see that the validation loss has completely dropped with a speed almost the same as the training loss. So both of the graphs show us a good example that the overfitting issue has been resolved perfectly and the model has reached peak accuracy once again.

![Pre-trained Neural Network Model Diagrams ](https://github.com/rigelHadushiDev/WaterBottleNNClassifiers/raw/main/documentation/Pre-trainedModelDiagram.png)

## Author

- [@rigelHadushiDev](https://www.github.com/rigelHadushiDev)

