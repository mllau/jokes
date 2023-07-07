# Jokes App Local Deployment

This repository contains a Flask app and an Azure DevOps pipeline configuration to automate the deployment process. Follow the instructions below to run the Flask app locally.

## Prerequisites
The app can be deployed using a docker image or by running the python script.
- Docker
- Python 3.x 

### Getting Started with Python

#### 1. Clone this repository to your local machine:

git clone https://github.com/ml-oak/ml-oak.git

#### 2. Navigate to the cloned repository:

cd ml-oak/

#### 4. Install the required dependencies using pip:

pip3 install -r requirements.txt
python3 jokes.py

### Docker

#### 1. Clone this repository to your local machine:

git clone https://github.com/ml-oak/ml-oak.git

#### 2. Navigate to the cloned repository:

cd ml-oak/

#### 4. Run the following command to load the Docker image from the tar file:

docker load -i jokes-app.tar

This command loads the Docker image from the jokes-app.tar file.
Once the image is loaded, you can use it to run containers on the target machine using the _docker run_ command

