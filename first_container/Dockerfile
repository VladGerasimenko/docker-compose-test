FROM python:3.6

RUN mkdir -p /usr/scr/app_1
WORKDIR /usr/scr/app_1

COPY . /usr/scr/app_1
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8080

CMD ["python", "main.py"]