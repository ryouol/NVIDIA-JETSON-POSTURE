# Description 
A program OpenPose based for posture analysis.

Program provide to watch patient's movement until the right position and save the new outline of body and angle values using Jetson Nano.

The 'server.py' can be used on any Developer Kit. And at least 1 camera must be integrated to the Kit.

The 'client.py' is for your personal computer, you can remote here all of operations on Kit.


# Dependencies

The following are required:

* Jetson Nano with integrated camera
* python3
* [OpenPose API](https://github.com/CMU-Perceptual-Computing-Lab/openpose)
* OpenCV (min version 2)

# Cloning and Installing Dependencies
 $ `git clone https://github.com/ysfzkn/posture-anaylsis-app/`
 
 $ `cd posture-anaylsis-app`
 
 $ `pip3 install -r requirements.txt`

# Run

* After activate the server program in Jetson Nano,
* It's just enough run this command on your PC:
* $ `python3 client.py` 
