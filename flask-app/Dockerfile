#Use Python Image
FROM python:latest

# Install apt dependencies

# RUN sudo apt -update -y
RUN apt update
RUN apt install python3-pip -y
# Copy contents into image
COPY . . 
# run pip dependencies
RUN pip3 install pymysql flask flask_sqlalchemy 
# Expose correct port
EXPOSE 5001
# Create an entrypoint
ENTRYPOINT ["/usr/local/bin/python3", "app.py"]
