FROM jupyter/scipy-notebook

WORKDIR /app
COPY requirements.txt /app

RUN pip install --upgrade pip
RUN pip install -r requirements.txt