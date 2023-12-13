FROM python:3.11

# ubuntu update & upgrade
RUN apt-get update -y && apt-get upgrade -y

# git 설치
RUN apt-get install -y git

# 작업 디렉토리 설정
WORKDIR /app

# Git repository clone
RUN git clone https://github.com/yojulab/study_pythons

WORKDIR /app/study_pythons
RUN rm -rf .git

# CMD echo "Hello, World!"

