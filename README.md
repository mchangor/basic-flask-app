#Basic dockerized python flask app

## Instructions

### To build Docker: 
docker build -f Dockerfile -t flaskapp .

### To run docker image at port 5000:
docker run -p 5000:5000 flaskapp

### The app will run at 
localhost:5000/