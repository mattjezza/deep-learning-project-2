This is Udacity Deep Learning Nanodegree Project 2. (This is the old version of Project 2 - hence there are two versions of Project 2 amongst my GitHub repos.) This project uses Convolutional Neural Networks (CNNs) for image recognition.

Environment

There are two alternatives:

Alternative A) Install environment from the yml file. 

Intended to run on Ubuntu Linux 16.04 AWS EC2 p2.xlarge GPU Compute Instance, image Deep Learning AMI with Source Code (CUDA9, Ubuntu)

To install the environment:

Install Miniconda like this: wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh chmod +x Miniconda3-latest-Linux-x86_64.sh ./Miniconda3-latest-Linux-x86_64.sh

Create the environment: conda-env create -f environment-tensorflow-gpu.yml -n tensorflow-gpu

Alternative B) Use the ready-made AWS environment 

This project runs well on the AWS Ubuntu Deep Learning AMI version 10. This separates environments with conda. This project runs in the Python 3.6 Tensorflow environment with CUDA 9. To activate this environment in the AMI use: source activate tensorflow_p36
