docker build -t nginx.site2 .


docker run -d -p 8080:80 --name nginx.site2 site2



kind get clusters

kind delete cluster --name infra-lab

