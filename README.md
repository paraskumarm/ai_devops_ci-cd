# Movie-Recommender-System
This is a hollywood movie recommender system built with Python. I used IMDB 5000 Movie Dataset to built this.
Link to dataset :- https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset

Link to the web application :- https://recommendor-system.herokuapp.com/

I also wrote a blog about this project which help you understand the overall process :- https://www.academyofdatascience.com/Blog_page/blog_3.html

I used Flask web framework in built in Python to put in on web.

# Files Brief
*In the preprocessing.ipynb file the Data Preprocessing part has been done. 

*In the create.py file I created two files for future uses one data.csv and other a numpy matrix.

*The application is run from the main.py file.

## End to End MAchine Learning Project

1. Docker Build checked
2. Github Workflow
3. Iam User In AWS

## Docker Setup In EC2 commands to be Executed

#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = simple-app
