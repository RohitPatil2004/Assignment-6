# Use official Node.js image
FROM node:18

# Set working directory
WORKDIR /

# Copy files
COPY . .

# Install dependencies if you have package.json
RUN npm install

# Expose port 3000
EXPOSE 3000

# Start the frontend
CMD ["node", "server.js"]
