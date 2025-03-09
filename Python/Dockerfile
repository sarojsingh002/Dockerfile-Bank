# Use the official Python image
FROM python:3.9

# Set the working directory
WORKDIR /usr/src/app

# Copy the requirements file
COPY requirements.txt ./

# Install the dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the source code
COPY . .

# Run the application
CMD ["python", "./your-script.py"]