FROM tmvdl/python

WORKDIR /app

COPY . .

RUN python ./main.py bdist

CMD ls -la ./dist/*.tar.gz
