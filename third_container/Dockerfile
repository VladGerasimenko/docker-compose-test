FROM python:3.6

RUN mkdir -p /usr/scr/app_3
WORKDIR /usr/scr/app_3

COPY . /usr/scr/app_3
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 3030

CMD ["python", "main.py"]