FROM python:3.11-slim

WORKDIR /app
COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

WORKDIR /app

COPY . .

CMD ["python3","-m", "executor.main"]