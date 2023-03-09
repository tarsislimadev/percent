FROM tmvdl/python:latest

WORKDIR /app

COPY app .

RUN python ./main.py bdist

CMD ls -la ./dist/*.tar.gz
