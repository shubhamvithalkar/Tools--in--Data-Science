# Use Python image
FROM python:3.11-slim

# Set working directory
WORKDIR /app

# Copy all files from q9 into container
COPY . /app

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Default command
CMD ["python3"]
