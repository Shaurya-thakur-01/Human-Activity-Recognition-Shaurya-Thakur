# Human Activity Recognition Using Smartphone Sensor Data

**Project by: SHAURYA THAKUR**

This project classifies six human activities from smartphone inertial sensor time-series data using an LSTM (Long Short-Term Memory) neural network.

## Activities
- Walking
- Walking Upstairs
- Walking Downstairs
- Sitting
- Standing
- Laying

## Tools
- Python
- TensorFlow / Keras
- NumPy and Pandas
- Matplotlib
- scikit-learn

## Dataset
UCI Human Activity Recognition Using Smartphones:
https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones

DOI: https://doi.org/10.24432/C54S4K

The notebook uses nine raw inertial signal channels with 128 time steps per sample.

## Run in Google Colab
1. Open `Human_Activity_Recognition_SHAURYA_THAKUR.ipynb` in Google Colab.
2. Run the cells from top to bottom.
3. Upload the official UCI HAR ZIP file when prompted.
4. Record the test accuracy printed by your run.

## Method
An LSTM neural network is trained on the official training split and evaluated on the official test split. The notebook produces training curves, a classification report, a confusion matrix, and an example prediction.

## Scope
This is an offline dataset-based demonstration. It does not collect live sensor readings from a phone.

## Attribution
Notebook prepared by **SHAURYA THAKUR**. Dataset authors and UCI are credited through the dataset reference above. Preserve any third-party code licenses and attribution if adapting external code.
