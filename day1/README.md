# NVIDIA GPU Bootcamp

KTH September 2019


## Day 1 - 24 Sep 2019
Paul Graham : pgraham@nvidia.com

Create Accounts on linuxacademy.com, developer.nvidia.com course.nvidia.com


### Session 1: Introduction to GPU Computing
1. What to expect? - Overview on  GPU Stack, GPU Architecture, ways to GPU computing
2. Full Stack Optimization  
   Plot of Relative performance vs time (with Moores law and GPU accelerated Growth), 2013- Accelerated server with Fermi, 2019 - Accelerated Server with Volta
3. Nvidia Universal Acceleration Platform - Single platform drives utilization and productivity.
   

Coustomer Usecases (Consumer Internet(Speech, Translate, Recommender), Industrial Applications, Scientific Applications), 
-------------------------------------------------------------------------------------------------------------------------
Apps and Frameworks (Python RAPIDS, TEnsorflow, pytorch, mxnet, chainer, onnx, Amber NAMD ANSYS, SIMULA), 
---------------------------------------------------------------------------------------------------------
Nvidia DSK & Libraries (ML/Analytics, Deep Learning, HPC), 
----------------------------------------------------------
CUDA
----

Tesla GPUs & Systems (Tesla GPU, Virtual GPU, Nvidia DGX Family, Nvidia HGX, System OEM, Cloud)
-----------------------------------------------------------------------------------------------


4. How GPU Acceleration Works

GPU `<--- Compute intensive Functions (5% of Code)` AppCode 

CPU- Optimized for serial Tasks
GPU Accelerator - Optimized for parallel tasks
CPU is a latency reducing Architecutre
5. CPU Strenghts
   1. Very large main memory
   2. Very fast clock speed

6. GPU Strenghts
   1. High bandwidth main memory
   2. Significantly more compute resources
   3. Latency tolerant via parallelism
   4. High throughput
   5. High performance/watt

7. GPU weakness
   1. Relatively low memory capacity


8. How to start with GPUS
   1. Applications
   2. Libraries 0 Easy to use, most performance; Compiler Directives (OpenACC); Programming Languages (CUDA)

9. GPU-Accelerated applications
   Life Sciences, Manufacturing, Physics, Oil and Gas

10. GPU Accelerated Libraries
   1. Deep Learning =cuDNN
   2. 

11. What is OpenACC? - Programming model for an easy onramp to GPUs

12. Nvidia Deep Learning Software Stack
   1. Training (Caffe2, Chainer, mxnet, tensorflow, pytorch, theano, microsoft cognitive toolkit)
   2. Inference (Data Center, TensorRT, Embedded, JETPACK SDK, Automotive, DriveWorks SDK)
   3. Nvidia Deep Learning SDK and Cuda (cuDNN, NCCL, cuBLAS, TensorRT, cuSPARSE, DeepStreamDSK)
13. RAPIDS- Open GPU Data Science (Software Stack Python)
   US Census dataset (predict income): 45k rows, 10k cols, H2O.ai ML- Generalized Linear Modeling

14. Challendes Utilizing AI & HPC Software
   1. Installation - Complex, time consuming and error prone
   2. Optimization - Requires expertise to optimize framework
   3. Maintenance
   4. Productivity

15. NGC Software Hub - GPU Optimized Software Hub


### Introduction to OpenAcc
https://app.linuxacademy.com/hands-on-labs/bddbc6db-9bb1-4b9d-96ed-4cf85e37e632



### Lecture 2 Outline : 

1. CPU and GPU Memories
2. Cuda Unified Memory




