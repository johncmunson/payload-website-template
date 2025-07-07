FROM node:18-alpine

RUN apk add --no-cache git bash

# Mark the project directory as safe for Git operations inside the container.
# This avoids "detected dubious ownership" errors due to UID mismatches between host and container.
RUN git config --global --add safe.directory /home/node/app
