FROM node:lts-alpine3.19

RUN apk update

WORKDIR /usr/app

RUN yarn global add serverless
RUN yarn global add serverless-offline
RUN yarn add serverless-stage-manager --save-dev
RUN yarn add serverless-python-requirements --save-dev
RUN yarn add serverless-wsgi --save-dev