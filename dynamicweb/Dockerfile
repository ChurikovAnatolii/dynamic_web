FROM python:alpine3.17
ENV APP_ROOT /src
ENV CONFIG_ROOT /config
WORKDIR ${APP_ROOT}
COPY requirements.txt ${CONFIG_ROOT}/requirements.txt 
RUN pip install -r ${CONFIG_ROOT}/requirements.txt 
COPY . ${APP_ROOT}