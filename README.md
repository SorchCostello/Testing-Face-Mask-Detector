# Testing Face Mask Detector
Testing Adrian Rosebrock's Face-mask Detector 
https://www.pyimagesearch.com/2020/05/04/covid-19-face-mask-detector-with-opencv-keras-tensorflow-and-deep-learning/


# Face Mask Detector
As part of my summer internship, I was asked to make a people counter code; the inspiration for the code was https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/ .
I decided after completing my internship I wanted to look more into  Adrian Rosebrock's codes & blog post. 

## Recent Updates:
* Almost all necessary documents have been uploaded, (dataset have not, as the file was too large; this file is avialable through Adrian Rosebrock's blog post).

## How To Use:
to run: python detect_mask_image.py -i examples/example_01.png
        python detect_mask_video.py
        

## Folders
examples => Contains the MobileNet SSD model used (prototxt and caffe files)  
face_detector => Contains an example video to use for the input argument  
example_outputs => Contains the outputs given by the example input video  
pyimagesearch => Contains further code used to support the main people counter files


## Setup
     1. Make sure you have OpenVINO installed
     2. Install the required libraries (OpenCV, NumPy, SciPy, dlib, imutils) by searching online or using pip install
     3. Download this git repo as a zip
     4. Extract the file to the Documents directory

## Running The Code
     5. Change directory
          ~ cd C:\Users\<USERNAME>\Documents\face-mask-detector
     6. Run the code
          ~ python detect_mask_image.py -i examples/example_01.png
          or
          ~ python detect_mask_video.py
