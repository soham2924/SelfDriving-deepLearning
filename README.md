<h1 align='center'>Self Driving Car</h1>
<br>
Project Autopilot helps in getting the angle of steering rotation in a self-driving car. This project is inspired by <b>NVIDIA End to End Learning for Self-Driving Cars</b> and data is gathered from <b>Udacity's Behavioral Cloning repository</b>. It is written in Python and leveraged Keras for Deep Learning functions. 
<br>
The End to End Learning for Self-Driving Cars research paper can be found in the below table.
This repository uses Convolutional Neural Networks to predict steering angle according to the road. 
<br>
##  🗃 Dataset 

|[Dataset](https://github.com/SullyChen/driving-datasets)|

## Note: 

💡 **I have made implementation code `AutopilotApp_V2.py` private to avoid misuse, feel free to contact me. ✌**

## 🗃 Dataset

Download the dataset from (https://github.com/SullyChen/driving-datasets) and extract it into the repository folder.
Data format is as follows: `filename.jpg angle,year-mm-dd hr:min:sec:millisec`


##3 🏃‍♂️ How to Run the code
Step-1: Run `LoadData_V2.py`. This will flow through the dataset and generates `labels` and `features` pickle files.<br>
Step-2: After generating two files, run `Train_pilot.py` which will load pickle files. After this, the training process begins.<br>
Step-3: For testing it on the video, run `AutopilotApp_V2.py`<br>
**I have made `AutopilotApp_V2.py` private to avoid misuse, feel free to contact me @v.snehith999@gmail.com for complete directory ✌**


### 📰 Generic Description
An autonomous car is a vehicle that is capable of sensing its environment and navigating without human input. Autonomous cars combine a variety of techniques to perceive their surroundings, including radar, laser light, GPS, odometry, and computer vision. Advanced control systems interpret sensory information to identify appropriate navigation paths, as well as obstacles and relevant signage.


### 📩 Packages Installation 
Use the `pip install -r requirements.txt` command to install packages in one go.
You can also use conda to get rid of any version problems.

If you face any problem, kindly raise an issue

### 🔗 References:
 - Mariusz Bojarski, Davide Del Testa, Daniel Dworakowski, Bernhard Firner, Beat Flepp, Prasoon Goyal, Lawrence D. Jackel, Mathew Monfort, Urs Muller, Jiakai Zhang, Xin Zhang, Jake Zhao, Karol Zieba. [End to End Learning for Self-Driving Cars](https://arxiv.org/abs/1604.07316)
 - [Behavioral Cloning Project](https://github.com/udacity/CarND-Behavioral-Cloning-P3) 
 - This implementation also took a lot of inspiration from the Sully Chen github repository: https://github.com/SullyChen/Autopilot-TensorFlow  



#   S e l f D r i v i n g - d e e p L e a r n i n g 
 
 
