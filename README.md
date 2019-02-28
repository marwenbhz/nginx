Nginx: This is a docker image for easy nginx load balancing applications.

1- Clone the repository.

2- Navigate to it.

3- Build the image: Start building the image using the command:
	docker build -t nginx-load-balancer .

4- Run a docker container
	docker run -d -p 8080:80 nginx-load-balancer host_1 etc ... 
    
Notice: You should specify at least one host, and also all hosts should be reachable. 