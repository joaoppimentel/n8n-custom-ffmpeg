# Use the official n8n image as a starting point
FROM n8nio/n8n:latest

# Switch to the root user to be able to install programs
USER root

# Update the package list and install ffmpeg
RUN apk update && apt-get install -y ffmpeg

# Switch back to the default n8n user for security
USER node
