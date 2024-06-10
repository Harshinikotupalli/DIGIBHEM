# CIFAR-10 Image Classification with Cifar-10 Dataset

This project aims to demonstrate image classification using the CIFAR-10 dataset with TensorFlow, an open-source machine learning framework. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The goal is to correctly classify these images into their respective categories.

![Screenshot 2024-06-10 160917](https://github.com/Harshinikotupalli/DIGIBHEM/assets/172130740/3278a8d3-e040-4e99-ae0e-895ef6adb056)



## Model Architecture

The model architecture used for this project is a convolutional neural network (CNN). CNNs are well-suited for image classification tasks due to their ability to automatically learn features from the input images.

## Dataset

The CIFAR-10 dataset is used for training and testing the model. It consists of the following classes:

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Harshinikotupalli/DIGIBHEM
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Train the model:

   ```bash
   python train.py
   ```

4. Test the model on a single image:

   ```bash
   python test_single_image.py --image_path /path/to/your/image.jpg
   ```

5. Generate the confusion matrix:

   ```bash
   python confusion_matrix.py
   ```

## Results

After training the model, it achieved an accuracy of X% on the test set. Testing on a single image yielded the following prediction: [Predicted Class]. The confusion matrix provides insights into the model's performance across different classes.

## Future Work

- Experiment with different CNN architectures to improve accuracy.
- Augment the dataset to increase variability and robustness.
- Deploy the model for inference in real-world applications.

## Credits

This project is inspired by the CIFAR-10 classification tutorial in the TensorFlow documentation.

