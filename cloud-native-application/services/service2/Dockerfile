FROM python:3.9-slim

# Set working directory
WORKDIR /app

# Copy requirements.txt
COPY requirements.txt .

# Install dependencies
RUN pip install -r requirements.txt

# Copy application code
COPY . .

# Expose port (replace 8000 with your service port)
EXPOSE 8000

# Command to run the service
CMD ["python", "app.py"]
