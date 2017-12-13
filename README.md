# MuleHelloWorld_Docker

Maven based mule project has been dockerized and tested via postman.

Running the project :

Go to the folder where pom.xml is present and  run the following commands:-

a) mvn clean package

b) docker build -t muledocker .

c) docker run -p 80:8081 --name muledocker muledocker


Test url : http://localhost:80/dockerhelloworld
