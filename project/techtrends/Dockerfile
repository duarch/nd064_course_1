FROM python:2.7
LABEL maintainer="Andre Duarch"

COPY . /app
WORKDIR /app
RUN python init_db.py
RUN pip install -r requirements.txt

EXPOSE 3112

# command to run on container start
CMD [ "python", "app.py" ]
