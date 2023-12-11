# 최신 Python 이미지 사용
# FROM python:3.9
# arm MAX OS
FROM arm64v8/python:3.9


# ubuntu update & upgrade
RUN apt-get update -y && apt-get upgrade -y

# git 설치
RUN apt-get install -y git

# app 디렉토리 생성
RUN mkdir /app

# 작업 디렉토리 설정
WORKDIR /app

# Git repository clone
RUN git clone https://github.com/yojulab/temp_gits
RUN rm -rf .git

CMD echo "Hello, World!"

