FROM python:3.11-alpine
RUN pip install --no-cache-dir Flask==3.0.3
COPY rng.py /
EXPOSE 80
CMD ["python", "rng.py"]
