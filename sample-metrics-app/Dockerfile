# Use a Python base image
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the Python code
COPY app.py .

# Install required packages
RUN pip install flask prometheus_client

# Expose ports
EXPOSE 5000 8000

# Run the app
CMD ["python", "app.py"]
