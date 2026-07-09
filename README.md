docker build -t nginx.site2 .


docker run -d -p 8080:80 nginx.site1



kind get clusters

kind delete cluster --name infra-lab

