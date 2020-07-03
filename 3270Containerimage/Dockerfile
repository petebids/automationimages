FROM ubuntu:18.04
RUN apt-get update \
    && apt-get install -y --no-install-recommends s3270 \
    && apt-get install -y --no-install-recommends python3 \
    && apt-get install -y --no-install-recommends python3-pip 
RUN pip3 install setuptools
RUN pip3 install py3270 
