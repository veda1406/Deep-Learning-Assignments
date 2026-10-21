# Assignment 7: Image Classification Model Comparison on CIFAR-10

## Objective
Compare image-classification performance using AlexNet-style CNN, VGG16, ResNet50, and EfficientNetB0 on CIFAR-10.

## Dataset
**CIFAR-10**, loaded from `tf.keras.datasets.cifar10`. It contains 10 classes of small colour images: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

## Implementation
- Load and visualize CIFAR-10 images.
- Resize images to 96 × 96 for model input.
- Build a shared classification head for transfer-learning backbones.
- Load ImageNet-pretrained VGG16, ResNet50, and EfficientNetB0 with their original top layers excluded.
- Freeze each pretrained backbone and train a new classifier.
- Build and train an AlexNet-style CNN.
- Evaluate test accuracy and compare the models in a table and bar graph.
- Generate a classification report.

## Important note about AlexNet
Keras Applications provides pretrained VGG16, ResNet50, and EfficientNetB0 models, but does not provide an official pretrained AlexNet model. The AlexNet-style model in this notebook is trained from scratch, so it is not transfer learning in the same sense as the other three models. A separate pretrained AlexNet checkpoint would be needed if pretrained weights are required for all four models.

## Technologies
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Pandas
- Scikit-learn

## Run
Open `DL_A7.ipynb` in Google Colab or Jupyter Notebook. CIFAR-10 downloads automatically through Keras. GPU acceleration is recommended. The pretrained model weights for VGG16, ResNet50, and EfficientNetB0 may download on first use.

## Files
- `DL_A7.ipynb` — implementation notebook
- `Vedanti Raut_CSEAI_E_38_A7.pdf` — practical record / exported report
