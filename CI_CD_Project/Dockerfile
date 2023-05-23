FROM python:3.12.0a7-alpine3.18

WORKDIR /app

ENV FLASK_APP=/app/app/run.py

COPY requirements.txt ./

RUN pip install -r requirements.txt

COPY ./ ./

RUN cd app

EXPOSE 8000

CMD [ "flask", "run","--host","0.0.0.0","--port","8000"]