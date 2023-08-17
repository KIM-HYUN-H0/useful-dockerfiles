FROM python:3.9.17-slim
WORKDIR /app
RUN apt update
RUN apt install -y git docker.io curl
RUN pip3 install awscli
#docker build -f Dockerfile --tag awscli-dind
