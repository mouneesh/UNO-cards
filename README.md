# UNO-cards
## Project Description
This system enables real-time detection of UNO cards using Python programming with the OpenCV and TensorFlow libraries. The application combines a CNN (convolutional neural network) for numeral identification on the cards and HSV color space techniques for color recognition.

## Key Features
- **Number Detection in Real-Time:** Leverages a CNN to identify numbers on the UNO cards.
- **Color Recognition:** Utilizes algorithms based on HSV color space for detecting the card colors.
- **Webcam Functionality:** Supports real-time card detection through a standard webcam setup.

## System Requirements
- **Anaconda Installation:** Required for managing dependencies. Download from [Anaconda's website](https://www.anaconda.com/download).

## Setup Instructions
1. Obtain the source code by cloning the repository:

```git clone <repository-url>```

2. Ensure all dependencies are installed by running:

```pip install -r requirements.txt```

Dependencies listed in `requirements.txt` include:
- numpy
- opencv-python
- matplotlib
- tensorflow

## Operating Instructions
Execute the system by running `final_copy.py`:

```python final_copy.py```

The command activates the webcam, allowing you to present UNO cards to it. The system then displays the detected numbers and colors on the video feed in real-time. To exit, press 'q'.

## Structure of the Project
- **final_copy.ipynb:** Main executable script that processes the video input.
- **best_model.keras/:** file containing the TensorFlow models used.
- **cards/:** Directory with UNO cards imagesfor processing and color detection tasks.

## Model Development
For those interested in training the model:
1. Gather a set of labeled UNO card images.
2. Employ a CNN to develop the number detection model.
3. Store the final model within the  folder.


## Additional Information
- Ensure that the repository URL and any file paths or names match those used in your actual project configuration.
