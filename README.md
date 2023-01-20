# detect-object
How to run this code?
Step 1: Create a directory in your local machine and cd into it

mkdir ~/Desktop/opencv_project
cd ~/Desktop/opencv_project
Step 2: Clone the repository and cd into the folder:

git clone https://github.com/Surya-Murali/Real-Time-Object-Detection-With-OpenCV.git
cd Real-Time-Object-Detection-With-OpenCV
Step 3: Install all the necessary libraries. I used MacOS for this project. These are some of the libraries I had to install:

brew install opencv
pip install opencv-python
pip install opencv-contrib-python
pip install opencv-python-headless
pip install opencv-contrib-python-headless
pip install matplotlib
pip install imutils
Make sure to download and install opencv and and opencv-contrib releases for OpenCV 3.3. This ensures that the deep neural network (dnn) module is installed. You must have OpenCV 3.3 (or newer) to run this code.

Step 4: Make sure you have your video devices connected (e.g. Webcam, FaceTime HD Camera, etc.). You can list them by typing this in your terminal

system_profiler SPCameraDataType
system_profiler SPCameraDataType | grep "^    [^ ]" | sed "s/    //" | sed "s/://"
Step 5: To start your video stream and real-time object detection, run the following command:

python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel
Step 6: If you need any help regarding the arguments you pass, try:

python real_time_object_detection.py --help

please help me continue working on this project buy a small donation 
thank you!

</br>
<a href="https://www.buymeacoffee.com/plantholdercrys" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

