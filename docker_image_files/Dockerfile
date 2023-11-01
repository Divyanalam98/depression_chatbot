FROM python:3.8

COPY requirements.txt .
# Install the dependencies
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Run the Streamlit app
CMD ["streamlit", "run", "app.py"]



