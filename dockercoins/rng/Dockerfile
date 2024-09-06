FROM python:3.13.0rc1-alpine3.20
RUN pip install Flask
COPY rng.py /
CMD ["python", "rng.py"]
EXPOSE 80
