FROM python:3

WORKDIR /RISHI
EXPOSE 5000

ADD . /RISHI
ENV STATIC_URL /static
ENV STATIC_PATH /static

RUN pip install -r requirements.txt


CMD ["python","app.py"]