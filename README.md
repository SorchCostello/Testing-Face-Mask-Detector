# Testing Face Mask Detector
Testing Adrian Rosebrock's Face-mask Detector
https://www.pyimagesearch.com/2020/05/04/covid-19-face-mask-detector-with-opencv-keras-tensorflow-and-deep-learning/

*## Face Mask Detector
As part of my summer internship, I was asked to make a people counter code; the inspiration for the code was https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/ .
I decided after completing my internship I wanted to look more into Adrian Rosebrock's codes & blog post. Due to current events I was very intrigued by his “COVID-19: Face Mask Detector with OpenCV, Keras/TensorFlow, and Deep Learning”.*

## Recent Updates:
* Almost all necessary documents have been uploaded; I have chosen to exclude the dataset folder and the train_mask_detector.py file, as the dataset folder was too large. 
* These files are available through Adrian Rosebrock's blog post.

## How To Use:
* to run: python detect_mask_video.py
          or python detect_mask_image.py -i examples/example_01.png (“example_01.png” can be changed to other example images).

## Folders
* examples => Contains the example images (from Rosebrock and my own example folder)
* face_detector => Contains the MobileNet SSD model used (prototxt and caffe files)

## Setup
     1. Install the required libraries (OpenCV, NumPy, SciPy, dlib, imutils) by searching online or using pip install
     2. Download this git repo as a zip
     3. Extract the file to the Documents directory

## Running The Code
     4. Change directory
          ~ cd C:\Users\<USERNAME>\Documents\face-mask-detector
     5. Run the code
          ~ python detect_mask_video.py
          or eg:
          ~ python detect_mask_image.py -i examples/example_01.png
