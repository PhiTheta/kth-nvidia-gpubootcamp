# Day 2
AI involves an agent and that differs from ML  
Mapping domain x to domain Y : Deep Learning  

ML Tribes - Boosters, Symbolists, Evolutionists, Connectionists, Bayesians, Analogists  
Image Similarity :  Eucledean distance, cosine distance (is Eucleadean distance for vectors)  

- Linear Map, Composition of linear maps is linear map
5x10 matrix = A  
5x1 matrix  = B  
Chain rule of gradients
Trained neural networks are called models.  
Core Tenet of Deep Learning : forward propagate an image through the network, generate an output, assess the loss, backward propagate the loss back through the network to update weights.


## Codes & Links

1. KTH_CV2.0_AMBASSADOR_SE19
2. https://courses.nvidia.com/dli-event
3. http://ec2-3-19-188-58.us-east-2.compute.amazonaws.com/digits/
4. http://ec2-3-19-188-58.us-east-2.compute.amazonaws.com/rYrJb7Fy/jobs/20171102-180326-8901
5. https://developer.nvidia.com/digits
6. https://latex.codecogs.com/
7. https://www.youtube.com/watch?v=Ilg3gGewQ5U
8. https://docs.google.com/document/d/1A8r1Shh0ssiRzrxNcraK7PJ_NUFay--EX1aBovpVMKU/edit?usp=sharing  (THis is updated regularly)
9. https://ngc.nvidia.com/

## From Slides



Throughout this course, you have been working on fully configured GPU-accelerated environments. Once you complete the assessment, you can return to this page to see how to create your own. 


1. Use the NVIDIA AMI on AWS ( 10 minutes): [https://github.com/NVIDIA/nvidia-docker/wiki/Deploy-on-Amazon-EC2]
2. Get started with nvidia-docker (5 minutes): [https://github.com/NVIDIA/nvidia-docker]
3. Get started with the NVIDIA DIGITS container ( 5 minutes): [https://github.com/NVIDIA/nvidia-docker/wiki/DIGITS] 


## Project

After you set up your own environment, you can take on any project you want. However, if you're at a loss for ideas, here's one you can attempt after completing the assessment on the next page:

Instead of solving problems for dogs, see what you can do for people. 

First, download a dataset:

1. Download a dataset with images of people by selecting "download" from ImageNet. Note: You will need to request access and await an approval email. 
2. Download a second (or third) dataset you would like to compare "people" with. 
3. Next, use the tools and workflow that you just practiced. Try to:
4. Train an image classification model to successfully classify people from other classes.
5. Deploy your model into a Jupyter notebook to create a useful output
6. Increase baseline performance in training and deployment using data, hyperparameter, architecture, transfer-learning techniques and tools like TensorRT
7. Use your model to start building a more personalized dataset






