# FaceRecognition_OpenCV
This project deals with Face Recognition problem. Here the approach used is OpenCV.



Here we have only 2 classes.

Number of people: 2
Training size (per person): 12 images
Test Size (per peson): 1 image

------------------------------
Dir

  |
  |
  |Train Set
    |
    |s1
      |
      |(12 images)
    |s2
      |
      |(12 images)
  |Test Set
    test_img1
    test_img2
    
-----------------------------
Other Algorithms that could have been used are:
1. Support Vector Classifiers
2. K nearest neighbors
---------------------
Exeution Steps:
1. Create a folder "training-data"
2. Inside training-data folder create 2 folders "s1" and "s2" and copy two sets of training images in each of them.
3. Create a folder "test-data" and paste the test images inside it. (the test-data folder should be created alongside training-data )
4. Now install the required packages mentioned (or imported) in code.
5. Edit the subjects name inside the code.
6. Use "python OpenCV-Face-Recognition-Python.py" command in order to run the python project.
