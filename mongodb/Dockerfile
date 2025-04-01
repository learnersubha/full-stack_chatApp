# Use the official MongoDB image
FROM mongo:latest

# Set environment variables for MongoDB
ENV MONGO_INITDB_ROOT_USERNAME=root
ENV MONGO_INITDB_ROOT_PASSWORD=password
ENV MONGO_INITDB_DATABASE=mydb

# Expose MongoDB default port
EXPOSE 27017

# Copy initialization scripts (optional)
COPY init-scripts/ /docker-entrypoint-initdb.d/
