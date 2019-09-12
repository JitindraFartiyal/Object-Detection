# Update:  
- Production code is work in progress and can be checked into going to branch object-detection-v2
- Added Dataset Directory structure for creating multiple folders with ranging from micro - mini - small - medium - large data. We have added here micro and mini folder only. You can easily switch folders from changing folder path from main function
- Dropout layer, batch normalization layer is added. We added 2 more Conv layer (subject to behaviour of loss) Currently, we are using Adam optimizer. 
- Code has been cleaned and became more dynamic. You can change the number of classes you want to classify, change the grid size,      number of bounding box from main function.
- Added other logging facilities, like steps completed, checking previous epoch loss and current loss to compare.
- Added Suggestion in README.md

# Intro:
With the advent of Alex Krizhevsky paper in 2012 for ImageNet challenge, the domain of Deep Learning has got much attention needed to it.
Computer Vision is one of its applications, which we are going to review in this repository.
Computer Vision is an area which has been developing since many years, but only now, its significance has came into light. Thanks to many researchers research papers specially Alex Krizhevsky and Yaan LeCun and the GPUs and TPUs which has reduced computational time complexity exponentially.

In this repository, we will create a program to detect cars in a video for the purpose of self driving cars. There are many algorithms to achieve this task starting from R-CNN, Fast R-CNN, Faster R-CNN, SSD. But,for this we are going to use YOLOv1 algorithm developed in 2016. Link to the paper - https://arxiv.org/abs/1506.02640. 
YOLOv1 has many shortcomings, which has been improved in later version of YOLO. Link to the paper - https://arxiv.org/abs/1612.08242 https://arxiv.org/abs/1904.04620


# Platform: 
We are using Google Colab for running our code. It provides decent GPU and TPU support.

# Language/Libraries:
We are using Python framework - Pytorch  for writing our code. Basic computational and data manipulation libraries are used like NumPy, SciPy, Pandas, Matplotlib, torchvision. It is not advised to go through all these libraries and then start coding. Best apporach is to start coding and understand it parallelly.

# Architecture:
We have used Resnet50 for our CNN Architecture

# Datasets:
We are using Kitti Dataset. You can download it from here: http://www.cvlibs.net/datasets/kitti/. It is an old dataset and might not be the first choice of researchers. But, low computational power constraints us to go for this. One can use other big dataset like COCO, Berkley, ImageNet or Google.

# Hyper parameter Tuning:
Using Comet.ML for visualizing hyper parameters. We also have used Cylcial Learning Rate https://arxiv.org/abs/1506.01186
 
# Feedback:
Feedback and suggestions are most welcomed !!
