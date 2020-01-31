## How to create private network with geth and parity node

### Step1: Install docker on your machine 
  Run following commands in sequence in order to install docker on machine or you can use official documentation of [docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/).

  ```linux
sudo apt update
sudo apt install apt-transport-https ca-certificates curl gnupg-agent software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
sudo apt update
sudo apt install docker-ce
sudo systemctl status docker
sudo apt-get install docker-compose
```
  
### Step2: Create 2 dockers containers. one is used to run geth client node and second will be used to run parity client node 
