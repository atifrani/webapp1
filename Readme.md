# Clone project:

https://github.com/atifrani/webapp.git


# Build Docker Image

docker rmi webapp_img

cd webapp

docker build -t webapp_img .

# Run Docker Container

 docker run --name webapp_cnt -d -p 8080:80 webapp_img

 # Test webapp

 http://localhost:8080/
