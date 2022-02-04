FROM python:3.10.0b4

WORKDIR /load

COPY requirements.txt /load/

RUN pip install -r requirements.txt

COPY entrypoint.sh /load/
COPY robot-shop.py /load/

CMD ["./entrypoint.sh"]

