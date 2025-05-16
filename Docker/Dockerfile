FROM python:3.10-slim

RUN apt-get update && apt-get install -y \
    libssl-dev libffi-dev build-essential \
    && apt-get clean

WORKDIR /app

COPY . /app

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "4n0n-BugHuntingV1.3.py"]
