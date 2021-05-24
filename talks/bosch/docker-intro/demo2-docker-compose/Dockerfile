FROM python:3.9-alpine

ENV FLASK_APP=app.py
ENV FLASK_RUN_HOST=0.0.0.0

WORKDIR /app

RUN apk add --no-cache gcc musl-dev linux-headers

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

EXPOSE 5000

COPY app.py app.py

CMD ["flask", "run"]
