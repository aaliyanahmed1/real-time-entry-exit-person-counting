# real-time-entry-exit-person-counting

Real-Time Entry/Exit Person Counting System

Project Overview:

This project demonstrates a real-time person counting system that accurately tracks the entry and exit of individuals through a camera feed. The system is designed to be highly efficient and scalable for use in various environments, such as smart buildings, event halls, retail spaces, and security monitoring systems. By leveraging object detection and motion tracking, it provides insights into people flow, enabling improved security and operational efficiency.

Key Features:

Real-time Detection: Uses the YOLO (You Only Look Once) model to detect people in real-time from video feeds.

Entry/Exit Tracking: Monitors the movement of individuals in and out of a predefined area or zone.

Motion Tracking: Detects and tracks movement to ensure accurate counting and avoids duplicate or missed detections.

Scalable Design: The system is designed to work efficiently across multiple cameras or locations.

Technologies Used:

YOLO (Ultralytics): Object detection framework used to detect people in the camera feed.

OpenCV: For video processing, motion tracking, and drawing bounding boxes around detected individuals.

NumPy: For handling numerical operations, including tracking counts and managing coordinates.

Python: Primary language used for the implementation of the system.

Setup Instructions:

  Clone the repository:

  git clone https://github.com/AaliyanAhmed/real-time-entry-exit-person-counting.git

Expected Output:

The system will continuously analyze the video stream and display a real-time count of people entering and exiting the area.

Visualized in the camera feed with bounding boxes indicating detected individuals.

Alerts can be triggered if desired, such as when a specific threshold of people is detected.

Use Cases:
Smart Buildings: Monitoring the flow of people in and out of office spaces, lobbies, or restricted zones.

Security Systems: Enhancing surveillance systems with automated counting to detect anomalies.

Retail Spaces: Tracking customer flow to optimize store layouts and operations.

Contributing:

Feel free to open issues or submit pull requests to improve the system. Contributions such as optimizing the tracking algorithm, adding multi-camera support, or improving UI are welcome.

