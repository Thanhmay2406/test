FROM python:3.11-alpine
RUN pip install --no-cache-dir redis==5.0.4 requests==2.31.0
COPY worker.py /
CMD ["python", "worker.py"]
