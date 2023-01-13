# Egyptian_Car_Plates_Using_YOLOV7
Nowadays, organizations try to increase safety and security among themselves, so, it is important for them to notice who entered the organization and who left, So, many organizations have their security systems which includes cars license plate detection System.

Data Collection And Preprocessing:

We used License plates pictures captured from real life, we used Roboflow as Annotation tool to make annotations to the boundaries of the objects in the image.

Algorithm Used:

We used YOLOV7 as an object detection Model, due to it’s high accuracy and fast speed in detection, YOLO use multiple CNN layers in which the image is divided into grids and pass through the CNN layers.

So we got a mAP of 0.92 on all the data, we can improve it by adjusting some parameters like learning rate.

You will find 2 Jupyter notebooks in this repository, Egyption_Car_Plates_Detection is the YOLO Algorithm, but the other one named Testing_on_image is where you can test the 2 models on your own image
