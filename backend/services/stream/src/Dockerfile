FROM pltnk/icecast2:latest

WORKDIR /etc/icecast2

COPY ./config/icecast.xml .

EXPOSE 8000 8000

CMD ["icecast", "-c", "/etc/icecast2/icecast.xml"]
