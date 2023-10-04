# Use the official Node.js runtime as a parent image
FROM node:20-alpine

# Set the working directory in the container
WORKDIR /src/app
COPY . .

RUN npm install -g @angular/cli

RUN npm install

# Copy the rest of the application code to the container


# Build the Angular app

# Expose a port to run the app
EXPOSE 4200

# Start the Angular app
CMD ["ng", "serve", "--host", "0.0.0.0"]
