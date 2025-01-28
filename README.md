# Face Recognition Based Attendance System Master

# Overview

This project is a Face Recognition-Based Attendance System built using Python and AI, leveraging the K-Nearest Neighbors (KNN) algorithm for efficient and accurate face classification. It automates the process of marking attendance by recognizing faces in real-time or from pre-recorded images or videos. 

# Features

•	Face Detection and Recognition: Uses state-of-the-art AI models to detect and identify faces.
•	Attendance Logging: Automatically logs attendance data into a file or database.
•	Real-Time Processing: Supports real-time face recognition via webcam.
•	KNN Algorithm: Employs KNN for face classification, ensuring simplicity and reliability.
•	User-Friendly Interface: Easy to use and configure.

# Requirements

Software and Libraries
•	Python 3.7+
•	OpenCV
•	NumPy
•	dlib
•	face_recognition
•	pandas
You can install the dependencies using the following command:
pip install -r requirements.txt

# Installation

1.	Clone the repository:
2.	git clone https://github.com/yourusername/face-recognition-based-attendance-system.git
3.	cd face-recognition-based-attendance-system
4.	Install required libraries:
5.	pip install -r requirements.txt
6.	Set up the dataset directory:
o	Create a folder named dataset inside the project directory.
o	Add labeled subfolders for each person (e.g., dataset/Person1, dataset/Person2, etc.).
7.	Train the KNN classifier:
8.	python train_knn.py
9.	Run the application:
10.	python main.py

# Usage

1.	Prepare Dataset: Collect images of individuals to be recognized and save them in labeled folders inside the dataset directory.
2.	Train Model: Use the train_knn.py script to train the KNN classifier.
3.	Run System: Execute main.py to start the face recognition system.
4.	Attendance Logs: Check the attendance.csv file (or database) for logged attendance records.

# File Structure

face-recognition-based-attendance-system/
|-- dataset/               # Directory for training images
|-- main.py                # Main application script
|-- train_knn.py           # Training script for the KNN classifier
|-- attendance.csv         # Attendance log file
|-- requirements.txt       # Required Python libraries
|-- README.md              # Project documentation

# How It Works

1.	Face Detection: Detect faces using the face_recognition library.
2.	Feature Extraction: Extract facial features and encode them.
3.	Classification: Use the KNN algorithm to classify the detected face based on the training dataset.
4.	Attendance Logging: Record the identified individual’s name and timestamp in the attendance log.

# Future Enhancements

•	Add GUI for a more intuitive user experience.
•	Integrate with cloud-based storage for attendance logs.
•	Implement multi-camera support.
•	Enhance model accuracy with advanced algorithms.

# Screenshot
![ss](https://github.com/user-attachments/assets/f4782286-6abf-4087-9e29-2689557667ac)


# Acknowledgments

•	This project uses the face_recognition library.
•	Thanks to the open-source community for contributing to these technologies.

# License

This project is licensed under the MIT License.

Contact
For any queries or support, please contact:
•	Name: Himanshu
•	Email: himanshu9917066767@gmail.com
•	GitHub: https://github.com/Himanshu70-17

