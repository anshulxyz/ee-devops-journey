FROM python:3.12-slim

WORKDIR /app
COPY requirements.lock ./
RUN PYTHONDONTWRITEBYTECODE=1 pip install --no-cache-dir -r requirements.lock

COPY src .
CMD ["fastapi", "run", "main.py", "--port", "80"]
