# Amazon Rekognition Face Matching
This demo solution demonstrates how to test the accuracy of Amazon Rekognition. The two main study focuses are: identical twins and facial variations. In the identical twins study, we tested if Amazon Rekognition recognize the twin sister with similar confidence scores as her twin. In the facial variations study, we tested if Amazon Rekognition recognize individuals with similar confidence scores when they have minor variations on their faces. 

## Analysis Workflow


## Architecture Overview


## Data Collection


## Results

## Get Started - Guidance for the code
First of all, we create an s3 bucket on AWS. We need to make sure that we make the bucket public. 
(insert picture)

Secondly, we push all of our images into the bucket. Remeber, the images should also be made public. As you can see, we have images of the twin sisters in the bucket, you can put images that you want to work with in your s3. 
(insert picture)

Then we set up the IAM role. After clicking on the name of your Sagemaker notebook, you will be able to set the IAM role as ARN. 
(insert picture)

We need to go to the "permissions" tab and make sure that we have full access to Amazon Rekognition. 
(insert picture) 

