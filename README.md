# YOLOv3-Object-Detection-with-OpenCV

This project implements an image and video object detection classifier using pretrained yolov3 models. 
The yolov3 models are taken from the official yolov3 paper which was released in 2018. The yolov3 implementation is from [darknet](https://github.com/pjreddie/darknet). Also, this project implements an option to perform classification real-time using the webcam.

## How to use?

1) Clone the repository

```
git clone https://github.com/noorkhokhar99/object-detect.git
```

2) Move to the directory
```
cd YOLOv3-Object-Detection-with-OpenCV
```

3) To infer on an image that is stored on your local machine
```
python3 yolo.py --image-path='/path/to/image/'
```
4) To infer on a video that is stored on your local machine
```
python3 yolo.py --video-path='/path/to/video/'
```
5) To infer real-time on webcam
```
python3 yolo.py
```

Note: This works considering you have the `weights` and `config` files at the yolov3-coco directory.
<br/>
If the files are located somewhere else then mention the path while calling the `yolov3.py`. For more details
```
yolo.py --help
```

## Inference on images


![yolo_img_infer_1](https://github.com/noorkhokhar99/object-detect/blob/main/Screen%20Shot%201444-03-12%20at%2010.31.26%20PM.png)


## Inference on Video

![yolov3-video](https://github.com/noorkhokhar99/object-detect/blob/main/Screen%20Shot%201444-03-12%20at%2010.31.26%20PM.png)(https://www.youtube.com/c/Pyresearch)

<small> Click on the image to Play the video on YouTube </small>





