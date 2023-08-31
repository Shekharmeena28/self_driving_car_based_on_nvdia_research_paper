# Self driving car based on nvdia research paper

# project demo video

[Watch the Project demo Video](https://drive.google.com/file/d/1av4VbQ4hzJYcghzP4i9YWE4B-5gK9ScY/view?usp=sharing)

![Image Alt Text](car.png)
![Image Alt Text](carr.jpg)


- Based on the nvidia research paper 'End to End Learning for Self-Driving Cars' this project is implemented as described by the nvdia, here udacity car simulater was used to collect the data(images, steering angle, throttle, speed up and down) this data is saved in the csv file.
- As we link images to steering angle we train the model but before this we performed various preprocessing techniques on the given images
- Then we train the model on the given dataset
- after words we created an app to link the udacity car to the trained data so that it can drive itself


## STEP 01: 
Clone the repository
```bash
https://github.com/Shekharmeena28/self_driving_car_based_on_nvdia_research_paper.git
```

## STEP 02: 
Create an environment & activate
```bash
conda create -n sdcar python=3.7 -y
```
# STEP 03: 
Install the requirements 
```bash
pip install -r requirements.txt
```

# STEP 04: 
Go to the issue.txt copy and paste in your command prompt first copy the first command and execute it and then paste second command execute it, do not execute both commands simultaneously

# STEP 05: 
open the udacity car simulator and click on play then wait

# STEP 06: 
execute the drive.py
```bash
python drive.py
```
# STEP 07: 
click on autnomus mode in udacity car simulator voila u are good to good, car will drive automatically

