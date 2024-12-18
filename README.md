# Face-Recognition-Attendance-Management-System
Attendance Management System based on Face Recognition using Python  and OpenCv  


### Code Requirements
- Opencv(`pip install opencv-python`)
- Tkinter(Available in python)
- PIL (`pip install Pillow`)
- Pandas(`pip install pandas`)

### What steps you have to follow??
- Download my Repository 
- Create a `TrainingImage` folder in a project.
- Open a `AMS_Run.py` and change the all paths with your system path
- Run `AMS_Run.py`.

### Project Structure

- After run you need to give your face data to system so enter your ID and name in box than click on `Take Images` button.
- It will collect 200 images of your faces, it save a images in `TrainingImage` folder
- After that we need to train a model(for train a model click on `Train Image` button.
- It will take 5-10 minutes for training(for 10 person data).
- After training click on `Automatic Attendance` ,it can fill attendance by your face using our trained model (model will save in `TrainingImageLabel` )
- it will create `.csv` file of attendance according to time & subject.
- You can store data in database (install wampserver),change the DB name according to your in `AMS_Run.py`.
- `Manually Fill Attendance` Button in UI is for fill a manually attendance (without facce recognition),it's also create a `.csv` and store in a database.

Set Up MySQL Database
Create a MySQL database to store attendance records.
Update the database connection details in the code as needed.

 Download Haarcascade
Download the Haarcascade XML file for face detection from the OpenCV GitHub repository and place it in the project directory.

Usage
1. Capture Images
Run main_Run.py to open the GUI.
Enter the student's enrollment number and name.
Click on "Take Images" to capture their face images.
2. Train the Model
After capturing images, click on "Train Images" to train the face recognition model.
3. Automatic Attendance
Select "Automatic Attendance" to start the face recognition process using the webcam.
4. Manual Attendance
Use the "Manually Fill Attendance" option to manually fill attendance records.
5. View Registered Students
Access the admin panel to view the list of registered students and their details.

Directory Structure
Attendance Management System using Face Recognition/
│
├── TrainingImage/               # Directory to store training images
├── TrainingImageLabel/          # Directory to save trained model
├── StudentDetails/              # Directory to save student details CSV
├── Attendance/                  # Directory to save attendance records
├── haarcascade_frontalface_default.xml  # Haarcascade file for face detection
├── requirements.txt             # Required Python packages
├── main_Run.py                  # Main application file
├── training.py                  # Script for training the face recognition model
├── testing.py                   # Script for testing face recognition
├── mini_app.py                  # Simple GUI application for capturing images
├── app.py                       # Streamlit app for attendance visualization
└── README.md                    # Project documentation

Contributing
Contributions are welcome! If you have suggestions for improvements or additional features, feel free to fork the repository and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to the following:

OpenCV for face detection and recognition functionalities.
Tkinter for GUI development.
NumPy and Pandas for data manipulation and analysis.
MySQL for database management.
For any questions or issues, feel free to contact [udayroyal2001@gmail.com].

Attendance-Management System Using Face Recognition
