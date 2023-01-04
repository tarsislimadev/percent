FROM tmvdl/python

WORKDIR /app

COPY . .

RUN python . bdist

CMD ls -la ./dist/*.tar.gz
