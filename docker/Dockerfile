# Base image
FROM python:3.12-slim

# Creating working directory
WORKDIR /app

# Copying files to container
COPY . .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Start Django
CMD ["python","manage.py","runserver","0.0.0.0:8000"]
