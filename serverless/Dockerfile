FROM node:lts-alpine3.19

RUN apk update

WORKDIR /usr/app

RUN yarn global add serverless
RUN yarn global add serverless-offline
RUN serverless plugin install -n serverless-stage-manager
RUN serverless plugin install -n serverless-python-requirements
RUN serverless plugin install -n serverless-wsgi