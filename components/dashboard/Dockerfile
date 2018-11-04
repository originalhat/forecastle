FROM node:latest
ADD . /app
WORKDIR /app
RUN yarn install
CMD NODE_ENV=development yarn webpack --mode=development --config config/webpack.config.dev.js --output-path=/tmp/public --watch

