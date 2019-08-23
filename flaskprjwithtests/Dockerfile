FROM python:3.7
ADD . ./opt/
WORKDIR /opt/
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
CMD ["python","app.py"]