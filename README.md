# Object-Detection-using-OpenCV-
Hello everyone. Being a Computer Vision enthusiast, I have tried to build a model which can detect the people and vehicles in the images and also depict the probability of accuracy of the results. This can be a small prototype of a model which can be implemented through the CCTV cameras for surveillance by the police.

I have used Open Image Dataset(OID) to get the training and testing data of Person + Vehicle. Around 800 images of each type has been used. In the end I've filtered and combined all those datasets into a final image_data.data file which is used to train the model. I've used YOLOv4(You Only Look Once).
Yolo follows the strategy of Single Shot Detection. It uses a single activation map for prediction of classes and bounding boxes at a time that's why it called "You Only Look Once".

Here pre-trained of yolo-v4 has also been used which can detect more than 80 different objects. Although this model is faster but it doesn't give the reliability of predicting the actual object in a given frame/image. It's a kind of trade-off between accuracy and precision. 
Few samples are given below. 


![myimage1](https://user-images.githubusercontent.com/75817072/118522335-8cf87e80-b759-11eb-93d2-79e36589f9bc.jpg)
![sample 1](https://user-images.githubusercontent.com/75817072/118522391-9eda2180-b759-11eb-9c4d-949bd1bef010.png)
