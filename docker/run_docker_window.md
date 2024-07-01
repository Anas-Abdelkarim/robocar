## to build the image 
docker build -f docker/Dockerfile -t ubix/robocar .

## to run the the container
docker run -it --name robocar --rm   -e DISPLAY=host.docker.internal:0.0   -v ${PWD}:/host   ubix/robocar 

%-v "D:\iso:/data"

## to link the bash
docker exec -it <container-id>  bash  
docker exec -it bd887197ddd0  bash  