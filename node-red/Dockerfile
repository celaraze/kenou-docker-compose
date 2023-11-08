FROM node:latest

RUN export https_proxy=http://192.168.1.102:7890
RUN git clone https://github.com/node-red/node-red.git
WORKDIR /node-red
RUN npm install
RUN npm run build