FROM ubuntu:16.04

ENTRYPOINT ["/bin/bash"]

RUN apt-get -y update && apt-get install -y python python-pip python-dev git
RUN pip install --upgrade pip
RUN pip install python-neutronclient python-heatclient==1.2.0 python-openstackclient
