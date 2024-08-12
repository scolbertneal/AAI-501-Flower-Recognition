# AAI-501-Flower-Recognition
The dataset we chose contains images of 16 different flower species. The primary problem is to build a system that can accurately classify these images into their respective species. Our goal is to develop a powerful image classification system that can adapt well to unseen data. 

Link to dataset: https://www.kaggle.com/datasets/l3llff/flowers/data

Installations needed:
- TensorFlow: https://www.tensorflow.org/install
- Installation commands:
    # Requires the latest pip
        pip install --upgrade pip
  
    # Current stable release for CPU and GPU
        pip install tensorflow

Imports:
  import matplotlib.pyplot as plt
  import numpy as np
  import PIL
  import tensorflow as tf
  from tensorflow import keras
  from keras import layers
  from keras.models import Sequential
