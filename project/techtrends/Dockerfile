FROM python:2.7
LABEL maintainer="Andre Duarch"

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt

EXPOSE 7111

# command to run on container start
CMD [ "python", "app.py" ]