# base OS name
FROM almalinux:9 

# installing nginx on base OS (AlmaLinux)
RUN dnf install -y nginx

# start nginx in the foreground (required for Docker container to stay alive)
CMD ["nginx", "-g", "daemon off;"]
