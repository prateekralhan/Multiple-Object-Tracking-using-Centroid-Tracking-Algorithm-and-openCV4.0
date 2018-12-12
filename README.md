# Multiple-Object-Tracking-using-Centroid-Tracking-Algorithm-and-openCV4.0
Multiple object tracking mechanism achieved using centroid tracking algorithm and openCV4.0.

## Libraries Installation:

1. OpenCV4.0: Refer this: https://www.pyimagesearch.com/opencv-tutorials-resources-guides/

2. numpy/argparse/imutils/scipy: Do _pip install numpy/argparse/imutils/scipy_

An ideal object tracking algorithm will:

    Only require the object detection phase once (i.e., when the object is initially detected)
    Will be extremely fast — much faster than running the actual object detector itself
    Be able to handle when the tracked object “disappears” or moves outside the boundaries of the video frame
    Be robust to occlusion
    Be able to pick up objects it has “lost” in between frames
    
## The centroid tracking algorithm
The centroid tracking algorithm is a multi-step process.

### STEP 1: Compute Euclidean distance between new bounding boxes and existing objects

### STEP 2: Update (x, y)-coordinates of existing objects

### STEP 3: Register new objects

### STEP 4: Deregister old objects

### Run command: 
python object_tracker.py --prototxt deploy.prototxt --model res10_300x300_ssd_iter_140000.caffemodel

![screenshot from 2018-12-12 13-08-38](https://user-images.githubusercontent.com/29462447/49854124-3a3f6d80-fe0f-11e8-820b-61edbfc38d3c.png)
