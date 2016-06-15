# docker-tutorial-mobydock

this repo is a part of http://www.jaynarol.com/understand-docker/

docker run --name hellomobydock -v ~/web:/usr/share/nginx/html:ro -v ~/web/nginx.conf:/etc/nginx/nginx.conf:ro -p 80:80 -d nginx:1.10
