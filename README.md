Step1: Create a new directory
   >> mkdir first-docker
   >> cd first-docker

Step2: Create a file index.html
   >> touch index.html

Step3: Create a dockerfile
   >> touch Dockerfile

Step4: Check if docker is running
   >> docker info

Step5(optional): If docker is not running
   >> sudo systemctl start docker

Step6: Build docker image
  >> docker build -t first-docker

Step7: Run docker conatiner and map it to port 8080 on your local machine to port 80 inside conatiner
  >> docker run -p 8080:80 first-docker

Step8: Access the we browser and navigate to http://localhostip:8080 to see "Hello World" message.
