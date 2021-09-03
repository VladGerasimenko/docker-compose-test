FROM python:3.6

RUN mkdir -p /usr/scr/app_2
WORKDIR /usr/scr/app_2

COPY . /usr/scr/app_2
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5050

CMD ["python", "main.py"]