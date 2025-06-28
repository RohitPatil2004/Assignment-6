# Use official Python image
FROM python:3.11

# Set work directory
WORKDIR /

# Copy files
COPY . .

# Install dependencies
RUN pip install -r requirements.txt

# Expose port 5000
EXPOSE 5000

# Run the backend
CMD ["python3", "app.py"]
