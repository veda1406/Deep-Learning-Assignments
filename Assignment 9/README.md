# Assignment 9: Pre-trained Vision Transformer (ViT) vs CNN on CIFAR-10

## Objective
Perform image classification with a pre-trained Vision Transformer (ViT) and compare its performance with a Convolutional Neural Network (CNN).

## Dataset
CIFAR-10 contains 60,000 colour images of size 32 × 32 pixels across 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. The notebook uses a selected subset for a practical demonstration; check the data-loading cell for the exact sample counts.

## Models
### Vision Transformer (ViT)
- Load a pre-trained ViT and its image processor.
- Preprocess images to the model's expected input format.
- Adapt the classification head to output 10 classes.
- Freeze the pre-trained feature-extraction backbone and train the classification head, as configured in the notebook.

### Convolutional Neural Network (CNN)
- Resize and normalize images.
- Use convolutional and pooling layers to learn image features.
- Use dense output layers to predict one of the 10 classes.
- Train the CNN from scratch on the selected training subset.

## Workflow
1. Import TensorFlow, PyTorch, Transformers, and Scikit-learn libraries.
2. Load CIFAR-10 and identify class names.
3. Select training and test samples.
4. Load the pre-trained ViT processor and model.
5. Adapt and train the ViT classification head.
6. Evaluate ViT on held-out test images.
7. Prepare the images for CNN input.
8. Build, compile, and train the CNN.
9. Evaluate CNN on the same test samples.
10. Calculate accuracy, precision, recall, and F1-score for both models.
11. Display classification reports and compare results in a table and accuracy chart.

## Main Technologies
- Python
- TensorFlow / Keras
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Matplotlib
- CIFAR-10

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Classification reports and a comparative accuracy visualization

## Running the Notebook
1. Open the notebook in Google Colab.
2. Enable a GPU runtime if available, especially for ViT.
3. Install the required packages.
4. Run data loading and preprocessing cells.
5. Train and evaluate ViT.
6. Train and evaluate the CNN.
7. Review the comparison table, reports, and chart.

## Interpretation and Limitations
ViT uses pre-trained image features while the CNN is trained from scratch. This is a practical comparison of the implemented pipelines, not a perfectly controlled comparison of architectures under identical pre-training conditions. A subset-based experiment may produce different results from a full CIFAR-10 run. Report the actual metrics produced by the notebook.
