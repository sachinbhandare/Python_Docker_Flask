
1. Create a Docker file

Refer the Dockerfile in the current directory

2. Build a docker image
  docker build -t python-test .

3. 
 docker images 

4. Run in interactive mode to test
docker run -it --name python-container -p 3200:3200 python-test

5. Check the docker all processes
docker ps -a 

6. Find the process for python-container

docker rm 86eda9fcd43e

6. Run the docker image in daemon mode
docker run -d --name python-container -p 3200:3200 python-test

