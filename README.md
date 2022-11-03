# Owncast
## _Repository for compose file_

 1. download and install docker on your local mashine from https://www.docker.com
  
 2. install git at your local mashine
 
 3. start docker
 
 4. open your terminal/shell/PowerShell/Putty
 
 5. change to your prefered directory i.e. to your root directory 
```sh
    cd /
```
 6. clone this repository
```sh
    git clone https://github.com/Fill205/owncast.git
```
7. change in the directory of the repository 
```sh
    cd owncast
```
8. >if you wount to change the default ports of the container, you have to open the docker-compose.yml file and change the ports on the left side from 8080:8080 to i.e. 7500:8080 or 80:8080
 
 
9. start owncast in docker
 
```sh
    docker-compose up -d
```
 10. after docker has start the owncast stage, open your browser and type the url http://localhost:8080/admin  or, if you changed the port, use the new one.
 You also can access to the site, if you host your docker on a cloud server over your domain http://your-domain.com:8080/admin
 
 11. User: admin
     Password: abc123
 
12. you can change now the config of your server, also the username and password
 
13. the deep documentation you can find here: https://owncast.online/docs/
 
14. you can use now obs to stream to your server. Obs is an open soure program. https://obsproject.com/de/download