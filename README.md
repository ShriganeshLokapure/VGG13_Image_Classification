# VGG-13 Implementation for Image Classification
The goal of this project is to implement the VGG-13 architecture for image classification on a dataset containing three classes: dogs, cars, and food.
### Implementation Details:

- Model Architecture: VGG-13 (Version B) is implemented using PyTorch. The architecture consists of 13 convolutional and 3 fully connected layers.
- Data Preprocessing: Images are resized to a fixed size and normalized to ensure consistency in input dimensions and scale.
- Training: The model is trained using the training dataset with the Adam optimizer and cross-entropy loss function.
- Evaluation: The model is evaluated on the validation dataset to monitor performance and prevent overfitting.
- Testing: Finally, the model is tested on the test dataset to assess its generalization and overall accuracy.
### Performance:

- Base Case: The initial performance of the model without any optimization techniques is evaluated.
- With Optimization Techniques: Regularization, dropout, early stopping, and image augmentation are applied to improve the model's performance.
- Metrics: Accuracy, loss, precision, recall, and F1 score are used to evaluate the model's performance.
## Code

You can find the code for the entire project in the VGG13_Image_Classification#.ipynb files.
## Detailed Report

A comprehensive report detailing the model architecture, training process, evaluation metrics, and performance graphs is available in `report.pdf`.

For questions or feedback, please [email](mailto:gayatriwalke@gmail.com).
