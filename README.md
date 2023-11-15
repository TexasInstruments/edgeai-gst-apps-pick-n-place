# Edge AI GStreamer Apps
> Repository to host GStreamer based Edge AI applications for TI devices
> Based off of the EDGEAI_APP_STACK_08_06_01_00 tag of edgeai-gst-apps

## Summary

This repo adds support for AprilTag detetion using Niryo USB camera on top of edgegai-gst-apps for [robotics arm pick-n-place](https://github.com/TexasInstruments/jacinto-picknplace-demo) demo. 

### New Features 

- This repo includes edgeai-mmdet yolox-nano-lite network artifact trained on AprilTags. 
- Custom gstreamer pipeline is added to process Niryo USB camera
- In the post-processing of object detection, input camera image and camera info are publised as ROS topics

### SDK Version

AprilTag detection network is running on **EdgeAI SDK Verion 8.6**
