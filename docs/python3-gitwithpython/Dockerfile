# 최신 Python 이미지 사용
FROM python:latest

# ubuntu update & upgrade
RUN apt-get update -y && apt-get upgrade -y

# git 설치
RUN apt-get install -y git curl

# app 디렉토리 생성
RUN mkdir /app

# 작업 디렉토리 설정
WORKDIR /app

# Git repository clone
RUN git clone https://github.com/yojulab/temp_gits
RUN rm -rf .git

# install vscode extension
RUN curl -fsSL https://code-server.dev/install.sh | sh

CMD echo "Hello, World!"

