# CCTV Criminal Detection

## Dataset

The dataset used for this project has been created and annotated manually. It consists of images categorized into two classes:

1. **Criminal-1** - This class represents individuals identified as criminals.
2. **Good-Person** - This class represents individuals identified as non-criminals or good persons.


### Dataset Access
The dataset is hosted on Roboflow. You can access it using the following link:
[Roboflow Dataset](https://app.roboflow.com/m-pkysv/ibos-project/models)

## Model Training
For this task, I have used the YOLOv8 model, which is trained on the prepared dataset. The Colab link for training the model is the following:
https://colab.research.google.com/drive/1t3GZJYBu6oZDNmGu5iwTzUDbvs8L9Edk?usp=sharing


## Real-Time Detection
Real-time detection of faces is implemented using the best-trained YOLOv8 model and the OpenCV library. The system processes frames from a video file and performs detection on selected frames to optimize performance. Key highlights of the real-time detection system include:

- **Frame Extraction**: Frames are extracted at regular intervals to ensure efficient processing without compromising on detection accuracy.
- **YOLOv8 Integration**: The pre-trained YOLOv8 model is used to detect faces in the extracted frames with high precision.
- **Annotated Output**: The detection results are plotted on the frames, and annotated frames are saved for further analysis.


