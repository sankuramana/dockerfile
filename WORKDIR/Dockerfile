# Use Almalinux 9 as the base image
FROM almalinux:9

# Create a new directory called /app
RUN mkdir /app

# Set /app as the working directory
# NOTE: By default, the working directory is "/" (root)
# If we want the container to start in another folder,
# we must set it using WORKDIR
WORKDIR /app

# Show the current working directory (it will print /app)
RUN pwd

# Keep the container running
CMD ["sleep", "1000"]
