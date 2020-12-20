FROM python:3.7.9-slim

RUN pip install mlflow psycopg2-binary boto3
EXPOSE 5000

# CMD mlflow server --host 0.0.0.0 --port 5000 --backend-store-uri=postgresql://mlflow:mlflow@127.0.0.1:5432/mlflow --default-artifact-root=/data
