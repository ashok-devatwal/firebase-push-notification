# Use an official Node.js image as a base
FROM node:18-bullseye

# Set the working directory
WORKDIR /workspace

# Copy over package.json and install dependencies
#COPY package.json yarn.lock ./
#RUN yarn install

# Copy the rest of the application code
COPY . .

# Expose the port Next.js runs on
EXPOSE 3000

# Set the default command to start the development server
#CMD ["yarn", "dev"]
