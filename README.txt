//to build a nestJs image
sudo docker build -t aws-nest-app .

//to run the container 
sudo docker run -p 8000:8000 aws-nest-app 

//to see the folder structure inside the container
sudo docker exec -it 757d3750a692 /bin/sh

