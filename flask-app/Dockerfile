#Use Python Image
FROM python:latest

# Install apt dependencies

# RUN sudo apt -update -y

# Copy contents into image
COPY . . 
# run pip dependencies
RUN pip3 install flask flask_sqlalchemy 
# Expose correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT ["/usr/local/bin/python3", "app.py"
