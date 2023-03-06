FROM python:3.6.0-alpine

RUN pip install MarkupSafe==1.0 flask==0.12.2 pymongo==3.5.1

WORKDIR /app
ADD . /app

ENV POST_DATABASE_HOST post_db
ENV POST_DATABASE posts

ENTRYPOINT ["python3", "post_app.py"]