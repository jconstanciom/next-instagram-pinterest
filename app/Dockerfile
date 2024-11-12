FROM tiangolo/uwsgi-nginx:python3.12

COPY ./requirements.txt /app/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /app/requirements.txt

COPY . .

EXPOSE 8080

CMD [ "python", "app.py" ]
