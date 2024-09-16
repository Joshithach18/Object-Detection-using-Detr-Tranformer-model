Object Detection in Images and Videos Using DETR Transformer Models

This project implements object detection in both images and videos using the DETR (DEtection TRansformer) model, a transformer-based approach to object detection. By leveraging the powerful DETR model, we aim to eliminate the need for anchor boxes and non-maximum suppression (NMS) while providing an end-to-end, transformer-based solution for detecting objects in real-time images and video streams.

Project Overview

Object detection is a core task in computer vision with numerous applications in fields such as autonomous driving, surveillance, healthcare, and more. Traditional object detection models rely heavily on region proposals, anchor boxes, and NMS to detect objects, which makes the pipeline complex. DETR, introduced by Facebook AI, simplifies this by applying a transformer architecture, allowing direct prediction of object locations and categories.

This project demonstrates:

How to use the DETR model for object detection in static images.

How to extend the same functionality to detect objects in real-time video streams.

The annotation of detected objects in images and video frames using bounding boxes and class labels.

Key Features

Image and Video Processing: Perform object detection on both static images and video files.

Transformer-Based Model: Use of the DETR (DEtection TRansformer) model for object detection.

Bounding Box Annotations: Annotate images and video frames with bounding boxes and labels corresponding to detected objects.

Real-Time Detection: Detect and label objects in video streams efficiently with GPU support.

Requirements

Supervision: Used for handling object detection annotations and visualizations.

Transformers: Provides the DETR model implementation for object detection.

PyTorch Lightning: Simplifies model training and organization.

Roboflow: Facilitates data collection and processing.

Timm: Provides image models and utilities.

Usage

Object Detection in Images

Load an image.

Process the image through the DETR model.

Extract and display bounding boxes and object labels.

Object Detection in Videos

Capture video frames.

Use the DETR model to detect objects in each frame.

Annotate frames with bounding boxes and labels, then save or display the video with detections.

Applications
Autonomous Vehicles: For detecting pedestrians, other vehicles, and obstacles.

Surveillance Systems: Real-time monitoring of security footage to detect suspicious objects or behaviors.

Retail: Detecting and tracking products or customers for automated checkouts or inventory systems.

Healthcare: Identifying medical objects in images such as X-rays or MRI scans.

Future Work

This is a beginner-level project designed to dive deeper into CNNs and computer vision, with further plans to:

Explore fine-tuning the DETR model for specific datasets.

Implement real-time object detection on live video streams.

Extend the project to other tasks like instance segmentation or tracking.

Contributions

Feel free to open an issue or submit a pull request if you'd like to contribute to improving this project!
