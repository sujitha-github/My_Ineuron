FROM python:3.9

COPY . /app

WORKDIR /app

RUN pip install -r requirments.txt

CMD ["python","main.py"]

ENV DEBUG="true"