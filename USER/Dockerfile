FROM almalinux:9

# Install packages (requires root access)
RUN dnf install nginx -y 

# Creating a normal user (requires root access)
RUN useradd ramana

# All configurations, installations, and system changes must be done as root.
# After finishing the tasks that need root permissions,
# switch to a normal user to avoid running the container as root.
# This prevents the container from having full access to the host storage.

# Switch to non-root user for safer container execution
USER ramana

# Run a long sleep to keep the container alive (spelling fixed)
CMD [ "sleep", "1000" ]
