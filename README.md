# MLflow

MLFLOW_TRACKING_URI=https://dagshub.com/imayank45/MLflow.mlflow \
MLFLOW_TRACKING_USERNAME=imayank45 \
MLFLOW_TRACKING_PASSWORD=1c5f5a5f1b0794cf87c81cd9db7f8e88402a0efa \
python script.py


export MLFLOW_TRACKING_URI=https://dagshub.com/imayank45/MLflow.mlflow

export MLFLOW_TRACKING_USERNAME=imayank45 

export MLFLOW_TRACKING_PASSWORD=1c5f5a5f1b0794cf87c81cd9db7f8e88402a0efa




--------------------------------------------------------------------------------

sudo apt update

sudo apt install python3-pip

sudo pip3 install pipenv

sudo pip3 install virtualenv

mkdir mlflow

cd mlflow

pipenv install mlflow

pipenv install awscli

pipenv install boto3

pipenv shell


## Then set aws credentials
aws configure


#Finally 
mlflow server -h 0.0.0.0 --default-artifact-root s3://mlflow-buck-24

#open Public IPv4 DNS to the port 5000


#set uri in your local terminal and in your code 
export MLFLOW_TRACKING_URI=http://ec2-54-147-36-34.compute-1.amazonaws.com:5000/