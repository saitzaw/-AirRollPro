# AirRollPro
project for batch and streaming pipeline 

# Build the project 
docker-compose build

# Run the project 
docker-compose up -d 
docker-compose --profile flower up -d

# permission 
sudo chmod +w dags/
sudo chown -R $USER:$USER dags/
### Note: $USER is current login user, please change the name  