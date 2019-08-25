# Update:  
Addition of Dropout, Batch Normalization and other optimization techniques are in process. 
You Tube link will be soon available.

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
This project is using custom CNN architecture. One can use other architectures like ResNet. But, for the exploratory reason and low GPUs power, we prefer to use smaller and simpler CNN architecture. We are also not using pre trained weights. Though, it is a good practice to do Transfer Learning, but for learning purpose we are working out the code from scratch.

(With more updates to increase accuracy, we might add more layers of Batch Normalization.)

# Datasets:
We are using Kitti Dataset. You can download it from here: http://www.cvlibs.net/datasets/kitti/. It is an old dataset and might not be the first choice of researchers. But, low computational power constraints us to go for this. One can use other big dataset like COCO, Berkley, ImageNet or Google.

# Hyper parameter Tuning:
Using Comet.ML for visualizing hyper parameters
 
# Suggestions:
1) Do not work directly with all the images in the dataset. Take a small sample of 100-500 images, work around the code and then start scaling it

# Feedback:
Feedback and suggestions are most welcomed !!
