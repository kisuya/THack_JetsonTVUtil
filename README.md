# THack_JetsonTVUtil
TV Watching guide Application 


## Features
* Face Detection and calculate distance from tv
  * use Darknet Yolo - face weight
    * https://github.com/quanhua92/darknet/
    * https://github.com/dannyblueliu/YOLO-version-2-Face-detection
* Pose Estimation and detect wrong pose 
  * use openpose
    * https://github.com/CMU-Perceptual-Computing-Lab/openpose
* Segmentation for background change
  * use FastMask
    * https://github.com/voidrank/FastMask
    * compile error 
      * hdf5 
        * https://stackoverflow.com/a/37057313
      * openblas
        * https://stackoverflow.com/a/37448511
* send event to set-top box via http

  
  
## System Architecture
* OS - Ubuntu 16.04.02
* Qt with OpenCV Based application
  * Qt - 5.5.1
  * OpenCV - 2.4.11
* darknet based application
* openpose based application
* FastMask based application