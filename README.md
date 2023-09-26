# Deploy-Spring-Webapp

Docker Installation:
---------------------
```
sudo apt update
```
```
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y
```
```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```
```
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
```
```
sudo apt update
sudo apt install docker-ce -y
```


SonarQube Setup:
---------------------

```
docker run -d --name sonarqube -e SONAR_ES_BOOTSTRAP_CHECK_DISABLE=true -p 9000:9000 sonarqube:latest
```
login: admin	
password: admin
