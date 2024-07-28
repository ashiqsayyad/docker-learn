# Running instructions 

docker build -t ashfirstimage .

docker run -d -p8585:80 ashfirstimage:latest

From local computer browser, http://127.0.0.1:8585/
It will display web page with contents in index.html

# Some miscellaneous commands
how to find the index.html path inside nginx container

 run nginx container 

 docker run -d -p9090:80 nginx:latest

 Then exec into container and open sh shell inside container with below command

 docker exec -it containrid sh 

 then run following inside container

  find / -type f -name "index.html"

  It will list all index.html files .. then copy the index.html path for nginx which is /usr/share/nginx/html



 

