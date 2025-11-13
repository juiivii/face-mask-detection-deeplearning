Face Mask Detection using Deep Learning
=======================================

This project implements a Convolutional Neural Network (CNN) to classify whether a person is wearing a mask or not. All steps — preprocessing, training, evaluation, and predictions — are done inside a Jupyter Notebook using TensorFlow/Keras.

----------------------------------------------------
FEATURES
----------------------------------------------------
- Binary classification: Mask vs No Mask
- CNN built with TensorFlow/Keras
- Image preprocessing + augmentation
- Training and validation accuracy/loss graphs
- Confusion matrix for evaluation
- Save trained model as .h5
- Easy-to-run Jupyter Notebook

----------------------------------------------------
PROJECT STRUCTURE
----------------------------------------------------
face-mask-detection-deeplearning/
│
├── Deeplearning-mask.ipynb      # Main notebook
├── dataset/                     # Optional (if small)
│   ├── with_mask/
│   └── without_mask/
├── models/                      # Trained models (optional)
│   └── mask_model.h5
├── results/                     # Plots and output images
│   └── training_curve.png
├── requirements.txt
└── README.txt

----------------------------------------------------
INSTALLATION
----------------------------------------------------
Install dependencies:

    pip install -r requirements.txt

Or install manually:

    pip install tensorflow numpy matplotlib opencv-python keras

----------------------------------------------------
HOW TO RUN
----------------------------------------------------
Open the notebook:

    jupyter notebook Deeplearning-mask.ipynb

Then run all cells to:
1. Load dataset
2. Preprocess images
3. Build & train CNN
4. Visualize accuracy/loss
5. Test on sample images
6. Save trained model

----------------------------------------------------
TRAINING RESULTS
----------------------------------------------------
The notebook includes plots for:
- Training accuracy
- Validation accuracy
- Training loss
- Validation loss

Save trained model:
  
    model.save("models/mask_model.h5")

----------------------------------------------------
FUTURE IMPROVEMENTS
----------------------------------------------------
- Real-time detection using OpenCV
- Add "Incorrect Mask" as third class
- Deploy model to mobile using TensorFlow Lite
- Use Transfer Learning (MobileNetV2, EfficientNet)
- Webcam-based detection

----------------------------------------------------
AUTHOR
----------------------------------------------------
Developed by: Jivesh Karthikeyan
