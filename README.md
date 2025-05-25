
# WaterBottleNNClassifiers

In this project, we aimed to build three different types of neural network classifiers that reach a high accuracy level. The types of classifier architectures consist of:

- Only dense layers.
- Convolutional and dense layers.
- Pre-trained neural network.

The first step that we had to go through was building a dataset of our own to classify the images inside. The dataset contains different photos of water brands in three categories:

1)  Qafshtama
2)  Lajthiza
3)  Tepelena

Our dataset consists of a total number of 324 photos. Each water bottle brand consists of three different water bottle sizes varying from 0.5 l, 1.5 l, and 2 l.
After the dataset was done, we were ready to build our three classifiers. The environment where we built our classifiers was Jupyter Notebook, powered by Anaconda.

# Environment and Development 

The environment where we built our classifiers was Jupyter Notebook, powered by Anaconda 24.1.2 running with Python version 3.11.7.

The modules used were:

- TensorFlow 2.16.1
- Keras 3.3.3
- NumPy 1.26.4
- CV2 4.10.0
- Pickle 4.0
- Matplotlib 3.8.0

# Documentation

In this repository, you will find three Jupyter notebooks containing my Data Science project. Each notebook includes comment lines that explain the purpose and details of the code implementation.

Additionally, a comprehensive project report in Word document format is provided below. This report documents the entire development process of the Data Science project, detailing its inception, methodology, and outcomes.

📄 [Download Data Science Report](documentation/dataScienceReport.docx)

# Models Performance

- Only Dense Layers Model

The first diagrams are from the only dense layers. It is clearly shown that the accuracy of the training data is way higher than the accuracy of the validation data. This is the reason why the accuracy of this model, unfortunately, was a bit lower than the expected accuracy.

In the second diagram, which is about the training and validation loss, if the training loss decreases while the validation loss plateaus or decreases at a slower rate, it suggests the model may be overfitting. The two different lines below in the second graph at some of its parts show exactly this, which can be later translated into an increase in the overfitting and a decrease in the total accuracy of the model.

![Only Dense Layers Model Diagrams ](https://github.com/rigelHadushiDev/WaterBottleNNClassifiers/raw/main/documentation/onlyDenseLayerModelDiagram.png)

- Convolutional and Dense Layers Model

The third and fourth diagrams depict the performance of models combining convolutional and dense layers, showcasing significant improvements and achieving expected results without overfitting concerns. Both training and validation accuracies demonstrate peak performance, indicating robust generalization across datasets. In the accompanying graph, while the training loss steadily decreases, the validation loss exhibits a slower decline, suggesting a modest disparity in performance between seen and unseen data. However, this gap does not undermine the overall accuracy of the model. By leveraging convolutional layers, the model effectively extracts spatial features crucial for tasks like image recognition, thereby mitigating overfitting and ensuring consistent high performance across diverse datasets.

![Convolutional and Dense Layers Model Diagrams](https://github.com/rigelHadushiDev/WaterBottleNNClassifiers/raw/main/documentation/Conv%26DenseModelDiagram.png)

- Pre-trained Neural Network Model

The last set of diagrams illustrates the performance of our final model, utilizing a pre-trained neural network. The first graph demonstrates the successful resolution of overfitting, showcasing high accuracies for both training and validation datasets. This achievement underscores the model's robustness in generalizing well to unseen data, culminating in a high overall accuracy that meets or exceeds expectations. In the second graph, the validation loss exhibits a decline rate comparable to that of the training loss, indicating effective training without significant overfitting. These observations collectively highlight the model's optimal performance, where the integration of a pre-trained neural network enhances feature extraction capabilities, mitigates overfitting risks, and ensures consistently high accuracy across diverse datasets.

![Pre-trained Neural Network Model Diagrams ](https://github.com/rigelHadushiDev/WaterBottleNNClassifiers/raw/main/documentation/Pre-trainedModelDiagram.png)

# Author

- [@rigelHadushiDev](https://www.github.com/rigelHadushiDev)
- [@KlajdiBajo](https://github.com/KlajdiBajo)


