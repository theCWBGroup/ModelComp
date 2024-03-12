# A Comparative Study of Real-Time Object Detection Algorithms

Our research project aiming to enhance navigation for individuals with visual impairments through real-time object detection and tracking algorithms. In this project, we evaluated four prominent models on an Indoor Objects Detection dataset. The models assessed are YOLOv5, SSD, Faster R-CNN, and Mask R-CNN.

## Models Overview

### 1. YOLOv5

**Overview:**
- YOLO (You Only Look Once) is known for its real-time object detection capabilities.
- YOLOv5 is the latest version, offering improved speed and accuracy.

**Results:**
| Metric           | Value     |
|------------------|-----------|
| Accuracy         | 90.1%     |
| Total Time       | 38.25 sec |
| Average Time     | 0.357 sec |

### 2. SSD (Single Shot Multibox Detector)

**Overview:**
- SSD is recognized for its balanced accuracy and speed.
- It uses default boxes and predicts bounding box offsets and class scores simultaneously.

**Results:**
| Metric           | Value     |
|------------------|-----------|
| Accuracy         | 79.8%     |
| Total Time       | 77.27 sec|
| Average Time     | 0.72 sec  |

### 3. Faster R-CNN (Region-based Convolutional Neural Network)

**Overview:**
- Faster R-CNN employs a two-stage approach for better precision in object detection.
- It uses a Region Proposal Network (RPN) for generating region proposals.

**Results:**
| Metric           | Value     |
|------------------|-----------|
| Accuracy         | 69%       |
| Total Time       | 703.73 sec|
| Average Time     | 6.57 sec  |

### 4. Mask R-CNN

**Overview:**
- Mask R-CNN extends Faster R-CNN to include instance segmentation in addition to object detection.
- It predicts segmentation masks for each detected object instance.

**Results:**
| Metric           | Value     |
|------------------|-----------|
| Accuracy         | 61.06%    |
| Total Time       | 790.80 sec|
| Average Time     | 7.60 sec  |
