# Traffic Signs Classification

This project implements traffic sign recognition using multiple deep learning models built with TensorFlow and Keras. It includes a simple convolutional model, a variant with sigmoid activation, and a transfer learning model using VGG16.

## Project Structure
- `psi.ipynb` : Jupyter Notebook that contains data loading, preprocessing, model definitions, training, evaluation, and visualization.
- Data is loaded from `/mnt/d/datasets/traffic-signs`, with labels provided in `/mnt/d/datasets/traffic-signs/Test2.csv`.

## Models
- **Simple Model:** Basic CNN with ReLU and softmax layers.
- **Optimized Model:** Contains additional modifications for better performance.
- **VGG16 Model:** Uses a pretrained VGG16 network as base, followed by custom dense layers.

## Requirements
- Python 3
- pip
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Pillow
