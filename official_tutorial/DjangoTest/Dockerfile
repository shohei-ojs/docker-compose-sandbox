FROM python:2.7
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
# ホストのrequirement.txtをコンテナ/code/へ追加
ADD requirements.txt /code/
RUN pip install -r requirements.txt
ADD . /code/