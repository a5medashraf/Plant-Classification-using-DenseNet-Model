# Plant-Classification-using-DenseNet-Model
 
## Introduction
A Binary Classification of Plants Images

<img src="https://github.com/a5medashraf/Plant-Classification-using-DenseNet-Model/assets/72763763/90a1c928-ed6e-4fb7-aef8-e51f5a6ebd09" width="250" height="750">

The [Data and NoteBook](https://www.kaggle.com/code/a5medashraf/plant-classification-using-densenet-model)

## Methodology

1. **Data Loading and Splitting:**
   The dataset is split into training and validation subsets.

2. **Data Visualization and Analysis:**
   The class distribution in the training dataset is analyzed using a pie chart.

3. **Balancing Classes:**
   The dataset is balanced by ensuring equal representation of each class.

4. **Model Architecture:** 
A pre-trained DenseNet-121 model is adapted by replacing the classifier with a custom fully connected layer.
The final layer uses a sigmoid activation function.

5. **Main Training Loop:**
The model is trained using:

- Batch_Size = 16
* epochs = 30
+ optimizer = Stochastic Gradient Descent (learning rate=0.001 , momentum=0.9)


7. **Model Evaluation:**
The best model state is saved based on its performance on the validation set.
Early stopping is implemented based on patience = 6.

