FROM python:3.10

ADD requirements.txt /app/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /app/requirements.txt

ADD meetup /app/meetup
ADD manage.py /app

WORKDIR /app
EXPOSE 8000

CMD ["gunicorn", "meetup.wsgi"]
