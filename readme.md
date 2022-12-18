Emotion Detector

This model is trained too detect neutral, happy, sad, and angry faces.

This image shows an example of a happy emotion being detected
[Imgur](https://i.imgur.com/FaSwGdQ.png)

## The Algorithm

I trained this model with Jupyter and a live camera with a variety of photos of people with different emotions. Depending on what face you make, it will detect what kind of emotion you are feeling. 

## Running this project

Once you download this model, you can use it in Linux, Python, or C++ to detect emotions of people in images or videos. 
For example, for detectnet it would be:
# Linux
detectnet --network=my_model.pth (image.jpg) (image test output.jpg)
# C++
$ ./detectnet --network=my_model.pth (image.jpg) (image test output.jpg)     
# Python
$ ./detectnet.py --network=my_model.pth (image.jpg) (image test output.jpg)  


You will need to download imagenet, detectnet, or any other object to run this model. 

https://youtu.be/klwQ0m59lng
