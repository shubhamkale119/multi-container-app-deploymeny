# Official node image 
FROM node:16-alpine

# working directory in the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install


# Copy the rest of the application code
COPY . .


#start the application
CMD ["npm", "start"]


# Expose the frontend port
EXPOSE 3000