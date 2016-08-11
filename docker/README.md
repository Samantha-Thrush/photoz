Run docker with:

sudo docker build -t ipytheano .

sudo docker ps

sudo docker rm -f

sudo docker run -d -p 443:8888 -e "PASSWORD=YourPassword" -v ~/ml-sims:/notebooks/ml-sims -v /mnt/volume:/mnt/volume ipytheano
