# How to use
docker build -t sisnec-front-image:v1 \
docker run -d -p 8000:80 sisnec-front-image:v1 \
Now access localhost:8000/ \
If any problem with port already allocated, change to docker run -d -p 8001:80 sisnec-front-image:v1
