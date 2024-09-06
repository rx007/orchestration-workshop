FROM python:3.13.0rc1-alpine3.20
RUN pip install redis
RUN pip install requests
COPY worker.py /
CMD ["python", "worker.py"]
