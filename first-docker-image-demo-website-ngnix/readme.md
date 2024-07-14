# Running instructions 
docker build -t ashfirstimage .
docker run -d -p8585:80 ashfirstimage:latest

From local computer browser, http://127.0.0.1:8585/
It will display web page with contents in index.html