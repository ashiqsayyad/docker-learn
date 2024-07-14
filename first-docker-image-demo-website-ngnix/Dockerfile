FROM nginx:1.10.1-alpine
# below line will copy index.html from local current directory into nginx container directory /usr/share/nginx/html
COPY index.html /usr/share/nginx/html
# below expose is just a hint to consumer that container is running at port 80 so that consumer can use in publush command -p9090:80
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]