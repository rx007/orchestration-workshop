FROM python:3.12.4-alpine3.20
RUN pip install redis
RUN pip install requests
COPY worker.py /
CMD ["python", "worker.py"]
