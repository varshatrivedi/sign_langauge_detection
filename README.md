# Sign Language Detection with TensorFlow

## Overview
This project involves creating a console-based application that detects and translates sign language gestures into text using Python. The app employs a combination of Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN), trained on a dataset of hand gestures. OpenCV is used for real-time video processing.

---

## Features
- **Real-Time Gesture Detection**: Processes live video feed to identify gestures.
- **CNN and RNN Models**: Utilizes CNN for feature extraction and RNN for sequence classification.
- **Custom Dataset Support**: The application is adaptable to various datasets for different sign languages.

---

## Technology Stack
1. **Python**: Core programming language for the application.
2. **TensorFlow**: Used for creating and training the CNN and RNN models.
3. **PyTorch**: Optional integration for experimentation and advanced model development.
4. **OpenCV**: Handles video processing for real-time gesture detection.

---

## How to Use

### Prerequisites
1. Python 3.7 or higher
2. Install required libraries:
   ```bash
   pip install tensorflow opencv-python numpy
   ```
3. Download the trained CNN and RNN models (`cnn_model.h5` and `rnn_model.h5`).

### Running the Application
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sign-language-detection.git
   cd sign-language-detection
   ```
2. Run the main script:
   ```bash
   python sign_language_detection.py
   ```
3. Use your webcam to perform sign language gestures. Press **'q'** to quit.

---

## Training the Models
1. **Dataset**:
   - Collect and preprocess a dataset of hand gestures.
   - Ensure the dataset has labeled sequences for RNN training.
2. **CNN Model**:
   - Train a CNN to extract spatial features from hand gesture images.
   - Save the model as `cnn_model.h5`.
3. **RNN Model**:
   - Train an RNN on the extracted CNN features for gesture classification.
   - Save the model as `rnn_model.h5`.

---

## Example Gestures
The following gestures are detected by the application:
- **Hello**
- **Thank You**
- **Yes**
- **No**
- **Please**

---

## Contributions
Feel free to contribute to this project by submitting pull requests or reporting issues.

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

## Contact
For questions or support, please reach out to [your email address].

