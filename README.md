nginx-load-balancer

This is a docker image for easy nginx load balancing applications.
Build the image

    Clone the repository.
    Navigate to it.
    Start building the image using the command:

docker build -t nginx-load-balancer .

Now you should be able to use the load balancer.
Usage:

You can run a docker container using this command:

docker run -d -p 8080:80 nginx-load-balancer host_1 host_2 host_3 etc

Notice: You should specify at least one host, and also all hosts should be reachable. 
