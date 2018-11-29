
##   HTML Hello World      
A simple HTML Hellow World application

#### You need to have install git and docker 

	docker build -t <container_name> .
    docker run --name helloworld-html -d -p 8080:80 <container_name>

#### Then http://localhost:8080

### Clean up
	
	docker stop <container_name>
    docker rm <container_name>

	
