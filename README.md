# A Sentiment Analysis Web App
## Using PyTorch and SageMaker

_Machine Learning Engineer Nanodegree Program | Deployment_

---

This project uses SageMaker to construct a complete machine learning project from end to end. This ia a simple web page which a user can use to enter a movie review. The web page will then send the review off to our deployed model which will predict the sentiment of the entered review. The Pytorch model is trained using the IMDB movie reviews dataset: http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz

**Note:** Running this will require training and deploying a new Sagemaker instance, which can be done using the notebook. The URL of the Sagemaker instance will have to be updated in the linked AWS Lambda function used by the AWS API Gateway reference in the website/index.html file.
