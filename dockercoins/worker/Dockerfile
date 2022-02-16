FROM python:3.11.0a5-alpine3.15
RUN pip install redis
RUN pip install requests
COPY worker.py /
CMD ["python", "worker.py"]
