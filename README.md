# Object Detection on Raspberry Pi 3

An object recognition application using [Google's TensorFlow Object Detection API](https://github.com/tensorflow/models/tree/master/object_detection), [PiCamera](http://picamera.readthedocs.io/en/release-1.13/index.html) and [OpenCV](http://opencv.org/).

## Requirements
- [Python 2.7](https://www.python.org/)
- [PiCamera](https://picamera.readthedocs.io/en/release-1.13/)
- [TensorFlow 1.2](https://www.tensorflow.org/)
- [OpenCV 3.1](http://opencv.org/)

## Installation
0) Always good practice to update everything before you install stuff:
```
sudo apt-get update
sudo apt-get upgrade
sudo rpi-update
```

1) Install picamera and pip
```
sudo apt-get install python-picamera
sudo apt-get install python-pip python-dev
```

2) Install Tensorflow using pip
```

pip install tensorflow
```
3) Install pre-complied OpenCV 3.1.0 following the instructions [here](https://github.com/jabelone/OpenCV-for-Pi).

## Getting Started
`python single_thread_detect_objects_from_camera.py`


## Copyright

See [LICENSE](LICENSE) for details.
Copyright (c) 2017 Hua Shu.
