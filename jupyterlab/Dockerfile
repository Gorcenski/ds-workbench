ARG BASE_CONTAINER=jupyter/all-spark-notebook
FROM $BASE_CONTAINER

USER root

RUN jupyter labextension install jupyterlab-s3-browser && \
    pip install jupyterlab-s3-browser && \
    jupyter serverextension enable --py jupyterlab_s3_browser && \
    jupyter lab build && \
    jupyter lab clean
