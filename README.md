 In this Web application, Users can log in either as faculty or student. The student can only search for attendance. Whereas faculty can add, update, mark, and search attendance of students. This project intends to serve as a substitute for manual attendance systems which is very cumbersome and difficult to use and maintain.
 
OpenCv and face_recognition libraries are used for the development of Face Recognizer. Web framework is built using Django.

Note: Python version 3.7 is used for this project. dlib package required for installation of face_recognition api is uploaded.

To run the web app on your local computer, install the required libraries(requirements.txt) using the command:
pip3 install -r requirements.txt

To create your own credential for logging into the application:
python manage.py createsuperuser

Finally run the following command in the command prompt:
python manage.py runserver