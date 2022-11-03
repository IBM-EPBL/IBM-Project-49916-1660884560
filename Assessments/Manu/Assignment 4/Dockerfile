FROM python:3.10-buster

WORKDIR /app

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

CMD ["ibm_db2", "--bind", "0.0.0.0:5000", "app:app"]
