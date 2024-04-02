# Detecting-Hate-Hand-Gestures
This program is a project inspired by malicious designers inserting "hate symbols" into outsourced animations.

This makes it easy to find "hate hand gestures" in images, and it can process a large number of images. 

You can learn hate hand gestures with YOLO and then collect the images you want to detect in a folder to check whether they have hate hand gestures or not.



# Programming procedure

We created a dataset to train the model using yolo.

The images were collected by image crawling, and to discriminate them with the val train test, the images were saved in yolo format in txt format by specifying the bounding box for each class using makesense.

Train it with yolo and infer the learned result.

Find the "hateful hand expression" by inference and output it to OpenCV.
