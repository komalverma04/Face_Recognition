# Face_Recognition
Face Recognition Attendance Marking Tool
This project is a face recognition attendance marking tool that uses computer vision techniques to detect faces in real-time and mark attendance in an Excel sheet. It leverages the face_recognition library to perform face recognition and OpenCV for video capturing and image processing.

Prerequisites
Python 3.x
face_recognition library
OpenCV library
NumPy library
datetime module
Installation
Clone or download the repository to your local machine.

Install the required libraries by running the following command:


pip install face_recognition opencv-python numpy
Usage
Ensure that you have a folder containing images of individuals for attendance marking. The images should be named using the respective person's name (e.g., "John.jpg", "Jane.jpg").

Modify the path variable in the code to the directory path containing the images.

Run the script using the following command:


python attendance_marking.py
The webcam will open, and faces detected by the program will be surrounded by a green rectangle. The detected person's name will be displayed above the rectangle.

The attendance will be marked in real-time and stored in a file named "attendance.csv" in the same directory as the script. The file will contain the name and timestamp of each attendance entry.

Note: Press the 'q' key to exit the program.

Contributions
Contributions to the project are welcome! If you find any issues or have suggestions for improvements, feel free to create a pull request.

License
This project is licensed under the MIT License.
