
# Emotion Detection using OpenCV and Keras

This project implements a real-time facial emotion detection system using OpenCV and Keras. It can classify emotions like happy, sad, angry, surprised, and more based on the input image from a webcam or any other video source.





## Features

- Real-time emotion detection from webcam feed.
- Detects and classifies human emotions such as:
    - Happy
    - Sad
    - Angry
    - Surprise
    - Neutral
- Utilizes Convolutional Neural Networks (CNNs) for emotion recognition.
- Built with OpenCV for real-time image processing.
- Trained on the FER2013 dataset for emotion classification.
- User-friendly interface with live camera feed and emotion labels.


## Technologies Used

- **OpenCV**: For image processing and webcam video capture.
- **Keras**: High-level neural networks API for training and prediction.
- **TensorFlow**: Backend framework for Keras.
- **Python**: Primary programming language used


## Prerequisites
To run this project, ensure you have the following installed:

- Python 3.x
- OpenCV
- Keras
- TensorFlow
- NumPy
- Matplotlib

Install the required dependencies using the following command:

```bash
 pip install -r requirements.txt
```


## Installation

1. Clone the repository:

```bash
  https://github.com/techvaishnavi/Emotion_detection.git
```

2. Navigate to the project directory:

```bash
cd emotion-detection

```
3. Install the dependencies:

```bash
pip install -r requirements.txt
```
4. Download the pre-trained model (if available) or train the model using the FER2013 dataset.

5. Run the project:

```bash
python emotion_detection.py

```
The webcam feed will open, and the system will classify emotions in real-time
 

## Results

After training, the model achieves an accuracy of around **65-70%** on the test set. You can further fine-tune the model by experimenting with different network architectures and hyperparameters
## Contributing

Feel free to fork this repository and submit pull requests. Any contributions, from bug fixes to new features, are welcome!
## License

This project is licensed under the MIT License - see the [License](https://choosealicense.com/licenses/mit/) file for details.



## Acknowledgements

- Thanks to the creators of the FER2013 dataset.
- Inspired by projects in emotion detection and facial recognition.

