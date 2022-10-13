# Demodock
check version
docker --version
2) Do cloning of project
git clone https://github.com/Anuj1990/Docker.git

3)Open the folder of Project
cd Docker

4) start Docker service
sudo systemctl start docker

5) build docker image
here phpcode is image name
sudo docker build -t phpcode . -f Dockerfile

6) To get list of all images 
sudo docker images

7) run project
 sudo docker run imagename
 
How to push image in dokerhub
1) create account in docker hub
2)  Open terminal
3) docker login 
give credentials
4) give tag to image

docker tag phpcode usernameofdocker/phpcode

5) docker push usernameofdocker/phpcode






6) run image means run complete code
docker run -d --name phpcode -p 80:80 phpcode
