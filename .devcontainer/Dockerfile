FROM python:3.8.7-slim-buster

RUN apt update \
    && apt install -y curl wget gosu jq unzip libgomp1

RUN pip install -U pip \
    && pip install \
    numpy \
    scikit-learn \
    pandas \
    lightgbm \
    ipython \
    jupyter \
    econml \
    witwidget \
    matplotlib \
    seaborn \
    plotly \
    flake8 \
    black

RUN apt install -y g++ && pip install shap