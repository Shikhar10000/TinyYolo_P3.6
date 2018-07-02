# TinyYolo_P3.6
Tiny Yolo Detection System For Python 3.6


## Rquirements:

  Numpy

  Python 3.6

  Tensroflow

  OpenCV


## Steps to use this code:
Go to utils/ and run:
$ python config.py
this downloads the darknet weight files. Also, fuses batchnorm layers and creates TensorFlow Ckpt files.


### To run image inference:
$ python inference.py , to run TinyYolo model
$ python infernce.py --v2 , to run YoloV2 model
$ NUM_INTER_THREADS=2 NUM_INTRA_THREADS=8 python inference.py --par , to run parallel TensorFlow session(Inter/Intra op threads), if it is supported in your system.

### To run Webcam inference:
$ python webcam_inference.py

Please refer the paper mentioned above to know more about the system used for testing and the versions of software tools used.
