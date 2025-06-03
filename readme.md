# Brain Cancer Detection with CNN

## Overview
This project implements a Convolutional Neural Network (CNN) for brain cancer detection using medical imaging data.

## Requirements
```bash
pip install tensorflow keras numpy pandas matplotlib opencv-python scikit-learn
```

## Dataset
- Medical brain imaging dataset
- Images should be organized in train/test folders
- Supported formats: PNG, JPG, JPEG

## Model Architecture
- CNN with multiple convolutional layers
- Pooling layers for feature extraction
- Dense layers for classification
- Dropout for regularization

## Usage
1. Prepare your dataset in the correct folder structure
2. Run the Jupyter notebook
3. Train the model with your data
4. Evaluate performance metrics
5. Make predictions on new images

## Results
- Training accuracy
- Validation accuracy
- Confusion matrix
- Classification report

## Files
- `brain_cancer_cnn.ipynb` - Main notebook with model implementation
- `data/` - Dataset directory
- `models/` - Saved model files

## License
MIT License