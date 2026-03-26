FROM python:3.11-alpine
RUN pip install --no-cache-dir Flask==3.0.3
COPY hasher.py /
EXPOSE 80
CMD ["python", "hasher.py"]
