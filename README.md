# Jaundiceprediction Using Resnet 50

The Model is Trained with Resnet-50 pretrained weights where some layers have been masked and some have been tuned During the training levels.

Pipeline:
1. Data Loading
2. Preprocessing (to determine the sharp edges in the images)
3. Building the Model with Pretrained Resnet weights
4. Training the Model with Pytorch
5. Model Evaluation
6. Deploying the model with onnx environment

