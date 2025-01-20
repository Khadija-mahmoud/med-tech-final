# Use an official Python image as the base
FROM python:3.10-slim

# Install system dependencies
RUN apt-get update && apt-get install -y \
    default-mysql-client \
    && rm -rf /var/lib/apt/lists/*

# Set the working directory
WORKDIR /workspace

# Copy requirements.txt into the container
COPY requirements.txt /workspace/requirements.txt

# Install Python dependencies
RUN pip install --no-cache-dir -r /workspace/requirements.txt

# Expose port (if your Flask app runs on port 5000)
EXPOSE 5000

# Command to keep the container running (useful for devcontainer setup)
CMD ["sleep", "infinity"]
