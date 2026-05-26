# Hand Gesture Recognition using SVM

## Project Description
This project develops a Hand Gesture Recognition System using Machine Learning techniques. The model classifies different hand gestures from image data using the Support Vector Machine (SVM) algorithm.

The project demonstrates:
- Image preprocessing
- Feature extraction
- Gesture classification
- Model training and testing
- Performance evaluation
- Gesture visualization

---

## Technologies Used
- Python
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Dataset Used
Leap Gesture Recognition Dataset

Dataset Source:
https://www.kaggle.com/datasets/gti-upm/leapgestrecog

The dataset contains multiple hand gesture images categorized into different classes.

---

## Algorithm Used
Support Vector Machine (SVM)

Kernel Used:
- Linear Kernel

---

## Project Workflow
1. Imported required libraries
2. Loaded hand gesture image dataset
3. Preprocessed images using OpenCV
4. Converted images into feature vectors
5. Split dataset into training and testing sets
6. Trained SVM classifier
7. Predicted gesture classes
8. Evaluated model performance
9. Displayed gesture visualization

---

## Files Included

```text
SCT_ML_4
│
├── dataset
│   └── leapGestRecog
│
├── notebook
│   └── hand_gesture_recognition.ipynb
│
├── screenshots
│
├── requirements.txt
│
└── README.md
```

---

## Screenshots Included
- Project Structure
- Dataset Loaded Output
- Feature Shape Output
- Train-Test Split Output
- Model Training Output
- Accuracy Output
- Classification Report
- Confusion Matrix
- Gesture Prediction Output
- Final Notebook Output

---

## Results
The model successfully classified hand gestures with good accuracy using the SVM algorithm.

The project demonstrates the effectiveness of Machine Learning techniques in gesture recognition systems.

---

## Future Improvements
- Real-time webcam gesture recognition
- Deep Learning implementation using CNN
- Increased dataset size
- Improved model accuracy
- Deployment using Flask or Streamlit

---

## How to Run

### Install Required Libraries

```bash
pip install -r requirements.txt
```

---

### Run Jupyter Notebook

Open:

```text
hand_gesture_recognition.ipynb
```

Run all cells sequentially.

---

## Requirements

```text
numpy
pandas
matplotlib
opencv-python
scikit-learn
jupyter
```

---

## Author
Y.Rahul
