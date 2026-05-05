docker cp index.html a5ffe123e5b7://usr/share/nginx/html # Copy index.html to the container's /usr/share/nginx/html directory.
docker commit -m "index.html Docker is FUN! " a5ffe123e5b7 # Commit the changes to a new Docker image.
docker pull
docker build -t my-nginx . # Build a new Docker image with the name "my-nginx" based on the current directory.
docker images # List all Docker images.
docker run 
docker ps
docker rm
docker rmi
docker cp
docker commitd