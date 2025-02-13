# test-server
To start the server:

git clone 
cd test-server
sudo docker build -t hello-world .
sudo docker run -d -p 8080:80 --name hello-container hello-world

Access:
http://localhost:8080

