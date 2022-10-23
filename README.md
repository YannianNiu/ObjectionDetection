# ObjectionDetection
A project for Fundamentals of Artificatial Intilligence (fall, 2020, ECNU).

A simple object detection Demo using YoloV3.

Training Steps:
1. Use the voc2yolo3.py file to generate the corresponding txt before training.(Training on the voc2007 dataset, I don't upload it since its big size)
2. Run voc_annotation.py, a 2007_train.txt is generated, with each line corresponding to the position of the image in the dataset and the position of the object's box in the image.
3. Before training, be sure to create a new txt document under model_data, in which you enter the classes to be divided.
4. Modify the classes in utils/config.py so that it is the number of classes to detect.
5. Run train.py to start training.

Camera detection and video stream detection can be performed using video.py.

Run predict.py and enter the name of the image such as street.jpg to detect the object in the image.
