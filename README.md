# Enhanced-Drowsiness-Detection-using-Deep-Learning
Driver's drowsiness is monitored through the deep learning model called CNN - Convolutional Neural Network
This project aims to develop an efficient model to monitor the driver's drowsiness and alert according to their change facial features

# Abstract
  Road safety is a significant public health issue, and a cause of injuries and fatalities. According to a report by the 
Ministry of Road Transport and Highways Transport Research Wing, road accidents claimed 1,53,972 lives and harmed 3,84,448 people 
in 2021. Unfortunately, the age range that is most severely hit by road accidents is 18 to 45 years old, which accounts for almost
67 percent of all accidental deaths.
	A crucial problem that causes numerous car accidents annually is driver fatigue. Due to the incapacity of a driver to halt or swerve to
prevent or minimise the impact, accidents caused by driver sleepiness are much more inclined to result in fatalities or severe accidents. Fatigue 
lowers attentiveness, alertness, and concentration, which impairs the accomplishment of tasks requiring attention such as driving.

# Technologies used
![image](https://github.com/jerutae/Enhanced-Drowsiness-Detection-using-Deep-Learning/assets/91835091/17a83d38-393a-4067-bbe2-d1e85a59ac5f)

# Viola Jones - Machine learning
The way that the Viola-Jones algorithm actually works is through the execution of four main steps: 
•	Haar-like Features
•	Integral Image
•	Adaboost Training
•	Attentional cascade (Viola & Jones, 2001)
	The first step, Haar-like features, are a set of rectangular digital image features that break up the image into multiple sets of “two adjacent rectangles located at any scale and position within an image” (Ephraim, Himmelman, & Siddiqi, 2009). These rectangles are then applied to the image that has been opened within the program. 
	The Haar-like features are applied to the image. As demonstrated, there is first one main region that is being examined, the area from the forehead to the eyes. This region is selected given that the region of the eyes is darker than the region of the nose and cheeks so if the Haar-like features can be matched then the image can go to the next step with the Adaboost training. What Adaboost training does here is to better define the region from the eyes to the cheeks. The way it does this is by employing a learning algorithm that is used to “teach” the program to look over a set of possible areas and then choose the areas with the “best” features resulting in a reduced image with more defined regions (Viola & Jones, 2001). 
	After the features are selected they are put through the Adaboost learning algorithm to narrow down the number of features that are looked at and then passed on to the cascading stage. In more broad terms, the Adaboost training makes sure that the region that is being examined is as precise as possible in order to help obtain the best accuracy. The last step is the attentional cascade. During this step, the program is trying, again, to maintain the smallest error percentage rate as possible. In order to do this, the attentional cascade’s main focus is to eliminate as many false positives as possible. In practice, for instance, the initial steps identify an object, such as a bush, as a potential face then the attentional cascade takes the bush and discards it as a viable option. 
	The Viola-Jones method, although it has a high accuracy rate, does come at the price of longer computation time. In contrast, CNNs have addressed computation time concerns and have successfully improved upon them.
 
# Working of CNN - Deep learning
In this project, in order to reduce the accidents that are caused by driver’s drowsiness or sleepiness, a driver drowsiness detection system is developed with the help of deep learning techniques. Initially Dataset contains images of both the closed and open eyes of several persons were collected to train the model. Before the training of model takes place, the images are preprocessed so that the dataset can be directly applied to the deep learning algorithm for further process. After preprocessing, our model has been trained. A convolutional neural network (CNN or convnet) is a subset of machine learning. It is one of the various types of artificial neural networks which are used for different applications and data types. A CNN is a kind of network architecture for deep learning algorithms and is specifically used for image recognition and tasks that involve the processing of pixel data. Our system will be installed in automobiles such as cars, buses etc. Our system continuously monitors the eyes of the driver. Whenever the user feels drowsy (He / She feels sleepy by closing the eyes), our system alerts the driver with a beep sound as its primary response. The Alarm goes on increasing when the driver doesn’t wakeup. Then our system is making a phone call to the driver’s emergency contact person or relatives to inform that the person feels drowsy or sleeping while driving along with the driver’s coordinates. Thus, this system effectively reduces the risk of road accidents that are caused by driver’s carelessness.

# Module description
•	Data Collection

•	Building and training a CNN Model

•	Face and Eye Detection

•	Drowsiness Detection

•	Alert System

# System specification
Software Used: 

	Operating System	:	Windows 7 / 8/ 10

	Language		:	Python

	IDE			:	Anaconda, Notebook

Hardware Used: 

	Processor		:	Ryzen5

	Ram			:	16 GB

	Hard Disk		:	120 GB


# RESULTS OF THE WORK

# Epochs vs Loss Graph

![image](https://github.com/jerutae/Enhanced-Drowsiness-Detection-using-Deep-Learning/assets/91835091/94b1572f-a82b-46ca-9405-c4db0ef6e720)

# Epochs vs Accuracy Graph

![image](https://github.com/jerutae/Enhanced-Drowsiness-Detection-using-Deep-Learning/assets/91835091/ae7bd151-64d0-4c21-987c-e19b05016cb1)


# Confusion Matrix

![image](https://github.com/jerutae/Enhanced-Drowsiness-Detection-using-Deep-Learning/assets/91835091/47f33610-037b-4634-98be-7144d1dd07f7)


# Classification Report

![image](https://github.com/jerutae/Enhanced-Drowsiness-Detection-using-Deep-Learning/assets/91835091/3d3a2d7c-8f4a-41fa-91d6-bf330f64dfd7)


