# MLflow-Basic-Operation

## For Dagshub:

MLFLOW_TRACKING_URI=https://dagshub.com/Chamindu77/MLflow-Basic-Operation.mlflow \
MLFLOW_TRACKING_USERNAME=Chamindu77 \
MLFLOW_TRACKING_PASSWORD=c24513b61e51f0adedbfcd6d4702a8a8cfd2c4a8 \
python script.py


...bash

export MLFLOW_TRACKING_URI=https://dagshub.com/Chamindu77/MLflow-Basic-Operation.mlflow

export MLFLOW_TRACKING_USERNAME=Chamindu77

export MLFLOW_TRACKING_PASSWORD=c24513b61e51f0adedbfcd6d4702a8a8cfd2c4a8

...

mlflow server -h 0.0.0.0 --default-artifact-root s3://mlflow-buc23

bucket s3 : S3/mlflow-buc23

export MLFLOW_TRACKING_URI=http://ec2-13-49-226-96.eu-north-1.compute.amazonaws.com:5000/



