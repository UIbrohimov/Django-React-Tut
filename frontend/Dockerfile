FROM node:14.4.0-alpine3.10
USER root
WORKDIR /frontend
COPY . /frontend
ARG API_URL
ENV REACT_APP_HOST_IP_ADDRESS $API_URL
RUN /usr/local/bin/yarn add antd redux axios react-redux redux-thunk redux-logger
RUN /usr/local/bin/yarn build