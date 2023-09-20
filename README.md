# Problem
The detection of people holding weapons, especially small ones, in a crowded place is nearly impossible using traditional methods.

# Solution
Devel a model that can detect various types of weapons in real time .

# Project Description
We used the open image v7 dataset and acquired three classes: knives, handguns, and mobile phones we will have more classes in the future. We trained our model using YOLOv8. We then used Roboflow for splitting, preprocessing, augmenting, and deploying our data.

# Splitting
We split our data into three categories:

Training set: 75%
Validation set: 15%
Testing set: 10%

# Preprocessing
We preprocessed our data by resizing and auto-orienting the images.

# Augmentation
We used bluring and flipping for augmentation.

# Training
We initially trained our model using 25 epochs, and the accuracy was around 79%. We then trained it again using 100 epochs, and the accuracy increased to 88.8%.

# Deployment
We chose Roboflow to deploy our data as it provides an interface in the most professional and user-friendly way. The Roboflow interface gave us the opportunity to visualize our model using a webcam, YouTube videos, and images.

# Features
Our model can detect various types of weapons, including knives and guns, in real-time.

# Explore
 
![Screenshot (232)](https://github.com/WeaponDetection/Weapon-Detection/assets/145555418/b818752e-a15c-4f27-8b90-6a32d24e0f7d)








