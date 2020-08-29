# The Ultimate Free Machine Learning Development Stack
### 4 tools, 0 dollars, everything you'll need

## Introduction

approach 1 - 
Hard enough to keep up with field with job, without lose access to problems to solve and the enterprise development tools ultizied in order to do so.


approach 2 -
The current job environment can be difficult to naviagate, and Data Scientists have not been immune to significant changes this year. However, the field continues to progress. Regardless of your current professional situation, there's no such thing as staying still. If you a machine learing developer or data scientist in the unfortuante position to have lost your job during the pandemic and are not working to improve your skills in these areas, you are absolutely getting passed by.
I've spent the past 3 years helping Data Scientists and Developers navigate the vast land cloud and open source machine learning development tools, and wanted to recommend a workflow that enables end-to-end machine learning with a couple of services, all of which are free, to help keep skills sharp .

## Object Storage 
Object storage is critcal to machine learning development, and provides a place to store training, test, and validation data sets as well as pretrained and fine-tuned models. It's also a huge revenue generator for cloud companies, as AWS' S3 is reported by numerous sources as the most popular service for the multi, multi billion dollar organization, so finding free and unlimited cloud object storage is quite difficult, but not impossible. 

Algorithmia is a serverless Machine Learning deployment platform (more on deploying models below). There are a number of utilites that Algorimthmia provides in order to facilitate the deployment of models, including free object storage. According to their docs, "Algorithmia’s Data Sources make it easy to host your data files on the Algorithmia platform for free, while our Data API makes it a cinch to work with your hosted data." Their Data API is available in Python and has a getFile()/putFile() structure that makes it easy to download and upload training/testing/validataion data sets as well as pretrained and fine-tuned models. Data collections can be made public, shared between teams, or private, and is free to store and access.

## Model Development and Training
There are a number of free, hosted Jupyter enviroments that can help in developing machine learning models. My favorite is Google Colab. Colab provides free access to GPUs, even including NVIDIA V100's if you are lucky, and has very tight and very easy to use integrations with both GitHub and Weights and Biases (more on Weights and Biases later). The free object storage service 

## Hyperparameter Optimization and Monitoring
Hyperparameter Optimzation allows developers to vary aspects of a model in order to tune its training performance. Weights and Biases' Sweeps libary automates hyperparameter optimization to explore a space of possible models. Sweeps provides a number of great features in additon to being a free service, including easy integration . Sweeps as decouples hyperparameter optimization from model training via their central sweep server, so multiple workers can iterated through a search space asynchronously and in parallel.


## Model Libraries and Deployment -- Hugging Face
Model registries, repositories, and libraries 

Algorithmia
Like Weights and Biases, Algorithmia will provide metrics model deployment monitoring


## Wrapup
A demonstration of all these tools working in concert can be found here.For more help AI+
