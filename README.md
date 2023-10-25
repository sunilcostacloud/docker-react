wsl

wsl -l -v

docker --version

///////////////////////////////
docker ps

docker stop ecommerce-container (container name or id)

docker rm ecommerce-container

docker rmi ecommerce-image

/////////////////////////////

////////////////////////////////

docker build -t ecommerce-image .

docker image ls

docker run --rm --name ecommerce-container -e CHOKIDAR_USEPOLLING=true -d -p 3000:3000 -v $(pwd):/app ecommerce-image

docker logs ecommerce-container (container name or id)

docker ps
