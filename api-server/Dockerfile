FROM python:3

EXPOSE 5001
COPY . /data
WORKDIR /data
RUN apt-get update 


RUN apt-get clean && \
    rm -rf /var/lib/apt/lists/*


CMD ["python", "socket_server.py"]
