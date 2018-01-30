
create 'Dockerfile'
docker build . -t devops-hellonode:1
docker run -it -p 8000:8000 devops-hellonode:1