# Amazon Rekognition Extreme Cases Testing
This project demonstrates how to test the accuracy of Amazon Rekognition under extreme cases. The two main study focuses are: 1) identical twins and 2) facial variations. In the identical twins study, we tested if Amazon Rekognition recognize the twin sister with similar confidence scores as her twin. In the facial variations study, we tested if Amazon Rekognition recognize individuals with similar confidence scores when they have minor variations on their faces. 

## Architecture Overview

The architecture diagram below provides an overview of this project.

![Architecture Diagram](architecture_diagram.png)

We first upload the source image and target image to an Amazon Simple Storage Service (S3) web bucket. The S3 bucket is then changed to public access. The AWS Rekognition is being accessed by setting up AWS IAM role. With the S3 bucket and Amazon Rekognition all set up, we can use Rekognition to test the source and target images uploaded to the S3 bucket. We focused on the FaceMatch function for finding similarities and the FaceNotMatch funciton for finding differences. From the results, we can perform further machine testing or machine learning.

## Data Collection

Our data are collected from our friends and ourselves. 

## Results

## Get Started - Guidance for the code
