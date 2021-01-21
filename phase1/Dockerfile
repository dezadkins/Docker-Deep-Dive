# Project: Extend an existing official image from Docker Hub to run a webserver
FROM nginx:1.19.6-alpine
# Step 1: Use the 'nginx' official image, with the latest version for alpine
#   Pinning a version makes development so much easier because it is predictable
WORKDIR /usr/share/nginx/html
# Step 2: Change our working directory to the root of nginx webhost
#   Using 'WORKDIR /some/path' is preferred to using 'RUN cd /some/path'

# Step 3: Copy in the file or files or folder!
COPY index.html ./
# No need to specify EXPOSE or CMD because they're include in the base (FROM)
