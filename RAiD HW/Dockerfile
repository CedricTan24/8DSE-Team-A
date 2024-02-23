FROM python:3.12.2

WORKDIR /app

COPY ./requirements.txt .

RUN python -m pip install -r requirements.txt

EXPOSE 5252

CMD ["python", "./exercise.py"]