FROM ubuntu:latest
RUN apt-get -y update
#RUN apt-get install -y parallel wget git

WORKDIR /app
COPY FragGeneScan1.31 /app/FragGeneScan/

ENV PATH=/app/FragGeneScan:$PATH

CMD ["FragGeneScan"]
