# dockerbasic
docker run -it --name NAME ubuntu
apt-get update

//create img
docker build -t dockername/NAME .
docker run -it NAME
exit
login
docker push dockername/NAME

docker run -it --name NAME dockername/NAME
