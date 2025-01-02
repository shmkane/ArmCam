# **ROS Camera & AprilTag Tracking System**  

## **Overview**  
This project is a **ROS-based vision system** integrating **OpenCV** and **AprilTag detection** to enable real-time camera streaming, image capture, and tag recognition. It leverages a **USB camera node** to process visual data and provides modular capabilities for **object tracking** and **pose estimation**—ideal for robotics and autonomous systems.  

The system was designed to support **live video feeds**, image analysis, and object detection using AprilTags, enabling precise localization and mapping applications.  

## **Key Features**  
- **Real-Time Camera Streaming**: Streams live video from a USB camera directly to a local web interface at `localhost:8080`.  
- **AprilTag Detection**: Implements the **apriltag_ros** package for high-accuracy tag recognition and position tracking.  
- **ROS Integration**: Built as a **ROS (Robot Operating System) package**, enabling seamless interaction with other robotics frameworks and nodes.  
- **OpenCV Support**: Utilizes OpenCV for image processing and analysis, enabling advanced vision-based algorithms.  
- **Image Capture**: Captures and saves snapshots from the video feed for further processing.  
- **Flexible Launch System**: Includes example launch files for quick deployment of camera nodes and tag detection pipelines.  
- **Submodule Integration**: Modularized codebase with submodules for enhanced reusability and extensibility.  
- **Development Workflow Optimization**: Includes robust file management, dependency handling, and streamlined ROS workspace setup.  

## **Use Cases**  
- **Autonomous Robotics**: Ideal for robots requiring visual recognition, navigation, and localization using fiducial markers (AprilTags).  
- **Surveillance Systems**: Supports capturing and analyzing real-time video streams for monitoring applications.  
- **AR/VR Applications**: Provides marker-based tracking for augmented and virtual reality systems.  
- **Research Prototyping**: Acts as a foundation for experimental robotics, AI research, and vision-based algorithms.  

## **Technologies Used**  
- **ROS (Robot Operating System)** for modular robotics development.  
- **OpenCV** for image processing and computer vision algorithms.  
- **apriltag_ros** for marker detection and localization.  
