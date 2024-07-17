# Image_Classification_Project
This project involves creating a convolutional neural network (CNN) to classify images of fruits and vegetables into various categories using TensorFlow and Keras. The model is trained, validated, and tested on datasets of images of fruits and vegetables and is capable of classifying new images with a high degree of accuracy.

## Project Structure
- **Fruits_Vegetables/**
  - **Fruits_Vegetables/**
    - **train/**: Contains training images categorized into folders
    - **test/**: Contains test images categorized into folders
    - **validation/**: Contains validation images categorized into folders
  - **apple.jpg**: Sample image used for prediction
  - **banana.jpg**: Sample image used for prediction
  - **cauliflower.jpg**: Sample image used for prediction
  - **onion.jpg**: Sample image used for prediction
  - **turnip.jpg**: Sample image used for prediction
  - **watermelon.jpg**: Sample image used for prediction
  - **Image_classify.keras**: Saved model file

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Pandas
- Matplotlib

Install the required packages using:

```bash
pip install tensorflow numpy pandas matplotlib
```

## Predicting with Your Own Images

You can use any image for prediction. Follow these steps:

1. Save your image in the project directory, similar to how `banana.jpg` is saved.
2. Adjust the file path in the prediction code to point to your saved image.
3. Run the prediction code to classify your image using the trained model.

