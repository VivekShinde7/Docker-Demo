# Use a base image with Python 3.8
FROM python:3.8-slim-buster

# Copy the application files
COPY . /app
WORKDIR /app

# Install dependencies with detailed output
RUN pip install --no-cache-dir -v -r requirements.txt

# Run the application
CMD ["python", "app.py"]