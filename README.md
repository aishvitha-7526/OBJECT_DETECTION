# Real-Time Object Detection using YOLOv8

## Project Overview

This project implements a Real-Time Object Detection System using YOLOv8 and OpenCV. The application captures live video from a webcam and detects objects in real time using the YOLOv8 deep learning model. Detected objects are highlighted with bounding boxes and labels, providing accurate and efficient object recognition.

## Features

- Real-time object detection using webcam
- Multiple object detection and classification
- Bounding box visualization
- Fast and accurate detection with YOLOv8
- Simple and easy-to-understand implementation

## Technologies Used

- Python
- OpenCV
- Ultralytics YOLOv8

## Requirements

Install the required libraries:

```bash
pip install ultralytics opencv-python
```

## Project Structure

```
Real-Time-Object-Detection/
│
├── object_detection.py
├── yolov8n.pt
└── README.md
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Real-Time-Object-Detection.git
```

2. Navigate to the project folder:

```bash
cd Real-Time-Object-Detection
```

3. Run the Python script:

```bash
python object_detection.py
```

4. The webcam will open and start detecting objects in real time.

5. Press **Q** to exit the application.

## Working Principle

1. Load the YOLOv8 pre-trained model.
2. Capture video from the webcam using OpenCV.
3. Process each frame through the YOLOv8 model.
4. Detect and classify objects present in the frame.
5. Draw bounding boxes and labels around detected objects.
6. Display the annotated frame in real time.

## Sample Detectable Objects

- Person
- Mobile Phone
- Bottle
- Chair
- Laptop
- Keyboard
- Mouse
- Book
- Cup
- Backpack

and many more objects supported by YOLOv8.

## Applications

- Smart Surveillance Systems
- Security Monitoring
- Traffic Analysis
- Robotics
- Industrial Automation
- Computer Vision Research
- AI-Based Monitoring Systems

  <img width="1048" height="939" alt="Screenshot 2026-06-01 211141" src="https://github.com/user-attachments/assets/eb487cec-46a3-4204-8178-f557b93fe66b" />


## Future Enhancements

- Custom Object Detection
- Object Tracking
- Face Recognition
- Sign Language Recognition
- Video File Detection Support
- Performance Optimization

## Conclusion

This project demonstrates the implementation of a real-time object detection system using YOLOv8 and OpenCV. It highlights the effectiveness of deep learning in computer vision applications by accurately detecting and classifying objects from live video streams.

