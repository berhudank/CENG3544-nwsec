# CENG3544 - Final

## About the project
A machine learning classification model for encrypted traffic analysis is implemented and tested. The model is trained with a dataset that is composed of encrypted malicious and legitimate traffic. The model is trained with only session-based data.

You need to get the dataset from https://data.mendeley.com/datasets/xw7r4tt54g/1 to modify the model

1. Install Python 3, pandas, numpy, matplotlib, seaborn, scikit-learn, and tensorflow.
2. Open model.ipynb in an IDE such as Visual Studio Code. Install required extensions.
3. Run the code step by step.

If you want to only test the model, use these lines to load the model:

    from tensorflow.keras.models import load_model

    loaded_model = load_model("model.keras")
