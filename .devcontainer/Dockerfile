FROM node:latest
RUN apt update && \
    apt upgrade && \
    apt install g++  && \
    apt clean && \
    yarn global add gatsby-cli && \
    npm install 
EXPOSE 8000 9000
