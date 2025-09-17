# Use official Python 3.11 image
FROM python:3.11

# Install git and curl
RUN apt-get update && apt-get install -y git curl && rm -rf /var/lib/apt/lists/*

# Set working directory inside container
WORKDIR /workspace
