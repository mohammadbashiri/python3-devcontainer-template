FROM mcr.microsoft.com/devcontainers/python:1-3.11-bullseye

# install the essentials
COPY .devcontainer/dev_requirements.txt /usr/src
RUN pip install -r /usr/src/dev_requirements.txt

# install the user-specific packages
COPY requirements.txt /usr/src
RUN pip install -r /usr/src/requirements.txt
