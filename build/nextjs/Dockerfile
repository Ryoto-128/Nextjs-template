FROM node:latest

WORKDIR /usr/src/project

RUN apt update \
    && apt upgrade \
    && apt autoremove \
    && npm update -g npm

# initial exec
# docker-compose run --rm nextjs npx create-next-app@latest <NEXTJS_PROJECT_NAME> --typescript