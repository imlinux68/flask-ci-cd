FROM python:3.12.0a7-alpine3.18

WORKDIR /app

COPY requirements.txt ./

RUN pip install -r requirements.txt

EXPOSE 8000

CMD ["python", "./app/run.py"]