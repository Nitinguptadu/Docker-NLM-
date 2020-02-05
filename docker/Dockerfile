FROM python:3

WORKDIR /usr/src/app

COPY Mona_Lisa.jpeg . 
COPY nlm.py .
COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

CMD  ["python", "./nlm.py"] 
