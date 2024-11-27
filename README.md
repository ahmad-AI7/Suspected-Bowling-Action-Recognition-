# Suspected-Bowling-Action-Recognition-
# Suspected Bowling Action Detection

This project aims to detect suspected bowling actions in cricket using a deep learning model.

## Project Description

This project uses a VGG16-based model trained on a dataset of images labeled as either "Legal" or "Illegal" bowling actions. The model is trained in Google Colab using TensorFlow and Keras.

## Dataset

The dataset used for this project is stored in Google Drive at the following path:

`/content/drive/MyDrive/Suspected labeled dataset`

The dataset is organized into two folders:

*   `ILLegal`: Contains images of suspected illegal bowling actions.
*   `Legal`: Contains images of legal bowling actions.

## Model

The model is a VGG16-based model with additional layers for classification. The model is trained using data augmentation techniques to improve generalization.

The trained model and metadata are saved in Google Drive at the following path: Contact : ahmadchaudhary8899@gmail.com

`/content/drive/MyDrive/Model`

## Usage

1.  Mount your Google Drive in Colab.
2.  Load the trained model using `tf.keras.models.load_model()`.
3.  Preprocess the input image using `preprocess_image()` function.
4.  Make predictions using `predict_image()` function.

## Requirements

*   Python 3.x
*   TensorFlow 2.x
*   Keras
*   Pillow
*   Google Colab (optional)

## Installation

1.  Install the required libraries using `pip`:

2.  2.  Mount your Google Drive in Colab (if using Colab).

## Training

1.  Prepare the dataset and store it in the specified path.
2.  Run the code in the "Model Code" section of the notebook to train the model.

## Testing

1.  Load the trained model and metadata.
2.  Run the code in the "Testing" section of the notebook to make predictions on a sample image.
