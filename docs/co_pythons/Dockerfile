FROM python:3.11

# 작업 디렉토리 설정
WORKDIR /app

# Git repository clone
RUN git clone -b complets https://github.com/gocolab/co_pythons.git co_pythons_complets

RUN git clone -b debugs https://github.com/gocolab/co_pythons.git

WORKDIR /app/co_pythons

# RUN pip install --no-cache-dir -r ./requirements.txt

RUN rm -rf .git

