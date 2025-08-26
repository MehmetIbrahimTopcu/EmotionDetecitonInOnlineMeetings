Emotion Detection in Online Meetings

This project aims to detect and classify participants' emotions in online meetings by analyzing facial expressions. The model is trained on a dataset downloaded from Kaggle and can perform predictions on real-time screen captures.

📂 Contents

deep_learning_model.ipynb → Use this notebook to train or modify the model according to your needs.

main.ipynb → This notebook uses the trained model to perform real-time emotion prediction, particularly from screen captures during online meetings.

📝 Usage
Training the Model

Open deep_learning_model.ipynb.

Adjust model parameters if needed.

Run the notebook to train or fine-tune the model.

Real-Time Prediction

Open main.ipynb.

Run the notebook to start capturing screen images and performing emotion predictions on faces detected in online meetings.

📊 Project Details

The system detects faces from screen captures, extracts them, and predicts emotions using a trained deep learning model.

The workflow can be run locally on your computer or adapted for different meeting platforms.

The two-notebook structure allows flexible experimentation with the model while keeping the prediction pipeline simple and ready-to-use.
