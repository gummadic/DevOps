FROM python:3.5
MAINTAINER Venkata Gummadi <gummadic@gmail.com>
ADD . /todo
WORKDIR /todo
RUN pip install -r requirements.txt
EXPOSE 5000
COPY api.py .
CMD python api.py