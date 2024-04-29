# Kaakchat 🐔🐣
We have developed a face detection system that not only detects the face but also the facial landmarks with an accepted accuracy.
Our main scheme is to detect faces using segmentation according to skin color and then use an SVM model to eliminate false positives.
Next we apply corner detection to the detected face together with a best fit algorithm to detect the corners of each eye and mouth.
We applied various filters using the detected face and landmarks.

# Sample of filters:
![image](https://github.com/abdelazizSalah/Kaakchat/assets/71516308/1699fe7f-f653-4220-8bbb-8bfed598b659)
![image](https://github.com/abdelazizSalah/Kaakchat/assets/71516308/e545141f-2ea7-41a8-80d5-07da3054db64)
![image](https://github.com/abdelazizSalah/Kaakchat/assets/71516308/433af61f-c992-45a6-9884-8caf3a140bf0)
![image](https://github.com/abdelazizSalah/Kaakchat/assets/71516308/6adaa1f6-da5e-40ea-850f-324ab9d89506)

![image](https://github.com/abdelazizSalah/Kaakchat/assets/71516308/fe4c5cbf-86c9-4b88-994d-0073cd4d1239)

### How to use?
First make sure you have installed all the required libraries on your machine,to install any library use
> pip install < Library-Name > 

To run the filters: navigate to required folder and write the following command
> python ./animatedSnapChatFilters.py.

To navigate to any path
> cd "path"

Used libraries:
* numpy
* pandas
* opencv
* skimage
* sklearn
* mediapipe
* matplotlib
* pickle
* random
* time
* os
