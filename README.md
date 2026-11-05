# YOLOv8 Object Detection Using Laptop Camera

## Aim
To capture images using a laptop camera and detect objects using the YOLOv8 model.

## Technologies Used
- Python
- Anaconda
- Jupyter Notebook
- OpenCV
- YOLOv8 (Ultralytics)
- Matplotlib

## Requirements
- Anaconda installed
- Jupyter Notebook
- Laptop camera
- Python 3.8 or later (compatible package versions)

## Installation

Install the required libraries:

```bash
pip install opencv-python ultralytics matplotlib
```

## Algorithm

1. Open Jupyter Notebook using Anaconda.
2. Access the laptop camera using OpenCV.
3. Wait for 5 seconds.
4. Capture and display an image.
5. Load the YOLOv8 pretrained model.
6. Perform object detection.
7. Display detected objects with bounding boxes and labels.
8. Repeat the experiment for three different scenes.

## Experimental Scenes

- **Scene 1:** Detect objects in a single-object scene.
- **Scene 2:** Detect multiple objects in one image.
- **Scene 3:** Detect objects in a different environment.

## Expected Output

The captured images are processed using YOLOv8. The detected objects are displayed with:
- Bounding boxes
- Object labels
- Confidence scores

## Conclusion

Successfully captured images using the laptop camera and detected objects in three different scenes using YOLOv8. OpenCV was used for image capture, and YOLOv8 was used for object detection.

## Reference

- [Ultralytics YOLOv8 GitHub](https://github.com/ultralytics/ultralytics)
- [OpenCV Documentation](https://docs.opencv.org/)
