# Face-Recognition
A simple face recognition app built in Python using KNN

# Algorithms Used
- K nearest neighbors from scikit-learn. You can also use your own KNN implementation.
- Used haar cascade classifier for face detection.
# How does it work
- First open "FaceDeteciton.py" it will ask for the name of the user whoose face is to be recognized.
- It will then open the camera and will start taking samples of the face.
- Once all the samples are taken camera will automatically be closed.
- Now open "FaceRecog.py", it will open the camera and start recognizing the faces it sees. 

# Loopholes
- Since it uses KNN so even if you show someone totally new whoose samples are not registered in the app.
it will still classify it as one of the available samples.

# Scope of Improvement 
- There are various ways to implement Face recognition. If you want a higher accuracy then you can use convolutional neural networks.
- You can implement a logic in the program which says "Not a match" if a new person is shown to the camera by simpling changing the voting mechanism in KNN.