# Select base image from https://hub.docker.com/
FROM python:3.8.2-slim-buster

# Set working directory for RUN, CMD, ENTRYPOINT, COPY, and ADD commands
WORKDIR "/application"

# Copy requirements first to leverage Docker caching
COPY requirements.txt /application/requirements.txt

# Upgrade pip
RUN /usr/local/bin/python -m pip install --upgrade pip

# Install pip packages
RUN pip install -r requirements.txt

# Copy all the code inside the container
#COPY . /application

# Run "python run.py command"
#CMD [ "python", "app.py" ]
ENTRYPOINT ["tail"]
CMD ["-f","/dev/null"]

