# How to use (IN DEVELOPMENT)
<code> docker build -t sisnec-front-image:v1 </code> \
<code> docker run -d -p 8000:80 sisnec-front-image:v1 </code> \
Now access localhost:8000/ \
If any problem with port already allocated, change to \
<code> docker run -d -p 8001:80 sisnec-front-image:v1 </code>
