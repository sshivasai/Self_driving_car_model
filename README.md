# Self_driving_car_model
Designing a small prototype for self driving car.  Changing steeering angles with respect to road.  Using car dash cam images and sterring images    Dataset used  from SullyChen----  https://github.com/SullyChen/Autopilot-TensorFlow

![5b2240b5-6115-49ed-be59-354d1a619a39](https://user-images.githubusercontent.com/64718250/142967466-5873243e-07e7-45c0-9bbc-79ffa70760da.png)
![11b26e5e-a0d6-4713-8487-82cfdb7b5e44](https://user-images.githubusercontent.com/64718250/142967730-f222412a-dd7a-4442-bf4b-740d1824b0bf.png)

# REFERENCE
https://developer.nvidia.com/blog/deep-learning-self-driving-cars/

# From above plot we can say that there are more datapoints with steering angle of 0. Probably the car is travellling more on a straight highway roads.

![download](https://user-images.githubusercontent.com/64718250/142979400-98ea8f36-ad3c-4706-b94c-536377c5f063.png)
# The train and test datasplits are almost similar


## using only cnn

image---> predict angle (end to end model )



## can also use 

image -------> cnn--------> vector representation----->LSTM----->OUTPUT
LSTM - many to many relation
![20211231_220750](https://user-images.githubusercontent.com/64718250/147832740-30407f9e-88c2-4ced-80f6-7b0b6dc3061c.jpg)
