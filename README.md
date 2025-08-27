## 🎭 Emotion Detection in Online Meetings

Emotion Detection in Online Meetings is a project designed to detect and classify participants’ emotions by analyzing facial expressions in online meetings. The model is trained on a Kaggle dataset and can perform real-time predictions on screen captures.

This README is structured in a Quill-style format for clarity and detailed guidance.

## 🛠 Technologies Used




- Python: Primary programming language.
- OpenCV: For face detection and image processing.
- PyTorch: Deep learning framework for training and prediction.
- NumPy & Pandas: Data manipulation.
- Matplotlib/Seaborn: Visualizations.
- Tkinter (optional): GUI interactions for screenshots.
 
## 📝 Usage

    Training the Model

- Open deep_learning_model.ipynb
- Adjust model parameters if necessary
- Run all cells to train or fine-tune the model
#

    Real-Time Prediction

Predict emotions in real-time
- Open main.ipynb
- Run the notebook to:
- Capture screen images
- Detect faces




## 📊 Project Details

-Detects faces from live screen captures

-Classifies emotions using a trained deep learning model

-Works locally or can be adapted for different meeting platforms

-Two-notebook structure allows flexible experimentation and ready-to-use pipeline



## 🚧 Challenges & Future Improvements

-One of the main challenges in this project was related to face size in online meetings.

-The dataset was trained on images resized to 224x224, suitable for transfer learning with models like EfficientNet and MobileNet.

-However, in real online meetings, as the number of participants increases, individual faces become smaller on the screen.

-This reduction in face size negatively impacts the accuracy of emotion detection, since the model struggles to extract meaningful features from low-resolution faces.

## Dataset 

https://www.kaggle.com/datasets/sudarshanvaidya/corrective-reannotation-of-fer-ck-kdef
