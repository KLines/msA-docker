FROM hub.idig88.com:8888/micro-service/python:3.6
MAINTAINER liming www.idig8.com

RUN pip install thrift

ENV PYTHONPATH /
COPY message /message
ENTRYPOINT ["python","/message/message_service.py"]

