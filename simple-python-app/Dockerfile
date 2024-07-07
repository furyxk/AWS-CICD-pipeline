

# Specify the Base image
FROM python:3.8

# Set the working directory inside the Docker container
WORKDIR /app

# Copy the requirements file
COPY requirements.txt .

# Install the application dependencies
RUN pip install -r requirements.txt

# Copy the application code into the container
COPY . .

# Expose the port the application will be opened on
EXPOSE 5000


# Run the application
CMD ["python", "app.py"]
