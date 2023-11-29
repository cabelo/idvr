![image](https://github.com/cabelo/idvr/assets/675645/745cdd0e-4c72-40ef-89e1-6095239c3d83)


# iDVR Intelligent Digital Video Recording
The objective of the project is to obtain a stream of h265 videos encoded by external devices or by the server itself. But with a big difference: the stream or video will be indexed by models of convolutional neural networks. The system will find specific scenes without evaluating all media content.

## Intel Technologies
DevCloud, oneAPI, DPC++, Intel Deep Link, Intel Integrated Graphics, Movidius NCS, OpenVINO

## Overview / Usage
Searching for information and analyzing it in video files takes time when we need to collect information stored on large scales. With intelligent cameras and 3d depth, we can insert information as metadata at intervals of the frames of the videos. This information is generated with models of convolutional neural networks processed on the capture device or on the server.

So analyzing traffic of people and vehicles, detecting robbery, fights in the crowd, people in danger is made possible with these systems. As well as looking for past events.

## Methodology / Approach
The video is captured with a webcam, smart cameras with movidius or realsense and converted to h265 for sending on the server. With cameras with OAK, or OAK-D that uses the movidius chip, the object's coordinates can be processed in real time and submitted to the server along with the video stream.

​If the camera has a depth sensor such as OAK-D or Realsense, the distance from the object will be sent as metadata along with the result of the inference processing.

## Technologies Used
- Movidius
- OAK
- OAK-D
- Realsense
- openCV
- openVINO
- oneAPI
- devcloud
- Iris Xe Max
- openSUSE
