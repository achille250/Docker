#Use the official Node.js image as the base image
FROM node:latest
#Set the working directory inside the container
WORKDIR /app
# copy the backend files to the container's working directoy
COPY server.js /app/
# Expose port 8080 to allow external access
EXPOSE 80
# start the backend server
CMD ["node", "server.js"]
