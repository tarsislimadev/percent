FROM tmvdl/python

WORKDIR /app

COPY . .

RUN python -m pip install nuitka

RUN python -m nuitka hello.py

CMD ls -la
