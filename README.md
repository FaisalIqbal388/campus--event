# campus--event
A static website built as part of DevOps Assignment 02.

## Build Instructions

### Install Parcel
npm install -g parcel

### Run locally
parcel src/index.html

### Build
parcel build src/index.html

### Docker Build
docker build -t username/campus-events:v1 .

### Run Docker Container
docker run -p 8080:1234 username/campus-events:v1

